<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar File Praktikum Modul 4</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f4f9;
            color: #333;
        }
        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin: 10px 0;
            background: white;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        li:hover {
            transform: translateX(10px);
            border-left: 5px solid #3498db;
        }
        a {
            text-decoration: none;
            color: #2980b9;
            font-weight: bold;
            display: block;
        }
        a:hover {
            color: #e74c3c;
        }
        .back-button {
            display: inline-block;
            margin-bottom: 10px;
            padding: 10px 16px;
            border: 0;
            border-radius: 5px;
            background-color: #3498db;
            color: white;
            font: inherit;
            font-weight: bold;
            cursor: pointer;
        }
        .back-button[hidden] {
            display: none;
        }
        .back-button:hover {
            background-color: #2980b9;
        }
        .info {
            margin-top: 30px;
            font-size: 0.9em;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

    <h2>Daftar File Praktikum Modul 4 (PHP Dasar)</h2>

    <button class="back-button" type="button" hidden onclick="if (history.length > 1) { history.back(); } else { window.location.href = '../'; }">
        &larr; Kembali
    </button>
    <script>
        const backButton = document.querySelector('.back-button');
        const currentDirectory = window.location.pathname
            .replace(/\/index\.php$/i, '')
            .replace(/\/+$/, '');

        if (currentDirectory || history.length > 1) {
            backButton.hidden = false;
        }
    </script>

    <ul>
        <?php
        // Mendapatkan semua file dan folder di direktori saat ini
        $entries = scandir(__DIR__);

        foreach ($entries as $entry) {
            if ($entry === "." || $entry === ".." || $entry === "index.php") {
                continue;
            }

            $isDirectory = is_dir(__DIR__ . DIRECTORY_SEPARATOR . $entry);
            $isPhpFile = pathinfo($entry, PATHINFO_EXTENSION) === 'php';

            if ($isDirectory || $isPhpFile) {
                $href = rawurlencode($entry) . ($isDirectory ? '/' : '');
                $label = htmlspecialchars($entry . ($isDirectory ? '/' : ''), ENT_QUOTES, 'UTF-8');
                echo '<li><a href="' . $href . '">' . $label . '</a></li>';
            }
        }
        ?>
    </ul>

    <div class="info">
        <p><em>Dokumen ini akan membaca dan memuat file PHP Anda secara otomatis.</em></p>
    </div>

</body>
</html>