# FERRARI-sample-webpage1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        body{
            margin:0;
        }

        .main1{
            width: 100vw;
            height: 100vh;
            background-color: black;
            position: relative;
        }
        .sub11{
            width: 100vw;
            height: 75vh;
            background-color: blueviolet;
            position: absolute;
            top: 0;
            left: 0;

        }

        .sub11 img{
            width: 100%;
            height: 100%;
        }

        .sub12{
            width: 100vw;
            height: 30vh;
            background-color: brown;
            position: absolute;
            top:70vh;
            overflow: hidden;
            transition: all 1s ease-in-out;
        }

        .main1:hover .sub12{
            height: 75vh;
            top:25vh;
        }

        .sub12 img{
            width: 100vw;
            height: 75vh;
        }

        .sub13{
            position: absolute;
            top: 3vh;
            left: 2vw;
            font-size: x-large;
            color: white;
        }
        .sub13 td{
            padding-left: 50px;
        }
        .sub14{
            width: 100vw;
            height: 30vh;
            color: whitesmoke;
            bottom: 45vh;
            position: absolute;
            font-size: 200px;
            text-align: center;
            left: -10vw;
            transition: all 2s ease-in-out;
        }
        .main1:hover .sub14{
            bottom: 19vh;
            left: 0;
        }
    </style>
    
</head>
<body>
    <div class="main1">
        <div class="sub11">
            <img src="https://wallpapers.com/images/hd/ferrari-f1-2019-upcm43vv4qpvrnss.jpg"> 

        </div>
        <div class="sub12">
            <img src="https://c4.wallpaperflare.com/wallpaper/652/804/929/ferrari-sf71h-formula-one-4k-2018-wallpaper-preview.jpg">

        </div>
        <div class="sub13">
            <table>
            <tr>
                <td>Home</td>
                <td>Models</td>
                <td>Bookings</td>
                <td>Racing</td>
                <td>Products</td>
            </tr>    
        </table>
        </div>

        <div class="sub14">
            FERRARI

        </div>
            
    </div>
    
</body>
</html>
