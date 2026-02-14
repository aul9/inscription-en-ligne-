<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Inscription en Ligne</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <!-- Font Awesome (icône) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background: white;
            padding: 40px;
            border-radius: 15px;
            width: 100%;
            max-width: 500px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        h2 {
            text-align: center;
            margin-bottom: 25px;
            color: #2c5364;
        }

        .form-group {
            margin-bottom: 15px;
        }

        label {
            font-weight: 500;
        }

        input, select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border-radius: 8px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: #2c5364;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background-color: #1e3c50;
        }

        .footer {
            text-align: center;
            margin-top: 15px;
            font-size: 13px;
            color: gray;
        }
    </style>
</head>

<body>

<div class="container">
    <h2>Formulaire d'Inscription</h2>

    <!-- FormSubmit permet d'envoyer vers ton email -->
    <form action="https://formsubmit.co/paulbossa97@gmail.com" method="POST">

        <!-- Anti-spam -->
        <input type="hidden" name="_captcha" value="false">

        <div class="form-group">
            <label>Nom complet</label>
            <input type="text" name="Nom" required>
        </div>

        <div class="form-group">
            <label>Email</label>
            <input type="email" name="Email" required>
        </div>

        <div class="form-group">
            <label>Téléphone</label>
            <input type="tel" name="Téléphone" required>
        </div>

        <div class="form-group">
            <label>Sexe</label>
            <select name="Sexe" required>
                <option value="">Choisir</option>
                <option>Masculin</option>
                <option>Féminin</option>
            </select>
        </div>

        <button type="submit">
            <i class="fas fa-paper-plane"></i> Envoyer l'inscription
        </button>

    </form>

    <div class="footer">
        © 2026 - Inscription en ligne | Paul José BOSSA
    </div>
</div>

</body>
</html>
