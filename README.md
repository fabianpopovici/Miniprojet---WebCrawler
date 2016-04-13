# Miniprojet---WebCrawler
Un robot d'indexation (ou littéralement araignée du Web ; en anglais web crawler ou web spider) est un logiciel qui explore automatiquement le Web. Il est généralement conçu pour collecter les ressources (pages Web, images, vidéos, documents Word, PDF ou PostScript, etc.), afin de permettre à un moteur de recherche de les indexer.

Fonctionnant sur le même principe, certains robots malveillants (spambots) sont utilisés pour archiver les ressources ou collecter des adresses électroniques auxquelles envoyer des courriels.

En français, depuis 2013, crawler est remplaçable par le mot collecteur.

PRINCIPES DE FONCTIONNEMENT: 
Pour indexer de nouvelles ressources, un robot procède en suivant récursivement les hyperliens trouvés à partir d'une page pivot. Par la suite, il est avantageux de mémoriser l'URL de chaque ressource récupérée et d'adapter la fréquence des visites à la fréquence observée de mise à jour de la ressource. Toutefois, si le robot respecte les règles du fichier robots.txt, alors de nombreuses ressources échappent à cette exploration récursive. Cet ensemble de ressources inexploré est appelé Web profond ou Web invisible.

Un fichier d'exclusion (robots.txt) placé dans la racine d'un site Web permet de donner aux robots une liste de ressources à ignorer. Cette convention permet de réduire la charge du serveur Web et d'éviter des ressources sans intérêt. Toutefois, certains robots ne se préoccupent pas de ce fichier.

Deux caractéristiques du Web compliquent le travail du robot d'indexation : le volume de données et la bande passante. Les capacités de traitement et de stockage des ordinateurs ainsi que le nombre d'internautes ayant fortement progressé, cela lié au développement d'outils de maintenance de pages de type Web 2.0 permettant à n'importe qui de mettre facilement en ligne des contenus, le nombre et la complexité des pages et objets multimédia disponibles, et leur modification, s'est considérablement accru dans la première décennie du XXIe siècle. Le débit autorisé par la bande passante n'ayant pas connu une progression équivalente, le problème est de traiter un volume toujours croissant d'information avec un débit relativement limité. Les robots ont donc besoin de donner des priorités à leurs téléchargements.

Le comportement d'un robot d'indexation résulte de la combinaison des principes suivants :

    Un principe de sélection qui définit quelles pages télécharger ;
    Un principe de re-visite qui définit quand vérifier s'il y a des changements dans les pages ;
    Un principe de politesse qui définit comment éviter les surcharges de pages Web (délais en général) ;
    Un principe de parallélisation qui définit comment coordonner les robots d'indexations distribués.

