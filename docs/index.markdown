---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Nosso travelogue do Egito
## Hoje, 11 de Agosto
### _Aqui você verá as últimas informações da nossa viagem_

**📍 Cidade que estamos:** Luxor<br/>
**🌡️ Temperatura:** 32 °C<br/>
**🏛️ Visitaremos:** Dahab
<p id="time">
    <script>
        var timeDisplay = document.getElementById("time");
        function refreshTime() {
            var dateString = new Date().toLocaleString("pt-BR", {timeZone: "Africa/Cairo"});
            var justTime = dateString.split(", ")[1];
            timeDisplay.innerHTML = "<p><strong>🕙 Horário aqui:</strong> "+justTime;
        }
        setInterval(refreshTime, 1000);
    </script>
</p>

## Últimos posts
### _O que estivemos fazendo nos últimos dias?_

<br/>

## Viagem
[ 📅 Ver roteiro completo](https://pietroid.github.io/egypt-travelogue/viagem/2024/08/04/roteiro.html) <br/>
[ ⏮️ Ver próximo dia]() <br/>
[ ⏭️ Ver dia anterior]() <br/>