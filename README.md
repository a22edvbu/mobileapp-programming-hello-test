
# Rapport

**Skriv din rapport här!**

_Du kan ta bort all text som finns sedan tidigare_.

## Följande grundsyn gäller dugga-svar:

- Ett kortfattat svar är att föredra. Svar som är längre än en sida text (skärmdumpar och programkod exkluderat) är onödigt långt.
- Svaret skall ha minst en snutt programkod.
- Svaret skall inkludera en kort övergripande förklarande text som redogör för vad respektive snutt programkod gör eller som svarar på annan teorifråga.
- Svaret skall ha minst en skärmdump. Skärmdumpar skall illustrera exekvering av relevant programkod. Eventuell text i skärmdumpar måste vara läsbar.
- I de fall detta efterfrågas, dela upp delar av ditt svar i för- och nackdelar. Dina för- respektive nackdelar skall vara i form av punktlistor med kortare stycken (3-4 meningar).

Programkod ska se ut som exemplet nedan. Koden måste vara korrekt indenterad då den blir lättare att läsa vilket gör det lättare att hitta syntaktiska fel.

```
function errorCallback(error) {
    switch(error.code) {
        case error.PERMISSION_DENIED:
            // Geolocation API stöds inte, gör något
            break;
        case error.POSITION_UNAVAILABLE:
            // Misslyckat positionsanrop, gör något
            break;
        case error.UNKNOWN_ERROR:
            // Okänt fel, gör något
            break;
    }
}
```

Bilder läggs i samma mapp som markdown-filen.

![](android.png)

-----------------------------------------------------------------------------------

Först av allt skapade jag ett nytt GitHub konto som kommer användas för skolprojekt. Sedan forkade jag kursens repositary så jag får min egen kopia att arbeta med utan att påverka originalfilerna. Mitt egna repositary laddades ner genom GitHub Desktop, som gör att filerna alltid är uppdaterade med molnet hos GitHub. 
Sedan öppnade jag filerna som ett projekt i Android Studio, där jag sedan ändrade texten “Hello” i filen strings.xml till “TjenaTjena”. En kort beskrivning skrevs där jag skrev ändringen och commitade och till sist pushade jag detta.

![](screenshot1.png)

```
<resources>
    <string name="app_name">TjenaTjena</string>
</resources>
```