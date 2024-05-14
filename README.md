
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Budget Commun</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #50b3a2;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        .content {
            padding: 20px;
            background: #ffffff;
            margin-top: 20px;
        }
        table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #dddddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Budget Commun</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#expenses">Dépenses Communes</a></li>
                    <li><a href="#personal">Budget Personnel</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <div class="content">
            <h2 id="expenses">Dépenses Communes</h2>
            <table>
                <thead>
                    <tr>
                        <th>Catégorie</th>
                        <th>Montant (CHF)</th>
                        <th>Commentaire</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Loyer</td>
                        <td>2565</td>
                        <td>Logement</td>
                    </tr>
                    <tr>
                        <td>Wifi</td>
                        <td>40</td>
                        <td>Internet</td>
                    </tr>
                    <tr>
                        <td>Femme de ménage</td>
                        <td>300</td>
                        <td>Services</td>
                    </tr>
                    <tr>
                        <td>Essence</td>
                        <td>80</td>
                        <td>Carburant</td>
                    </tr>
                    <tr>
                        <td>Voiture</td>
                        <td>320</td>
                        <td>Assurance + entretien</td>
                    </tr>
                    <tr>
                        <td>Courses</td>
                        <td>900</td>
                        <td>Nourriture pour deux personnes et deux chats</td>
                    </tr>
                    <tr>
                        <td>Électricité</td>
                        <td>100</td>
                        <td>Facture électrique</td>
                    </tr>
                    <tr>
                        <td>Assurance voiture</td>
                        <td>100</td>
                        <td>Assurance véhicule</td>
                    </tr>
                    <tr>
                        <td>Facture Serafe</td>
                        <td>30</td>
                        <td>Redevance audiovisuelle</td>
                    </tr>
                    <tr>
                        <td>Restaurants</td>
                        <td>200</td>
                        <td>Sorties au restaurant</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>4635</td>
                        <td>Total des dépenses communes</td>
                    </tr>
                    <tr>
                        <td>Contribution individuelle</td>
                        <td>2317.50</td>
                        <td>Par personne</td>
                    </tr>
                </tbody>
            </table>

            <h2 id="personal">Budget Personnel</h2>
            <table>
                <thead>
                    <tr>
                        <th>Catégorie</th>
                        <th>Montant (CHF)</th>
                        <th>Commentaire</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Contribution au compte joint</td>
                        <td>2317.50</td>
                        <td></td>
                    </tr>
                    <tr>
                        <td>Fitness</td>
                        <td>50</td>
                        <td>Abonnement fitness</td>
                    </tr>
                    <tr>
                        <td>Cours extra</td>
                        <td>400</td>
                        <td>Cours additionnels</td>
                    </tr>
                    <tr>
                        <td>Argent pour votre mère</td>
                        <td>150</td>
                        <td>Soutien familial</td>
                    </tr>
                    <tr>
                        <td>Assurance maladie</td>
                        <td>610</td>
                        <td>Couverture santé</td>
                    </tr>
                    <tr>
                        <td>Téléphone</td>
                        <td>75</td>
                        <td>Abonnement téléphonique</td>
                    </tr>
                    <tr>
                        <td>3ème pilier</td>
                        <td>200</td>
                        <td>Épargne retraite</td>
                    </tr>
                    <tr>
                        <td>Impôts</td>
                        <td>1500</td>
                        <td>Impôts sur le revenu</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>5302.50</td>
                        <td>Total des dépenses personnelles</td>
                    </tr>
                    <tr>
                        <td>Revenu restant</td>
                        <td>1797.50</td>
                        <td>Revenu après dépenses</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</body>
</html>
