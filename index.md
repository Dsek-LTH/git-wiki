#  [✏️](/edit/master/./index.md)

## Guide Hur man gör ett fint wiki-testamente:
    * Forka detta repo
    * Lägg till mappar, markdown filer som till exempel [denna](testmapp/testfil.md)
    * Kör ./updateHeaders.sh scriptet
    * Commita och pusha!
    * Sätt upp i github så master blir din githubpages
    * Nu finns testamentet som hemsida, trycker man på pennan så kan man redigera rakt i webbläsaren!

### Exkludera från hemsidan

    Vill man exkludera en fil från att finnas med på hemsidan, skriv
    ```
    ---
    nav_exclude: true
    ---
    ```
    längst upp i den!
