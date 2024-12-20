# project réalisé par : Belgacem Chaibi & Rayen Ben Cheikh       MP2 SD
## Système de Recommandation d'Offres de Travail :
Objectif :

Développer un système de recommandation qui identifie et propose à chaque utilisateur les offres d’emploi les plus pertinentes dans son domaine, en fonction de ses compétences (skills).
avec 2 liens pour tester deux  les systemes de recommandations 
 Attension : Ces lien restent valables seulement pour 72 heures .
## Dataset :
Notre dataset comprend 1,6 million d'annonces de travail. Actuellement au format CSV, il devra être converti au format JSON .

Lien : https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset

## Prétraitement des Données

## Premier Système de recommandation :
https://12520bf8b03aefc280.gradio.live

▶ Le système utilise cosine_similarity de scikit-learn pour mesurer la similarité entre les utilisateurs et les descriptions des offres.

▶ GloVe pour générer des représentations vectorielles des textes.

▶ Il exploite MongoDB pour la gestion des données,

▶ NumPy pour les calculs matriciels,

▶ Gradio pour une interface utilisateur interactive et accessible

## Deuxieme Systeme de recommandation :
 https://a3e71a6ff8e6af6743.gradio.live

Le système de recommandation utilise :

▶ MongoDB pour le stockage des données,

▶ SentenceTransformer pour générer des représentations vectoriell\es des textes.

▶ Il évalue la similarité entre les offres et les compétences avec cosine_similarity

▶ propose une interface utilisateur interactive grâce à Gradio.

