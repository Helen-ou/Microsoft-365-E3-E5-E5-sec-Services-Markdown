Top 10 des pratiques de cybersécurité.
Ce post sera divisé en deux Top 5 par ordre de priorité : Un au niveau individuel, et l'autre au niveau IT Management :

#### Top 5 Pratiques pour les Utilisateurs : 

1.  Utilisez un générateur de mot de passes aléatoire en conjonction avec un gestionnaire de mots de passe (géré souvent par les entreprises pour une bonne compliance).
2.  Si vous avez le moindre doute sur un email ou une pièce-jointe, vérifiez l'origine du mail : Est-ce que vous connaissez la personne ? Est-ce qu'un I (i) majuscule n'est pas en fait un l (L) minuscule ? Et si le mail semble légitime mais que le doute persiste, vérifiez cela avec l’émetteur.
3.  Le Shadow Applicatif est une autre difficulté de la cybersécurité. En outre, comment être sûr qu'une application ne cache pas de malware ? De manière générale, les applications ne devraient être téléchargées que via des sites ou d'entreprises fiables, ou si le but est précis, de dépôts open-source et populaires récents.
4.  Il est important de vérifier épisodiquement si votre adresse mail à été compromise et est présente dans une base de données publique. [Have I been Pwned](https://haveibeenpwned.com/) permet de vérifier cela parmis des centaines de brèches sur 10 ans : Si c'est rouge, changez le mot de passe.
5.  Comme [vous êtes votre propre défense](https://www.phishingbox.com/resources/phishing-facts), exercice surprise ! 
Quelles sont les deux différences entre ces adresses *fictives* ?

Softwareone.help
Softwаreone.heIp

Tout d'abord, le L s'est transformé en I. Mais avez-vous remarqué l'autre différence ? Le a de Softwareone s'est transformé en [а de l'alphabet cyrillique](https://fr.wikipedia.org/wiki/Alphabet_cyrillique#Alphabets_contemporains).


#### Top 5 Pratiques pour l'IT Management 




1. Utilisez un gestionnaire de mots de passe pour vous et les employés : Éliminez l'attaque brute force ou les mots de passes appartenant à une [Rainbow Table](https://www.ionos.fr/digitalguide/serveur/securite/rainbow-tables/)
2. Écoutez les conseils de vos équipes informatiques et éventuellement de cybersécurité ; ce ne sont aujourd'hui pas des dépenses mais des nécessités. **Le coût d'un Ransomware est la faillite en moins de 6 mois (re-vérifier).**
3.  Pour plus de protection, utilisez la [Multi-Factor Authentification](https://aws.amazon.com/fr/what-is/mfa/#:~:text=L'authentification%20multifactorielle%20(MFA)%20est%20un%20processus%20de%20connexion,un%20simple%20mot%20de%20passe.) : On évite ici l'usurpation d'identité si un mot de passe à tout de même été compromis. **Conditional Access** est un service proposant des règles à appliquer au MFA.
4. Sauvegardez vos données régulièrement pour faire office de sécurité intégrée en cas de brèche : La probabilité des attaques informatiques n'est pas une question de si mais de quand ; Utilisez l'offre BackupSimple proposée par SoftwareOne pour vous protégez encore plus. 
   **Testez la restoration de temps en temps**. Et pour aller plus loin, Il est conseillé d’appliquer la règle dite « 3 – 2 – 1 », qui consiste à disposer de 3 copies des donnés, stocker sur 2 supports différents, dont 1 hors ligne.
5. Obligez via WSUS ou Intune la mise à jour de **tous** les logiciels, systèmes d'exploitations. **Gérez** les mises à jour.

Bonus: Faites attention aux Shadow LLM. Ce sont les IA qui récupèrent les données qui ont été rentrées afin de s'améliorer, mais peuvent être récupérées par les utilisateurs. Microsoft Purview permet de se prémunir des fuites de ce type.


