# Quadratic-equation

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Assignment On Quadratic Eqaution</title>
  </head>
  <body>
    <script>
      let a, b, c, root1, root2, descriminant;

      a = parseInt(prompt("Enter your first coeficient"));
      b = parseInt(prompt("Enter your second coeficient"));
      c = parseInt(prompt("Enter your third coeficient"));

      descriminant = b ** 2 - 4 * a * c;

      root1 = (-b + descriminant ** 0.5) / (2 * a);
      root2 = (-b - descriminant ** 0.5) / (2 * a);

      if (descriminant < 0) {
        document.write("Complex root equation");
      } else {
        document.write(`Your answers are ${root1} and ${root2} respectively`);
      }
    </script>
  </body>
</html>
