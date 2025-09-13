# intro-slutuppgift

# CI Check – GitHub Actions 🚀

Detta repo innehåller en övning i att använda **GitHub Actions** för att skapa ett enkelt CI-flöde.
Workflowen körs automatiskt vid varje `push` och gör följande:

- Visar ett meddelande i Actions-loggen
- Kör en enkel check för att bekräfta att allt fungerar
- Skickar resultatet till en Discord kanal (via webhook)

Dessutom finns en mapp med två filer: **reflektion.txt** och **fragor.txt**,
som har pushats i två separata branches och sedan mergats via pull requests.
