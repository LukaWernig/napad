<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div id="bg1" href="spodrs.html"></div>

    <script>
        var audio = new Audio("remzi.mp3");
        document.addEventListener("click", () => {
            audio.play();
            setTimeout(function() {
                document.getElementById("bg1").style.backgroundImage = "url('romzi.jpg')";

            }, 4000);
            audio = new Audio("funi.mp3");
        });
    </script>


</body>

</html>
