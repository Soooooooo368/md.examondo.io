<!DOCTYPE html>
<html lang="ro">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Examodo Moldova</title>
    <style>
        /* Stiluri generale */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: linear-gradient(to bottom, #a8e6cf, #ffffff);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* HEADER */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #64b5f6;
            padding: 10px 20px;
            color: white;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            width: 40px; /* Logo mai mic */
            margin-right: 10px;
        }

        /* Caseta de elevi */
        .elevi-box {
            background-color: #1565c0;
            color: white;
            padding: 10px 15px;
            border-radius: 8px;
            font-size: 16px;
            text-align: center;
            margin-left: 20px; /* Spațiu între logo și caseta „Elevi” */
        }

        /* Caseta de mesaj pătrată */
        .message-box {
            background: #f5f5f5;
            padding: 20px;
            width: 150px; /* Lățimea fixă pentru a face caseta pătrată */
            height: 100px; /* Înălțimea fixă pentru a face caseta pătrată */
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            font-size: 14px;
            color: #333;
            margin-top: 20px; /* Plasarea la 20px sub header */
            display: flex;
            flex-direction: column;
            justify-content: space-between; /* Asigură spațierea între text și buton */
            align-items: center;
        }

        .message-box button {
            background-color: #1565c0;
            color: white;
            border: none;
            padding: 8px 12px;
            font-size: 12px;
            border-radius: 5px;
            cursor: pointer;
            width: 80%; /* Lățimea butonului pentru a se potrivi mai bine în casetă */
        }

        .message-box button:hover {
            background-color: #0d47a1;
        }

        /* FOOTER */
        footer {
            background: #e0e0e0;
            padding: 1rem;
            text-align: center;
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
        }

        footer a {
            margin: 0 8px; /* Distanță mai mică între linkuri */
            color: #1565c0;
            text-decoration: none;
        }

    </style>
</head>

<body>
    <!-- Bara de navigare -->
    <header>
        <div class="logo">
            <img src="Design_fără_titlu-removebg-preview.png" alt="Examodo Logo">
            <h1 style="font-size: 18px; margin: 0;">Examodo Moldova</h1>
        </div>
        <!-- Caseta „Elevi” în colțul din dreapta al header-ului -->
        <div class="elevi-box">
            Elevi
        </div>
    </header>

    <!-- Caseta de mesaj pătrată -->
    <center><div class="message-box">
        Vi se atribuie un test de rezolvat.
        <br><br>
        <button onclick="window.location.href='http://127.0.0.1:5500/md.examen.1.html';">Accesați Testul</button>
    </div></center>

    <!-- Imaginea clasei -->
    <img src="stock-photo-classroom-without-students.png" alt="Imagine cu o clasă" class="class-image">

    <!-- Footer -->
    <footer>
        <a href="#">Termeni și condiții</a>
        <a href="#">Politica de confidențialitate</a>
        <a href="#">Consimțământ privind cookie-urile</a>
    </footer>

</body>

</html>
