# lab7-5
<html>
<head>
<meta charset="UTF-8" />
<script>
{
            let input = parseInt(window.prompt("Тоот өг"));
            window.alert("1 орцонд 8 давхар ба 1 давхарт 4 айл байгаа гэж үзье.");
            if (input == 0) {
                console.log('podvol?')
                return 0;
            }
            let orts = parseInt(input % 32) == 0 ? parseInt(input / 32) : parseInt(input / 32 + 1);
            let davhar = (orts == 1) ? parseInt(input / 4) : parseInt((input - 32 * (orts - 1)) / 4);
            let toot = (input % 4 == 0) ? 4 : input % 4;
            console.log('orts: ' + orts);
            console.log('davhar: ' + davhar);
            console.log('haalga: ' + toot);

        }
</script>
</head>
<body>
   <a href="https://munkhtulga0826.github.io/lab7/">bod1<a>
  <a href="https://munkhtulga0826.github.io/lab7-2/">bod2<a>
   <a href="https://munkhtulga0826.github.io/lab7-3/">bod3<a>
    <a href="https://munkhtulga0826.github.io/lab7-4/">bod4<a>
</body>
</html>
