# cours-Html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- titre de la page -->
    <title>Cours HTML de zéro</title>
    <!-- incone de l'onglet -->
     <link rel="shortcut icon" href="./logo_head.png">
</head>
<body>
    <nav>
        <!-- ul= Unordered List -->
        <ul>
            <li>Acceuil</li>
            <li>Boutique</li>
            <li>
                <a href="#from" >Fomulaire</a>
            </li>
        </ul>
    </nav>
    <header>
        <!-- un seul h1 par page -->
        <h1>Ceci est le titre principal</h1>
        <p> texte clasique <em>texte en italique</em> <strong>texte en gras</strong></p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Officiis quibusdam quas alias deleniti consequuntur nihil consectetur voluptate cumque quod magni. Laborum, quis quam natus maiores dignissimos eius aliquid! Maxime, quos?</p>
    </header>
    <main>
        <section>
            <h2>ordered list</h2>
            <ol>
                <li>Ceci est une</li>
                <li>liste</li>
                <li>dans l'ordre</li>
            </ol>
        </section>
        <h3>Image en HTML</h3>
       <img src="./italy.png" height="200" alt="Image-section">
       <!-- l'alt de l'image est pour l'accessibilité -->
        <div>
            <h4>Tableau</h4>
            <table border="4" cellpadding="10 "style="text_align: center">
                <!-- thead est pour lentete du tableau -->
                 <thead>
                    <tr>
                        <th>Col 1</th>
                        <th>Col 2</th>
                        <th>Col 3</th>
                    </tr>
                 </thead>
                 <tbody>
                    <tr>
                        <td rowspan="2">Cell 1</td>
                        <td>Cell 2 </td>
                        <td>Cell 3</td>
                    </tr>
                    <tr>
                        <td colspan="2">Cell 4</td> 
                    </tr>
                 </tbody>
            </table>
        </div>
        <div>
            <h5><span>&#8594;</span>Les liens</h5>
            <!-- blank permet de crée un nouvel ongler -->
            <a href="https://htmlcheatsheet.com"target="_blank">Html Cheat Sheet</a>
        </div>
        <div>
            <h6><i>&#127916;</i>Vidéo</h6>
            <video src="./video.mp4"height="200" autoplay muted loop ></video>
        </div>
        <section id="form">
            <h2>Les formulaires</h2>
            <!-- "action" ou vont les données une fois qu'on à saisie le Formulaire -->
            <form action="">
                <!-- "for" et "id" permettent de lier le label à input -->
                <label for="">Nom</label> 
                <input type="text"id="name" placeholder="entrer votre nom">
                <br/>
                <label for="">Age</label>
                <input type="number" id="Age" value="18"/>
                <br/>
                <label for="gender">Genre</label>
                <select  id="gender">
                   <option value="Homme">Homme</option>
                   <option  selected="selected" value="Femme">Femme</option>
                   <option value="Autre">Autre</option>
                </select>
                <div>
                <!-- input de type radio -->
                 <input type="radio" name="type" id="Human"checked/>
                 <label for="human">Humain</label>

                 <input type="radio" name="type" id="Dog">
                 <label for="Dog">Chien</label>

                 <input type="radio" name="type" id="Cat">
                 <label for="Cat">Chat</label>
                </div>
                    <textarea placeholder="Votre message ..." cols="20" rows="5"></textarea>
                    <br />

                    <!-- input de type checkbox -->
                 <input type="checkbox" name="" id="cgv">
                 <label for="cgv">Accepter les conditions générales</label>
                <br />
                <!-- input de type submit permet de valider -->
                 <input type="submit" value="Ceci est le bouton pour valider le formulaire">
            </form>
            <button>ceci est un boutuon</button>
        </section>
    </main>
    <footer>
        <!-- mail et envoie de fichiers -->
         <a href="mailto:fsgmail.com">Contactez moi !</a>
         <a href="./notice.txt" download="Notice">Télécharger la notice</a>
    </footer>

</body>
</html>  
