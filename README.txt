Vinkällarmästaren – inköpsställe
Ändringar:
- Nytt fält Inköpsställe: Cavarosa eller Systembolaget.
- Visas på varje vinkort.
- Följer med i Excel-exporten och läses vid Excel-import.
- Befintliga viner får automatiskt inköpsställe enligt användarens lista:
  VIN-0001, 0002, 0003, 0004, 0006, 0007, 0009 = Cavarosa
  VIN-0005, 0008 = Systembolaget
- Saknade inköpsställen i befintlig lokal data kompletteras automatiskt utan att radera övriga uppgifter.
- Standardförvaring sätts till Vinkyl om den saknas.

Installera:
1. Gör först en JSON-säkerhetskopia i appen.
2. Ersätt index.html i GitHub-repositoryt med den här filen och spara ändringen.
3. Öppna appen i Safari och uppdatera sidan. Om den gamla versionen visas, stäng fliken helt och öppna igen.
4. Kontrollera att inköpsställe visas på vinkorten.
5. Exportera Excel och kontrollera kolumnen Inköpsställe.

Obs: appen sparar fortfarande data lokalt i webbläsaren och synkroniserar inte automatiskt med iCloud. Den här ändringen ska inte återställa eller radera befintliga lokala viner.
