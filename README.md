# formulier
formulierpagina opdracht 1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <article>
        <h1>Aanmelden</h1>
<p>
Bent u geïnteresseerd in samenwerken met CMD Amsterdam? Dat kan! <br>
Tijdens de opleiding werken studenten aan projecten voor echte opdrachtgevers. Ook
    lopen de studenten stage, in het tweede en afstudeerjaar.</p>

<p><i>CMD Amsterdam zoekt altijd naar positieve verbindingen met de creatieve stad
    Amsterdam.</i></p>

<p>Voor het aanmelden van stageplekken of projecten kunt u onderstaand formulier invullen. <br>
Wij nemen zo nodig contact met u op nadat het formulier is verstuurd. <br>
    Voor vragen of opmerkingen kunt u <a href="url">contact</a> met ons op.</p>

       <form>
          <fieldset>
           <legend> <h3>Contactgegevens:</h3></legend>
                Naam<br>
                    <input type="text" name="Naam" placeholder="bv. Jan Janssen"><br>
                Bedrijf<br>
                    <input type="text" name="Bedrijf" placeholder="bv. Microsoft"><br>
                Adres <br>
                    <input type="text" name="Adres" placeholder="bv. Dorpstraat 22"><br>
                Postcode <br>
                    <input type="text" name="Postcode" placeholder="1234 AA"><br>
                Plaats <br>
                    <input type="text" name="Plaats" placeholder="bv. Amsterdam"><br>
                Telefoon <br>
                    <input type="tel" name="Telefoon" placeholder="bv. 0612345678"><br>
                Email <br>
                    <input type="email" name="email" placeholder="bv. j.janssen@gmail.com"><br>
           </fieldset> <br>
           <fieldset>
               <legend><h3>Ik wil me aanmelden:</h3></legend>
                    <input type="radio" name="Voor een project" value="male">Voor een project
                      <br>
                    <input type="radio" name="Als stagebedrijf" value="female">Als stagebedrijf
           </fieldset> <br>
           <fieldset>
           <legend><h3>Project</h3></legend>
                Titel<br>
                    <input type="text" name="Titel"> <br>
                Opdrachtomschrijving<br>
                    <textarea rows="4" cols="50"></textarea> <br>
                Doelgroepomschrijving <br>
                    <textarea rows="4" cols="50"></textarea> <br>
                Doelstelling/intentie van het project <br>
                    <textarea rows="4" cols="50"></textarea> <br>
                Looptijd <br>
                    <input type="text" name="Looptijd"> <br>
                Deadline <br>
                    <input type="date" name="deadline">
           </fieldset>
            <fieldset>
               Geschikt voor: <br>
                   <input type="checkbox" name="1e" value="1e">Eerstejaars studenten <br>
                   <input type="checkbox" name="2e" value="2e">Tweedejaars studenten <br>
                   <input type="checkbox" name="3e" value="3e">Derdejaars studenten <br>
                   <input type="checkbox" name="afstudeer" value="afstuurd">Afstudeer studenten <br>
                   <input type="radio" name="onbekend" value="onbekend">Onbekend <br>
            </fieldset> <br>
            <fieldset>
                <legend><h3>Stage</h3></legend>
                   Geschikt voor: <br>
                    <input type="checkbox" name="2e" value="2e">Tweedejaars studenten <br>
                    <input type="checkbox" name="afstudeer" value="afstuurd">Afstudeer studenten <br>
                    <input type="radio" name="onbekend" value="onbekend">Onbekend <br>
            </fieldset>
            <fieldset>
                    Hoe lang is de stage? <br>
                     <input type="radio" name="onbekend" value="onbekend">10 weken <br>
                     <input type="radio" name="onbekend" value="onbekend">20 weken <br>
                    Begin datum
                     <input type="date" name="deadline" placeholder="begindatum"> <br>
                    Beschrijving werkzaamheden: <br>
                    <textarea rows="4" cols="50"></textarea> <br>
            </fieldset>
        </form>
    </article>
</body>
</html>
