# gptmegoldas
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kártyák elhelyezése flexbox segítségével</title>
    <style>
        .kartyak {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            background-color: bisque;
            /* height: 600px; */
            align-content: center;
        }

        .kartya {
            width: 200px;
            height: 400px;
            margin: 10px;
            border-radius: 10px;
            background-color: darkcyan;
            box-shadow: 2px 3px rgba(0, 0, 0, 0.25);
        }

        #kakukk {
            background-color: blueviolet;
        }

        @media screen and (min-width: 480px) {
            .kartyak {
                background-color: cornflowerblue;

            }

            #kakukk {
                display: none;

            }
        }
    </style>
</head>

<body>
    <div class="kartyak">
        <div class="kartya">1.kártya</div>
        <div class="kartya">2.kártya</div>
        <div class="kartya">3.kártya</div>
        <div class="kartya">1.kártya</div>
        <div id="kakukk" class="kartya">kakukktoás</div>
        <div class="kartya">3.kártya</div>
        <div class="kartya">1.kártya</div>
        <div class="kartya">2.kártya</div>
        <div class="kartya">3.kártya</div>
    </div>
</body>

</html>
