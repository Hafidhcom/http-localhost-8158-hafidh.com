<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website dengan Background Bunga Bergerak</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            overflow: hidden;
            background-image: url('https://images.unsplash.com/photo-1527061011665-3652c757a4d4'); /* URL gambar bunga */
            background-size: cover;
            background-repeat: repeat-x;
            animation: moveBackground 20s linear infinite;
        }

        @keyframes moveBackground {
            0% {
                background-position: 0 0;
            }
            100% {
                background-position: 100% 0;
            }
        }
    </style>
</head>
<body>
    <!-- Tidak ada konten di sini -->
</body>
</html>
