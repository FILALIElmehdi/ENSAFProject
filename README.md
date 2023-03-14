<h1 >
Réalisateurs: 
</h1>
      <H2><I>-FILALI Elmehdi </I></H2>
     <H2><I>-BOUTAHIR Ghita </I></H2>
     <H2><I>-FRIDI FILALI Ayoub </I></H2>
     <H2><I>-MAAKOUL Mohammed </I></H2>
  
<h1 align='center'>
Calculatrice avec menu ( Présentation )
</h1>


https://user-images.githubusercontent.com/116765052/225055905-4067198c-f3ae-4e9a-bc84-2504743038b1.mp4



<h1 align='center'>
**Installation et exécution sur une machine virtuelle**
</h1>


https://user-images.githubusercontent.com/116765052/225113582-0cc80093-1694-430a-8353-2abd391f8f7c.mp4

<h1 align='center'>
**Installation et exécution sur une machine pyhisique**
</h1>


https://user-images.githubusercontent.com/116765052/225113951-da3f3148-7576-4a38-894a-12c7ab942dfe.mp4



<h1 align='center'>
**Etapes de création ( Compte rendu )**
</h1>

<h2>Voici le compte rendu pour créer une calculatrice avec un menu dans Android Studio :</h2>

  <h3>1.Créer un nouveau projet Android Studio et sélectionner l'activité "Empty Activity".</h3>

                1.1.Ouvrir Android Studio et sélectionner "Start a new Android Studio project" dans l'écran d'accueil.

                1.2.Dans la boîte de dialogue "New Project", saisir le nom du projet dans le champ "Application name".

                1.3.Sélectionner la langue de programmation (Java ) et la version minimale d'Android pour 

  <h3>2.Dans le fichier layout de l'activité principale, ajouter les boutons et les vues nécessaires pour la calculatrice.</h3>
             
              2.1.Dans le dossier "res" du projet, ouvrir le dossier "layout" et cliquer sur le fichier "activity_main.xml".

                    2.1.1.Ouvrir le fichier XML de l'activité principale en cliquant sur l'onglet "activity_main.xml" dans la barre latérale de 
                              l'éditeur de code.
              2.2.Dans l'éditeur de mise en page, ajouter une vue
                      2.2.1.Ajouter un TextView en haut de la mise en page pour afficher les résultats des calculs. Par exemple, vous pouvez 
                                  utiliser la bal

  <h3>3.Dans le fichier java de l'activité principale, ajouter le code pour le traitement des clics sur les boutons de la calculatrice.</h3>
                    3.1.Dans le fichier Java de l'activité principale, déclarez les variables pour les vues que vous avez ajoutées dans le fichier 
                         XML. Par exemple, si vous avez ajouté un TextView avec l'ID "resultTextView", vous pouvez le déclarer comme suit.

                               #  javaCopy codeTextView resultTextView = findViewById(R.id.resultTextView).

                         3.1.1.Ouvrir le fichier Java de l'activité principale en cliquant sur l'onglet "MainActivity.java" dans la barre latérale de 
                                 l'éditeur de code.
                          3.1.2.Ajouter des variables de classe pour stocker les vues de la calculatrice, comme le TextView pour afficher les 
                                  résultats, et les boutons numériques et d'opérations.    
                                                                                  
                       private TextView resultTextView.
                      private Button button0, button1, button2, button3, button4, button5, button6, button7, button8, button9.
                      private Button buttonAdd, buttonSubtract, buttonMultiply, buttonDivide, buttonEquals, buttonClear.

                       3.1.3.Dans la méthode onCreate() de l'activité, initialiser les vues en utilisant la méthode findViewById() et les affecter 
                             aux variables de classe.
                       3.1.4.Ajouter un listener de clic
  <h3>4.Créer un nouveau fichier XML pour le menu </h3>

             4.1.Dans l'arborescence du projet, ouvrir le dossier "res", puis le dossier "menu".

            4.2.Clic droit sur le dossier "menu" et sélectionner "New" > "Menu resource file".

            4.3.Dans la boîte de dialogue "New Resource File", saisir le nom du fichier XML de menu et sélectionner le type de menu (par 
                   exemple, "Options Menu").

            4.4.Cliquer sur "OK" pour créer le fichier XML de menu.

            4.5.Dans le fichier XML de menu, ajouter les éléments de menu nécessaires. Par exemple, vous pouvez ajouter des éléments 
                   pour lancer une nouvelle activité, pour effacer les résultats de la calculatrice, pour afficher des informations sur 
                   l'application, etc.

          4.6.Dans la méthode onCreateOptionsMenu() de l'activité principale, utiliser la méthode getMenuInflater() pour obtenir une 
              référence au MenuInflater, puis appeler sa méthode inflate() pour créer le menu à partir du fichier XML de menu :
  
  <h2>Ci-joint des captures écrans :</h2>
  
  
![boutton](https://user-images.githubusercontent.com/116765052/225071288-87ac75ee-4fa1-4ec0-ba98-ac2038bd6c78.PNG)


![Capture](https://user-images.githubusercontent.com/116765052/225071493-bce8a6f6-7cda-4268-bed1-8902b54beeaf.PNG)

![CodeJava](https://user-images.githubusercontent.com/116765052/225071595-7e7bd8c3-626c-444e-8cdf-b278049e95a7.PNG)

![Menu](https://user-images.githubusercontent.com/116765052/225071630-895b2573-098f-4512-8b06-d61614e8002f.PNG)

  
![Capture2](https://user-images.githubusercontent.com/116765052/225072643-0fc0786c-e27e-4817-ace8-dd4ef943310a.PNG)

![Capture3](https://user-images.githubusercontent.com/116765052/225072671-3c31a9e8-9703-4eae-8d6e-2b2beef6c5ea.PNG)
