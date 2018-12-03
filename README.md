<!DOCTYPE html>
<html lang="nl">

<head>
    <title>Formelier</title>
    <meta charset="UTF-8">
</head>

<body>
  <form action="http://bla.hosts.ma-cloud.nl/pop.php" method="get">
    <h1>Een plan voor jouw ontwikkeling</h1>
    <p>Om een eerste stap te zetten naar een persoonlijk opleidingplan zul je eerst een paar vragen voor jezelf moeten beantoorden. Dit formulier helpt jou daar bij.</p>
    Naam: <input type="text" name="Naam" placeholder="Bv. Joep Janssen">
    <select>
      <option value="">selecteer jouw klas</option>
      <option value="MG1A">MG1A</option>
      <option value="MG1B">MG1B</option>
      <option value="MG1C">MG1C</option>
      <option value="MG1D">MG1D</option>
      <option value="MG2A">MG2A</option>
      <option value="MG2B">MG2B</option>
      <option value="MG2C">MG2C</option>
      <option value="MG2D">MG2D</option>
    </select>

  <fieldset>
    <legend>welbevinden</legend>
    <p>Hoe positief ben je op dit moment over je opleiding?</p>
    <br>
    <input type="radio" name="posetief" value="0"> 0
    <input type="radio" name="posetief" value="1"> 1
    <input type="radio" name="posetief" value="2"> 2
    <input type="radio" name="posetief" value="3"> 3
    <input type="radio" name="posetief" value="4"> 4
    <input type="radio" name="posetief" value="5"> 5
    <input type="radio" name="posetief" value="6"> 6
    <input type="radio" name="posetief" value="7"> 7
    <input type="radio" name="posetief" value="8"> 8
    <input type="radio" name="posetief" value="9"> 9
    <input type="radio" name="posetief" value="10"> 10
    <br>
    <p>Hoe gemotiveerd ben je momenteel om de opleiding af te maken?</p>
    <br>
    <input type="radio" name="gemotiveerd" value="0"> 0
    <input type="radio" name="gemotiveerd" value="1"> 1
    <input type="radio" name="gemotiveerd" value="2"> 2
    <input type="radio" name="gemotiveerd" value="3"> 3
    <input type="radio" name="gemotiveerd" value="4"> 4
    <input type="radio" name="gemotiveerd" value="5"> 5
    <input type="radio" name="gemotiveerd" value="6"> 6
    <input type="radio" name="gemotiveerd" value="7"> 7
    <input type="radio" name="gemotiveerd" value="8"> 8
    <input type="radio" name="gemotiveerd" value="9"> 9
    <input type="radio" name="gemotiveerd" value="10"> 10
    <br>
    <p>Hoeveel vertrouwen heb je momenteel in je eigen kunnen?</p>
    <br>
    <input type="radio" name="vertrouwen" value="0"> 0
    <input type="radio" name="vertrouwen" value="1"> 1
    <input type="radio" name="vertrouwen" value="2"> 2
    <input type="radio" name="vertrouwen" value="3"> 3
    <input type="radio" name="vertrouwen" value="4"> 4
    <input type="radio" name="vertrouwen" value="5"> 5
    <input type="radio" name="vertrouwen" value="6"> 6
    <input type="radio" name="vertrouwen" value="7"> 7
    <input type="radio" name="vertrouwen" value="8"> 8
    <input type="radio" name="vertrouwen" value="9"> 9
    <input type="radio" name="vertrouwen" value="10"> 10
    <br>
  </fieldset>
  <fieldset>
    <legend>sterke kanten</legend>
    <p>wat zijn jouw sterke kanten?</p>
    <input type="checkbox" name="Sterkte" value="Coderen in HTML/CSS"> Coderen in HTML/CSS
    <input type="checkbox" name="Sterkte" value="Programmeren in Java"> Programmeren in Java
    <input type="checkbox" name="Sterkte" value="Scripting: programmeren in JavaScript"> Scripting: programmeren in JavaScript
    <input type="checkbox" name="Sterkte" value="planning"> planning
    <input type="checkbox" name="Sterkte" value="Samenwerken"> Samenwerken
  </fieldset>

  <fieldset>
    <legend>Nog te ontwikkelen</legend>
    <p>Aan welke skills moet je nog extra aandacht besteden?</p>
    <input type="checkbox" name="Zwakte" value="Coderen in HTML/CSS"> Coderen in HTML/CSS
    <input type="checkbox" name="Zwakte" value="Programmeren in Java"> Programmeren in Java
    <input type="checkbox" name="Zwakte" value="Scripting: programmeren in JavaScript"> Scripting: programmeren in JavaScript
    <input type="checkbox" name="Zwakte" value="planning"> planning
    <input type="checkbox" name="Zwakte" value="Samenwerken"> Samenwerken
  </fieldset>

  <fieldset>
    <legend>Vrije tijd</legend>
    <p>Wat doe je in je vrije tijd?</p>
    <textarea name="vrije tijd" rows="2" cols="55"></textarea>
  </fieldset>

  <p>Wat zijn jouw plannen voor de toekomst?</p>
  <textarea name="toekomstplannen" rows="9" cols="55"></textarea>
  <input type="submit" value="Versturen">
  <p> </p>
  <input type="search" value="zoeken" placeholder="zoeken">
    <footer>
        <div id="validatie">
            <a href="http://validator.w3.org/check?uri=referer" target="_blank">
                <img src="http://blog.boyet.com/blog/files/media/image/valid-html5-blue.png" alt="Valide HTML5"></a>
            <a href="http://jigsaw.w3.org/css-validator/check/referer" target="_blank">
                <img src="http://jigsaw.w3.org/css-validator/images/vcss-blue.gif" alt="Valide CSS">
            </a>
        </div>
    </footer>
  </form>
</body>

</html>
