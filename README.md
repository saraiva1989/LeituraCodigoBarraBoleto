# Ler Código de Barras de Boleto e Contas de Consumo.
Página Web para leitura de código de barra de conta de consumo e boleto de cobrança. Passei muito tempo pesquisando como 
funciona para ler o código de barras de boleto e retornar a linha digitável, e descobri que a linha digitável 
não é o mesmo valor que o código de barra. Sendo assim é feito um algoritmo que de acordo com o código de barra é gerado 
sua linha digitável.

Sendo assim esse código é apenas para quem tem interesse em ler o código de barra e ter como retorno a linha digitável

<img src="https://saraiva89.com/dev/leituraboleto/leituracodigobarra.GIF" width="50%">

### para esse projeto é utilizado a biblioteca quagga.js, veja sua documentacão aqui: https://serratus.github.io/quaggaJS/#api

## Observação

Para ler código de barra é necessário utilizar a câmera do celular, e os navegadores permitem fazer o uso da câmera apenas 
em sites que possui SSL (https). Sendo assim para que possa ser feito os teste é necessário que a página esteja em uma 
hospedagem e que o domínio tenha SSL. Na máquina local funcionará apenas na webcam do notebook (ou caso consiga simular um 
ssl em sua rede local).

Url para teste: https://saraiva89.com/dev/leituraboleto/
