<!DOCTYPE html>
<html lang="pl">

<head>
  <meta charset="utf-8"/>
  <title>JS innerHTML</title>
  
  <script>
  
  function z1()
  {
    document.getElementById("z1").innerHTML="Jedna bogini dostała jabłko z koszykiem";
  }
  function z2()
  {
  document.getElementById("z1").innerHTML="Tu znajdziesz odpowiedz";
  }
  
  function z3()
  {
    document.getElementById("z3").innerHTML="Jutro";
  }
  function z4()
  {
  document.getElementById("z3").innerHTML="Tu znajdziesz odpowiedz";
  }
  
  function z5()
  {
    document.getElementById("z5").innerHTML="Trzy";
  }
  function z6()
  {
  document.getElementById("z5").innerHTML="Tu znajdziesz odpowiedz";
  }
  
  function z7()
  {
    document.getElementById("z7").innerHTML="Nie padało";
  }
  function z8()
  {
  document.getElementById("z7").innerHTML="Tu znajdziesz odpowiedz";
  }
  
  function z9()
  {
    document.getElementById("z9").innerHTML="W słowniku";
  }
  function z10()
  {
  document.getElementById("z9").innerHTML="Tu znajdziesz odpowiedz";
  }
  
  
  </script>
</head>


<body>

  <h2>Zagadki logiczne:<h2>
  <p>
  Parys miał w koszu 3 jabłka, które rozdał 3 boginiom tak, że każda z nich dostała jedno jabłko, ale jedno jabłko zostało w koszyku. Jak to możliwe?
  </p>
  <input type="button" value="zobacz odpowiedz" onclick="z1()">
 </br> </br>
 <div id = "z1">Tu znajdziesz odpowiedz</div>
 </br>
 </br>
  <input type="button" value="ukryj odpowiedz" onclick="z2()">
  
  <p>
  Zawsze przyjdzie, ale nigdy nie przyjdzie dzisiaj. Co to takiego?
  </p>
  <input type="button" value="zobacz odpowiedz" onclick="z3()">
 </br> </br>
 <div id = "z3">Tu znajdziesz odpowiedz</div>
 </br>
 </br>
  <input type="button" value="ukryj odpowiedz" onclick="z4()">
  
  <p>
  Szły gęsi gęsiego – jedna za drugą. Ile było gęsi?
  </p>
  <input type="button" value="zobacz odpowiedz" onclick="z5()">
 </br> </br>
 <div id = "z5">Tu znajdziesz odpowiedz</div>
 </br>
 </br>
  <input type="button" value="ukryj odpowiedz" onclick="z6()">
  
  <p>

Jeśli troje dzieci i ich trzy psy nie znajdowało się pod parasolem, to jak to się stało, że żadne z nich nie zmokło?
  </p>
  <input type="button" value="zobacz odpowiedz" onclick="z7()">
 </br> </br>
 <div id = "z7">Tu znajdziesz odpowiedz</div>
 </br>
 </br>
  <input type="button" value="ukryj odpowiedz" onclick="z8()">
  
  <p>
   Gdzie czwartek  jest przed środą?
  </p>
  <input type="button" value="zobacz odpowiedz" onclick="z9()">
 </br> </br>
 <div id = "z9">Tu znajdziesz odpowiedz</div>
 </br>
 </br>
  <input type="button" value="ukryj odpowiedz" onclick="z10()">
