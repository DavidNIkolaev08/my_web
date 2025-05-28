1
<!DOCTYPE html>
2
<html>
3
<head>
4
<title>Тьрсене на човек по ID</title>
5
</head>
6
<body>
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
<<1>Търсене на човек по ID</h1>
<label for="personId">Вьведи ID: </label>
<input type="number" id="personId" min="1" />
<button onclick="searchPerson()">Тьpcи</button>
<pre_id="result"></pre>
<script>
// Данни за хора (като "база данни" в масив от обекти) const people
];
=
[
{ id: 1, name: "Иван Иванов", age: 30, city: "Cooия" },
{ id: 2, name: "мария Петрова", age: 25, city: "Пловдив" },
{ id: 3, name: "гeopги гeоpгиев", age: 40, city: "Bapнa" },
function searchPerson() {
const input = document.getElementById("personId"); 
  const result = document.getElementById("result"); 
  const id = Number(input.value);
