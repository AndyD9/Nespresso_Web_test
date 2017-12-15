Maquette Nespresso réaliser en cours de Web Design.

Intégration Web, Mobile First.

Date de fin : indéfinis.

DODAKAL Andy

CSS :
.nespressologo{
 margin-top: 2%;
 margin-bottom: 2%;
 width: 20%;
}


.header {

 Par défaut, une balise de type block fait 100%
 */
 background: grey;
 /* On met une marge en dessous du header */
 margin-bottom: 40px;
}


.navList{
 display: none;
}

@media (min-width: 1024px) {
 .navList {
   /* On affiche les <li> en liste */
   display: flex;
   justify-content: space-between;
   /*
   On met une largeur afin que les <li> prennent
   l'espace qu'on lui donne
   */
   width: 30%;
   /* Retirer les puces de la liste */
   list-style: none;
   float: right;
   margin-bottom: 90%;
 }
}
