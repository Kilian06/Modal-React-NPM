React Modal Simplifier
----------------------

Ce package npm a pour but de simplifier la création d'une modal au sein d'une page React. Il vous permet de créer facilement une modal en spécifiant des paramètres tels que la couleur de l'arrière-plan, la couleur du texte, et bien plus encore.

Installation
------------

Pour installer ce package, vous pouvez utiliser npm en exécutant la commande suivante :

    npm i modal-component-kle
    

**Remarque :** Pour que ce package fonctionne correctement, vous devez avoir installé `react-router`. Si vous ne l'avez pas déjà installé, vous pouvez l'installer avec la commande suivante :

    npm install react-router-dom
    

Utilisation
-----------

Pour utiliser ce package, vous devez d'abord importer le composant Modal depuis le package :

    import {Modal} from "modal-component-kle";
    

Ensuite, vous pouvez utiliser le composant Modal dans votre application React :

    <Modal
      bgModal={"#FF0000"}
      bgContent={"#00FF00"}
      colorContent={"#FFFFFF"}
      colorClose={"#FFFFFF"}
      visible={modal}
      closelink={"/employee-list"}
      textContent={"Employee Created!"}
      onClose={handleModalClose}
    />
    

Vous pouvez spécifier les paramètres suivants pour personnaliser votre modal :

Paramètres
----------

*   `bgModal` : la couleur de l'arrière-plan de la modal.
*   `bgContent` : la couleur de l'arrière-plan du contenu de la modal.
*   `colorContent` : la couleur du texte à l'intérieur de la modal.
*   `colorClose` : la couleur de la croix de fermeture de la modal.
*   `visible` : un booléen pour indiquer si la modal doit être affichée ou non.
*   `closelink` : pour permettre lors de la fermeture de la modal d'être redirigé vers une page en spécifiant l'URL. Si aucune URL n'est spécifiée (c'est-à-dire ""), la modal se ferme et l'utilisateur reste sur la même page.
*   `textContent` : le texte à l'intérieur de la modal.
*   `onClose` : un booléen pour fermer la modal.

Licence
-------

Ce package est sous licence MIT.
