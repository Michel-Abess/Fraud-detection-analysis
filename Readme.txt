==========================================
Detection des Faux billets
==========================================
l'objectif de ces travaux est de créer un algorithme de détection de faux billets. 
un jeu de données "training-model" contenant les caractéristiques géométriques de billets de banque est mis à notre disposition. Pour chacun d'eux, nous connaissons :

la longueur du billet (en mm) ;
la hauteur du billet (mesurée sur le côté gauche, en mm) ;
La hauteur du billet (mesurée sur le côté droit, en mm) ;
la marge entre le bord supérieur du billet et l'image de celui-ci (en mm) ;
la marge entre le bord inférieur du billet et l'image de celui-ci (en mm) ;
la diagonale du billet (en mm).



=========================================
Fichiers
=========================================

	- training_model.csv : échantillon contenant deux categories d'individus vrais et faux billets. records: 170
	- test_notes.csv : Echantillons permettant de tester l'efficacité du modèle

	
=========================================
How to open file in jupyternotebook
=========================================	

Open terminal and use the following command line:
	- ipython notebook detection de fraude.ipynb
 	- jupyter notebook detection de fraude.ipynb
If you haven't installed python yet, you can use the command line: pip install ipython 


