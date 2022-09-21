# Modal OCP14

Cette librairie est une simple modal affichant un texte et le boutton permettant de fermer la modal.

## Installation 

Vous pouvez installer la librairie grâce à `npm i modal-p14-tp`  
Puis importer le component : `import { Modal } from 'modal-p14-tp'`  
Ainsi que le css `import 'modal-p14-tp/dist/index.css'`  

## Exemple d'utilisation

### Default
```js

<Modal text="Employee Created!" close={ handleModal } />

```

### Custom
```js

<Modal 
	text="Employee Created!" 
	close={ handleModal }
	classText="text-red-500"
	classButton="bg-red-500 hover:bg-red-600 h-6 w-6 text-white absolute -top-2 -right-2 rounded-full p-2"
/>

```

## Options
```js

<Modal 
	text="Employee Created!" // Texte que l'on souhaite afficher
	close={ handleModal } // La fonction de fermeture de la modal
	classText="" // Classe css qui seront appliqué sur le texte de la modal
	classButton="" // Classe css qui seront appliqué sur le bouton de fermeture de la modal
	mainBackground="" // Classe css appliqué sur le fond qui recouvre le site
	modalBackground="" // Classe css appliqué à la modal
/>

```

