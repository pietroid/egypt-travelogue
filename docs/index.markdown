---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---



# Nosso travelogue do Egito
## Hoje, 08 de Agosto
### _Aqui você encontra todas as informações da nossa viagem_
<div>
<p style="display:inline"><strong>🕙 Horário aqui:</strong></p>
<p style="display:inline" id="time">
    <script>
        var timeDisplay = document.getElementById("time");

        function refreshTime() {
        var dateString = new Date().toLocaleString("pt-BR", {timeZone: "Africa/Cairo"});
        var justTime = dateString.split(", ")[1];
        timeDisplay.innerHTML = justTime;
        }

        setInterval(refreshTime, 1000);
    </script>
</p>
</div>
**📍 Cidade que estamos:** Luxor <br/>
**🌡️ Temperatura:** 42 °C <br/>
**🏛️ Visitaremos:** Templo de Karnak e Templo de Luxor <br/>

<br/>

## Últimos posts
### _O que estivemos fazendo nos últimos dias?_

<br/>

## Viagem
[ 📅 Ver roteiro completo]() <br/>
[ ⏮️ Ver próximo dia]() <br/>
[ ⏭️ Ver dia anterior]() <br/>