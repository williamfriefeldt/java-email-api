# Hej Jon!

Här är kodbasen (repository) där jag tänker att du ska bygga ett Java API som man kan skicka mail från.

Jag tänker att vi gör det som uppgifter där jag ger dig en uppgift som du sedan får göra genom att pusha upp koden till en egen branch och sen göra en **pull request** (du kommer fatta vad det är snart).

För att kunna gära detta tänker jag att första uppgiften kommer handla om `git`.

# Git och GitHub

Git är ett versionhanteringsprogram/språk som gör att man kan spara sin kod och dela den med andra. Med hjälp av git pushar man upp sin kod till GitHub där andra kan ladda ner den och göra ändringar

# Uppgift

Första uppgiften blir att klona detta repository till din dator, skapa en egen branch, svara på de frågor står i `README.md` genom att fylla i de tomma raderna. Sedan pusha upp koden och göra en pull request.

- Första steget är att [installera git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Klicka sedan på `Code` på denna sida och välj Clone -> SSH.
- Kopiera länken och öppna din Terminal, ställ dig i en folder du vill lägga projektet i och skriv `git clone [länk]`
- Projektet kommer nu laddas ner.
- Gå in i projektet genom att skriva `cd [projektets-namn]` i Terminalen.
- Om du nu skriver `git status` ska det stå vilken branch du är på (`main`).
- Skapa nu en ny branch med `git checkout -b [branchen namn]`. Branchens namn ska beskriva det du ska ändra.
- Besvara sedan frågorna nedan genom att ändra i `README.md`, öppna programmet i Intellij.
- När du är klar skriver du `git add *` för att lägga till de filerna du ändrat, i Terminalen. (Innan du gör det kan du kolla de ändrade filerna med `git status`)
- Sen skriver du `git commit -m "[meddelande som beskriver ändringarna]"`.
- Sist gör du `git push` för att pusa till GitHub.
- På GitHub kan du nu se din branch och på **Pull requests** kan du skapa ett förslag på ändringar som borde in i main branchen, en så kallad pull request. Välj då att koden ska från din branch till main så kommer du se ändringarna.
- Skriva vad du ändrat, skapa pull requesten och skicka den till mig.

# Troubleshoot

- För att göra ovan måste du skapa ett konto på GitHub.
- Du kan behöva ha en SSH-nyckel för att ha tillåtelse att pusha kod till GitHub. [https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](Här) finns instruktioner på hur du skapar en. Det kan vara lite klurigt på hör av dig om du kör fast.

# Frågor

1. Vilket kommand gör du med git för att checka ut en ny branch som heter `feature/jon-is-cool`?

2. Vad skulle detta Java program skriva ut om man startade det?

3. Om man vill lägga till ett nytt bibliotek (dependency) i ett Java program, var lägger man det då?

4. Vad gör filen `.gitignore`?

5. Vad är skillnaden på filen `main` och `test` i ett Java program?

# Tips

- Fråga hellre mycket än lite! Bara att skriva till mig :)
- Läs detta [https://www.w3schools.com/git/git_intro.asp?remote=github](https://www.w3schools.com/git/git_intro.asp?remote=github)
- Kolla denna [https://www.youtube.com/watch?v=iv8rSLsi1xo](https://www.youtube.com/watch?v=iv8rSLsi1xo)
