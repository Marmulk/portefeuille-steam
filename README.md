# portefeuille-steam

Page relais de « Se connecter avec Steam » pour l'app Portefeuille (iPhone).

Steam (OpenID 2.0) ne renvoie qu'à une adresse web : il revient sur `retour.html`, qui passe
aussitôt sa réponse à l'app (`portefeuille://steam/retour`). L'app vérifie la signature auprès
de Steam avant de garder l'identifiant du compte. La page ne contient aucune donnée, ne charge
rien d'extérieur et ne garde rien ; le mot de passe se tape sur la page de Steam, jamais ici.
