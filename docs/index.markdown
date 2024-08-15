---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Nosso travelogue do Egito
## Hoje, 15 de Agosto
### _Aqui você verá as últimas informações da nossa viagem_

**📍 Cidade que estamos:** Cairo<br/>
**🌡️ Temperatura:** 34 °C<br/>
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

[Coração - parte 1 (Aswan)](https://pietroid.github.io/egypt-travelogue/contos/2024/08/05/coracao-parte-1.html)
[Coração - parte 2 (Aswan)](https://pietroid.github.io/egypt-travelogue/contos/2024/08/05/coracao-parte-2.html)
[Khan el Khalili - A 25 de março do Cairo](https://pietroid.github.io/egypt-travelogue/locais/2024/08/04/khan-el-khalili.html)

<br/>

## Viagem
[ 📅 Ver roteiro completo](https://pietroid.github.io/egypt-travelogue/viagem/2024/08/04/roteiro.html) <br/>
[ ⏮️ Ver próximo dia]() <br/>
[ ⏭️ Ver dia anterior]() <br/>