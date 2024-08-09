---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Nosso travelogue do Egito
## Hoje, 09 de Agosto
### _Aqui você verá as últimas informações da nossa viagem_
<style>
    .timestamp {
        color: #00000098;
        font-size: 0.7rem;
        font-family: 'Literata', serif;
        margin: 0rem 0;
    }
</style>
<p class="timestamp"><strong>🕙 Horário aqui:</strong></p>
<p class="timestamp">
    <script>
        var timeDisplay = document.getElementById("timestamp");

        function refreshTime() {
        var dateString = new Date().toLocaleString("pt-BR", {timeZone: "Africa/Cairo"});
        var justTime = dateString.split(", ")[1];
        timeDisplay.innerHTML = justTime;
        }

        setInterval(refreshTime, 1000);
    </script>
</p>

**📍 Cidade que estamos:** Luxor<br/>
**🌡️ Temperatura:** 43 °C<br/>
**🏛️ Visitaremos:** Templo de Hathor em Dendera e de Osíris em Abydos

## Últimos posts
### _O que estivemos fazendo nos últimos dias?_

<br/>

## Viagem
[ 📅 Ver roteiro completo](https://pietroid.github.io/egypt-travelogue/viagem/2024/08/04/roteiro.html) <br/>
[ ⏮️ Ver próximo dia]() <br/>
[ ⏭️ Ver dia anterior]() <br/>