# Redirecione para o whatsapp e acione o pixel de marketing (PT)

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

# Redirect to Whatsapp with marketing Pixel (EN)

If you have difficulty measuring how many people click the WhatsApp button, this option facilitates your measurement.

This script does the following:

1) Defines a GetParameterbyname function for URL parameters. This function analyzes the current URL in search of the specified parameters.
2) Get the values of the "Phone" and "text" parameters of the URL using the GetParameterbyname function.
3) Wait 3 seconds (3000 milliseconds) using settimeout.
4) After 3 seconds, redirects to the WhatsApp page with the "Phone" and "Text" parameters received from the URL.
5) You can incorporate this code into an HTML page and then access the page as follows:

``` javascript
http://seusite.com/suapagina.html?phone=xxx&text=xxx
```

Remember to replace http://seusite.com/suapagina.html with the real URL of your HTML page and define the appropriate values for "XXX" in the "Phone" and "Text" parameters.
