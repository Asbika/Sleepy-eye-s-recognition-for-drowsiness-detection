# Sleepy-eye-s-recognition-for-drowsiness-detection

**************  Sleepy eye’s recognition for drowsiness detection **************

++++++++++++++++Application de détection et reconnaissance de somnolence - Guide de mise en œuvre++++++++++++++++++++++++
####################### POUR LE PREMIER MODEL ##############################################################################
Ce fichier README fournit des instructions sur la manière de mettre en œuvre l'application
de détection et de reconnaissance de somnolence basée sur un modèle de deep learning.
Suivez les étapes ci-dessous pour exécuter l'application avec succès.Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre système :

    Python (version 3.6 ou supérieure)
    Jupyter Notebook
    TensorFlow (version 2.x)

Instructions

    Ouvrez le fichier Jupyter Notebook (Execute_The_Model_Directly.ipynb) correspondant à l'application.

    Assurez-vous que le fichier de modèle "my_model2.h5" est présent dans le même 
    répertoire que le fichier Jupyter Notebook. Si vous avez déjà le modèle dans un autre emplacement, 
    veuillez vous assurer de spécifier le bon chemin d'accès lors de l'importation du modèle.

    Démarrez le Jupyter Notebook et accédez au fichier correspondant à l'application.

    Exécutez les cellules du notebook séquentiellement en appuyant sur Shift + Entrée. 
    Assurez-vous que toutes les cellules s'exécutent sans erreur.

    Lorsque vous atteignez la cellule 3, importez le modèle en utilisant le code suivant :

    

    "from tensorflow.keras.models import load_model
     new_model = load_model('my_model2.h5')"

     Assurez-vous de modifier le chemin d'accès au fichier si nécessaire.
    
     Assurez-vous d'avoir les éléments suivants dans le même chemin de ce projet :
           - haarcascade_frontalface_default.xml
           - haarcascade_eye.xml

     Continuez à exécuter les cellules suivantes pour terminer l'exécution de l'application.

     L'application devrait maintenant être fonctionnelle et prête à être utilisée pour la détection et la reconnaissance de somnolence.

     Remarque : Assurez-vous d'avoir les packages et les dépendances requis installés sur votre système.
                Si vous rencontrez des erreurs liées aux packages manquants, utilisez pip ou un gestionnaire de packages similaire pour les installer.

Cela devrait vous permettre de mettre en œuvre avec succès l'application de détection et de reconnaissance de somnolence basée sur le modèle de deep learning fourni.
N'hésitez pas à consulter la documentation du projet ou à nous contactez les développeurs si vous rencontrez des problèmes supplémentaires. Bonne utilisation de l'application !
