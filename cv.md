# Artur Kleshchanka

### Contacts
- **phone**: +375(33)374-55-36;
- **email**: try3987@gmail.com;
- **skype**: orso_grande;


### Summary
My name is Artur and I am a freelance professional front-end developer from Belarus with 1 year of experience. I consider myself a person who follows modern web development practices and new technologies; a person who never stops learning; a person who is trustworthy, responsible, respects deadlines and knows that customer’s satisfaction is the key to success.

### Skills
Basic knowledge of JS, HTML, CSS, Python.

### My code example

```
<!DOCTYPE html>
<html>
<head>
 <meta charset="UTF-8">
 <title>Анимация с canvas</title>
</head>
<body>
 <canvas id="canvas" width="200" height="200"></canvas>
 <script>
     
     var circle = function (x, y, radius, fillCircle) {
         ctx.beginPath();
         ctx.arc(x, y, radius, 0, Math.PI * 2, false);
         if (fillCircle) {
             ctx.fill();
         } else {
             ctx.stroke();
         }
     };
     
     var drawBee = function (x, y) {
         ctx.lineWidth = 2;
         ctx.strokeStyle = "Black";
         ctx.fillStyle = "Gold";
         
         circle(x, y, 8, true);
         circle(x, y, 8, false);
         circle(x-5, y-11, 5, false);
         circle(x+5, y-11, 5, false);
         circle(x-2, y-1, 2, false);
         circle(x+2, y-1, 2, false);
         
     };
     
     var update = function (coordinate) {
         var offset = Math.random() * 2 -1;
         coordinate += offset;
         
         if (coordinate > 200) {
             coordinate = 200;
         }
         if (coordinate < 0) {
             coordinate = 0;
         }
         return coordinate;
     };
     
     var canvas = document.getElementById("canvas");
     var ctx = canvas.getContext("2d");
     
     var x = 100;
     var y = 100;
     
     setInterval(function () {
         ctx.clearRect(0, 0, 200, 200);
         
         drawBee(x, y);
         x = update(x);
         y = update(y);
         
         ctx.strokeRect(0, 0, 200, 200);
     }, 30);
 </script>
</body>
</html>
```

### Experience

* Сustomer Support Agent (iHerb.com)
  * I quickly and efficiently processed requests from customers of the online store thanks to pre-prepared response templates and excellent knowledge of the online store.

* Content Manager (SYVO)
  * Content creation, product listing, site administration.

### Education

* Educational establishment «Mozyr State Polytechnical College»

  * Speciality: «Oil and gas refining»

### English

Pre-intermediate  

