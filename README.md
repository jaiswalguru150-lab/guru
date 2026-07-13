<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guru App</title>

    <style>
        body{
            margin:0;
            padding:20px;
            font-family:Arial, sans-serif;
            background:#f4f4f4;
            text-align:center;
        }

        h1{
            color:#0066ff;
        }

        h2,h3{
            color:#222;
        }

        p{
            font-size:20px;
        }

        .box{
            background:white;
            width:90%;
            max-width:700px;
            margin:auto;
            padding:20px;
            border-radius:15px;
            box-shadow:0 0 10px gray;
        }

        img{
            width:220px;
            border:3px solid black;
            border-radius:12px;
            margin:10px;
        }

        a{
            display:inline-block;
            margin:10px;
            padding:10px 20px;
            background:#007BFF;
            color:white;
            text-decoration:none;
            border-radius:8px;
        }

        a:hover{
            background:#0056b3;
        }

        table{
            width:100%;
            border-collapse:collapse;
            margin-top:20px;
        }

        th,td{
            border:1px solid black;
            padding:10px;
            text-align:center;
        }

        th{
            background:#007BFF;
            color:white;
        }

        .fail{
            background:red;
            color:white;
        }
    </style>
</head>

<body>

<div class="box">

    <h1>Welcome to Guru App</h1>

    <p>मेरा नाम <b>गुरु जायसवाल</b> है।</p>

    <p style="background:pink;color:white;padding:10px;border-radius:8px;">
        मैं HTML सीख रहा हूँ।
    </p>

    <h2>My Images</h2>

    <img src="1756645747443[1].jpg" alt="Image 1">
    <img src="WhatsApp Image.jpeg" alt="Image 2">
    <img src="guru.png (3).jpg" alt="Image 3">
    <img src="guru5 - Copy.jpeg" alt="Image 4">
    <img src="WhatsApp Image 2026-07-09 at 19.20.41 (1).jpeg" alt="Image 5">

    <h3>SATYAM JAISWAL</h3>

    <p style="background:green;color:white;padding:10px;border-radius:8px;">
        आज मैंने Title का Color बदलना सीख लिया है।
    </p>

    <a href="https://www.youtube.com/results?search_query=guru+to+mach" target="_blank">
        YouTube Search
    </a>

    <a href="guru7.html">
        Open AB Page
    </a>

    <a href="https://www.youtube.com/@SatyamJaiswal-q4k" target="_blank">
        Subscribe
        <br><br>
        <img src="youtube-logo-icon.webp" alt="youtube-logo-icon.webp" height="60" width="60">
    </a>

    <h2>Student Result</h2>

    <table>
        <tr>
            <th>Name</th>
            <th>Father Name</th>
            <th>Result</th>
        </tr>

        <tr>
            <td>Satyam</td>
            <td>Jaiswal</td>
            <td>Pass</td>
        </tr>

        <tr>
            <td>Guru</td>
            <td>Jaiswal</td>
            <td>Pass</td>
        </tr>

        <tr>
            <td>Rahul</td>
            <td>Kumar</td>
            <td class="fail">Fail</td>
        </tr>
    </table>
      <a href="AB.html">
        Open QR Page
    </a
</div>

</body>
</html>
