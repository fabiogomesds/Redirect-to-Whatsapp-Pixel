# Redirect-to-Whatsapp-Pixel

Se você tem dificuldade em mensurar quantas pessoas clicam no botão de whatsapp, esta opção facilita seu mensuração.

Este script faz o seguinte:

1) Define uma função getParameterByName para obter parâmetros da URL. Essa função analisa a URL atual em busca dos parâmetros especificados.
2) Obtém os valores dos parâmetros "phone" e "text" da URL usando a função getParameterByName.
3) Aguarda 3 segundos (3000 milissegundos) usando setTimeout.
4) Após os 3 segundos, redireciona para a página do WhatsApp com os parâmetros "phone" e "text" recebidos da URL.
5) Você pode incorporar esse código em uma página HTML e, em seguida, acessar a página da seguinte maneira:

``` javascript
http://seusite.com/suapagina.html?phone=xxx&text=xxx
```
Lembre-se de substituir http://seusite.com/suapagina.html pelo URL real da sua página HTML e definir os valores apropriados para "xxx" nos parâmetros "phone" e "text".
