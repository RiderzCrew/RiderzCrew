<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kapcsolódj hozzám!</title>
    <style>
        /* Alapvető stílusok */
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1d1f21, #444950);
            color: #fff;
        }

        h1 {
            font-size: 2.5rem;
            margin-top: 50px;
        }

        .button-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        /* Gomb stílusok */
        .button {
            display: inline-block;
            padding: 15px 30px;
            font-size: 1.2rem;
            color: #fff;
            text-decoration: none;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
            min-width: 180px;
            font-weight: bold;
        }

        .button:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }

        .facebook {
            background-color: #1877f2;
        }

        .tiktok {
            background: linear-gradient(45deg, #69c9d0, #010101, #ee1d52);
        }

        .instagram {
            background: linear-gradient(45deg, #feda75, #d62976, #962fbf, #4f5bd5);
        }

        .youtube {
            background-color: #ff0000;
        }

        /* Responsív design */
        @media (max-width: 768px) {
            .button-container {
                flex-direction: column;
                gap: 15px;
            }

            .button {
                min-width: 80%;
            }
        }
    </style>
</head>
<body>
    <h1>Kapcsolódj hozzám!</h1>
    <div class="button-container">
        <a href="https://www.facebook.com/groups/632770822614617" class="button facebook">Facebook</a>
        <a href="https://www.tiktok.com/@riderzcrew" class="button tiktok">TikTok</a>
        <a href="https://www.instagram.com/riderzcrew0/" class="button instagram">Instagram</a>
        <a href="https://www.youtube.com/@Riderz_Crew" class="button youtube">YouTube</a>
    </div>
</body>
</html>
