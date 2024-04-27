### documentation : https://archive.trufflesuite.com/guides/pet-shop/

# Pré-config:

- installation de java openjdk 17+

- installation metamask: https://metamask-io.translate.goog/?_x_tr_sl=en&_x_tr_tl=fr&_x_tr_hl=fr&_x_tr_pto=sc
- installation ganache: https://archive.trufflesuite.com/ganache/
- installation truffle:
 ```sh
    sudo npm install -g truffle
    sudo npm install @truffle/hdwallet-provider
 ```

depuis la racine du projet :

pour lancer le serveur en local 

    ```sh
    truffle compile
    truffle migrate --network <network_name> // où network_name = clique_network pour deployer les contrats sur notre propre réseau blockchain Clique.
    ```

    pour lancer le frontend :

  - il faut configurer truffle-config.js pour ajouter le consentium à utiliser pour l'application.
  - il faut configurer metakask et connecter le compte/portefeuile au site.
  - une fois la configuration faite : 
    
    ```sh
    npm run dev
    ```
