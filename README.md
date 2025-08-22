# Veiledning for studenter: Slik jobber du med øvinger på GitHub

Hva er GitHub Codespaces?
GitHub Codespaces er et utviklingsmiljø i skyen som kjører direkte i nettleseren. Det gir deg tilgang til Visual Studio Code med alle filene 
fra prosjektet ditt, slik at du kan programmere, teste og lagre endringer uten å måtte installere noe på din egen PC.

## Del 1: Leg en Fork repository med øvingen



### Steg 1: Finn øvingsrepositoryet
1. Åpne nettleseren og gå til GitHub (github.com)
2. Logg inn med din GitHub-konto (opprett konto først hvis du ikke har)
3. Gå til lenken til øvingsrepositoryet som læreren har delt med deg. Hvis dette er din første øving - kan du gjerne bruke dette repositoryet som et eksempel!

### Steg 2: Lag en fork
1. Når du er inne på øvingsrepositoryet, klikk på **"Fork"**-knappen øverst til høyre på siden
   - Knappen ser ut som en gaffel-ikon med tallet på antall forks ved siden av
2. Du kommer nå til en side som heter "Create a new fork"
3. **VIKTIG**: La følgende innstillinger stå som de er:
   - Owner: Din egen GitHub-konto (skal allerede være valgt)
   - Repository name: La navnet være som det er
   - Description: Valgfritt, men du kan la den stå tom
   - "Copy the main branch only" skal være huket av
4. Klikk på den grønne knappen **"Create fork"**
5. Vent noen sekunder mens GitHub lager din personlige kopi
6. Du blir automatisk sendt til din egen fork når den er ferdig

### Hvordan vite at du har gjort det riktig?
- URL-en i nettleseren skal nå vise: `github.com/DITT-BRUKERNAVN/repository-navn`
- Under repository-navnet står det "forked from [original-repository]"
- Du har nå din egen kopi som du kan jobbe med!

## Del 2: Opprett GitHub Codespace

### Steg 1: Start Codespace fra din fork
1. **VIKTIG**: Sørg for at du er på DIN fork (sjekk at ditt brukernavn står i URL-en)
2. Klikk på den grønne **"Code"**-knappen (midt på siden, over fillisten)
3. I menyen som dukker opp, klikk på fanen **"Codespaces"** (ved siden av "Local" og "SSH")

### Steg 2: Opprett nytt Codespace
1. Klikk på den grønne knappen **"Create codespace on main"**
   - Hvis du allerede har et codespace, vil du se det listet opp. Du kan enten:
     - Klikke på det eksisterende for å gjenbruke det
     - Eller klikke på pluss-ikonet (+) for å lage et nytt
2. Vent mens GitHub setter opp ditt utviklingsmiljø (dette kan ta 1-3 minutter første gang)
3. Du vil se en lasteindikator og tekst som "Setting up your codespace..."

### Steg 3: Codespace er klart
1. Når lasting er ferdig, åpnes VS Code direkte i nettleseren
2. Du ser nå:
   - Filutforskeren til venstre med alle filer fra øvingen
   - En terminal nederst hvor du kan kjøre kommandoer
   - Hovedvinduet hvor du kan redigere kode
3. Du er nå klar til å begynne med øvingen!

## Viktige tips

### Lagre arbeidet ditt
- Codespace lagrer automatisk endringer lokalt
- For å lagre til GitHub (anbefales jevnlig):
  1. Klikk på Source Control-ikonet i venstre meny (ser ut som forgreninger)
  2. Skriv en beskrivelse av hva du har gjort
  3. Klikk "Commit" og deretter "Sync Changes"

### Stoppe og starte Codespace
- **Stoppe**: Lukk nettleser-fanen eller gå til github.com/codespaces og klikk "Stop"
- **Starte igjen**: 
  1. Gå til github.com/codespaces
  2. Finn ditt codespace i listen
  3. Klikk på navnet for å åpne det

### Slette Codespace når du er ferdig
1. Gå til github.com/codespaces
2. Finn codespace du vil slette
3. Klikk på de tre prikkene (...) til høyre
4. Velg "Delete"
