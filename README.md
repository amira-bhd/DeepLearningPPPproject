# DeepLearningPPPproject
Reconnaissance des émotions par approche DeepLearning

Description : Dans la littérature, plusieurs travaux ont été proposés pour la reconnaissance des émotions et cela à travers la reconnaissance des expressions faciales et la détection des Action Units [1,2]. Les expressions reconnues sont classées en six actions universelles définies par le psychologue Paul Ekman [5] (colère, dégoût, joie, surprise, tristesse, peur). 
Les méthodes de reconnaissance d’expressions se distinguent naturellement en deux classes : les approches statiques et les approches dynamiques. Les approches statiques utilisent une seule image pour reconnaître l’expression (typiquement l’apex de l’expression). Néanmoins, cette représentation statique de l’expression n’est pas naturelle comme l’expression évolue dans le temps, commençant de l’état neutre et passant par le début de l’expression (onset) puis le maximum de l’expression (apex) et la fin de l’expression (offset) pour finir par l’état neutre à nouveau. Ainsi, la reconnaissance des expressions à partir des vidéos est plus commune que celle à partir des images statiques : on parle d'approche dynamique. 

Dans le cadre de ce projet, nous proposons d’utiliser les notions d’arousal et de valence pour détecter l’état émotionnel d’une personne (par exemple : un apprenant dans un contexte d’un système tutoriel émotionnellement intelligent). Dans ce contexte, nous proposons d'utiliser l’apprentissage profond (Deep Learning) pour reconnaitre et classifier les émotions. 

Travail demandé :
1- Maîtriser les concepts théoriques relatifs au Deep Learning
2-Implémentation du Deep Learning : 
- TensorFlow : Développé par Google Brain Team // écrit en Phyton/C++ // Interface : Phyton,C/C++ // Win, MacOS X, Linux 
3. Application à la reconnaissance/classification des émotions :
- Etudier la problématique de reconnaissance des émotions
- Choix de la base de test 
- Proposer un framework de classification/reconnaissance des émotions se basant sur DeepLearning 
- Implémentation et interprétations

Références 
[1]	[O. Rudovic, V. Pavlovic, M. Pantic, Context-sensitive dynamic ordinal regression for intensity estimation of facial action units, IEEE Transactions on Pattern Analysis and Machine Intelligence 37 (2015) 944-958.
[2]	S. Kaltwang, S. Todorovic, M. Pantic, Doubly sparse relevance vector machine for continuous facial behavior estimation, IEEE Transactions on Pattern Analysis and Machine Intelligence,Volume: 38, Issue: 9 (2016).
[3]	H. Gunes, B. Schuller, Categorical and dimensional affect analysis in continuous input: Current trends and future directions, Image and Vision Computing 31 (2) (2013) 120-136.
[4]	Y. Panagakis, M. A. Nicolaou, S. Zafeiriou, M. Pantic, Robust correlated and individual component analysis, IEEE Transactions on Pattern Analysis and Machine Intelligence (accepted).
[5]	P. Ekman and W. V. Friesen, Manual for the the Facial Action Coding System. Palo Alto, CA: Consulting Psychologist Press, 1977.
