<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informatyka dla 7. klasy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #406566;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            top: 0;
            width: 100%;
        }
        .container {
            width: 80%;
			height: 9999px;
            margin: auto;
            padding: 80px 20px 20px; /* Dodaj padding od góry równy wysokości nagłówka, aby treść nie zachodziła na niego */
        }
        .sidebar {
            background-color: #ccc;
            width: 160px;
            padding: 10px;
            position: fixed;
            top: 100px; 
            left: 0;
            bottom: 0;
        }
        .content {
            padding-left: 200px; 
        }
        h2 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
        }
        footer {
            background-color: #406566;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Informatyka dla 7. klasy</h1>
    </header>
    <div class="container">
        <div class="sidebar">
            <h3>Więcej</h3>
            <ul>
                <li><a href="https://pl.wikipedia.org/wiki/ENIAC">Pierwszy komputer</a></li>
                <li><a href="https://coderslab.pl/pl/blog/jak-zostac-programista-przewodnik-dla-poczatkujacych">Jak zostać programisto</a></li>
                <li><a href="https://www.komputronik.pl/advanced-configurator/">Jak złożyć komputer</a></li>
            </ul>
        </div>
        <div class="content">
            <section id="podstawy">
                <h2>Podstawy informatyki</h2>
                <ul>
                    <li>Pojęcia podstawowe: komputer, oprogramowanie, sprzęt komputerowy</li>
                    <li>Systemy operacyjne: Windows, macOS, Linux</li>
                    <li>Podstawowe operacje na komputerze: uruchamianie, zamykanie, restartowanie</li>
                </ul>
            </section>
            <section id="programowanie">
                <h2>Programowanie</h2>
                <ul>
                    <li>Podstawy algorytmów: sekwencja, warunek, pętla</li>
                    <li>Programowanie w Scratch: tworzenie prostych gier i animacji</li>
                    <li>Wprowadzenie do języków programowania: Python, JavaScript</li>
                </ul>
            </section>
            <section id="sieci">
                <h2>Sieci komputerowe</h2>
                <ul>
                    <li>Pojęcie sieci komputerowej</li>
                    <li>Podstawowe elementy sieci: komputer, router, switch</li>
                    <li>Protokoły komunikacyjne: TCP/IP</li>
                </ul>
            </section>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Informatyka dla 7. klasy. Wszelkie prawa zastrzeżone.</p>
    </footer>
</body>
</html>

