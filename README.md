# Projet BOOKI

Booki est une petite entreprise proposant un outil de planification de vacances en ligne.

Son site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix.
Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.

L'objectif de ce projet consiste à réaliser le prototype en HTML/CSS de la page d'accueil du nouveau site de l'entreprise à partir des maquettes fournies.

# Consignes de base

## Spécifications fonctionnelles

1. Les usagers pourront rechercher des hébergements dans la ville de leur choix.
   Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur.
   Il faut englober ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C.
   La partie recherche ne doit pas être fonctionnelle.
2. Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre).
   Pour l’instant, les liens sont vides.
   On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.
3. Les filtres doivent changer d’apparence au survol.
   L’effet approprié est laissé libre mais les filtres ne doivent pas être fonctionnels.
4. Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens.
   Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques

1. Deux maquettes ont été réalisées : l’une desktop et l’autre mobile.
   Le site devra être également adapté aux formats tablette.
   Pour les tablettes, nous sommes libres de faire les adaptations nécessaires.
   Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
2. Concernant les breakpoints, il a été convenu avec le designer UI d’utiliser 992 px et 768 px :
   992 px pour les écrans d’ordinateurs, 768 px pour les tablettes et tout ce qui est en dessous de 768 pour les téléphones portables.
3. Il faut d’abord réaliser l’intégration pour les ordinateurs (desktop first), puis les tablettes et enfin les téléphones.
   L’utilisation des Media Queries permettra de réaliser l’intégration pour les différents supports.
4. Plusieurs formats et tailles d’images ont été exportés.
   Il faudra choisir le format le plus adapté par rapport à la résolution et au temps de chargement.
5. Les icônes proviennent de la bibliothèque Font Awesome (passer par un CDN pour faciliter le chargement des icônes).
6. Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
7. La police du site est Raleway ( Lien de l'importation Google Font https://fonts.google.com/specimen/Raleway ).
8. Il est important d’utiliser les pixels et les pourcentages plutôt que les REM et les EM.
9. l est important d’utiliser Flexbox plutôt que Grid car c’est la techno que l’équipe maîtrise le mieux.
10. Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
11. Il est important d’utiliser des balises sémantiques (type `main`, `header`, `nav`, etc.).
12. Le code doit être valide aux validateurs W3C HTML et CSS.
13. La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox.
    Il faudra tester le prototype sur ces deux navigateurs.
14. Il n’est pas nécessaire de versionner le code.

# Bilan du projet

Un prototype HTML/CSS a été réalisé conformément aux consignes énoncées précédemment.
Les fichiers rendus se composent d'un index.html accompagné de ses fichiers CSS de mise en forme.
Le projet répond aux attentes du client sur les point suivants :

- HTML et CSS conformes aux normes W3C
- Design responsive pour les résolutions desktop, tablettes et smartphones (respect des breakpoints fournis)
- Respect du design et de la charte graphique proposés par les maquettes et la note de synthèse fournies
- Compatibilité du prototype avec les dernières versions de Chrome et de Firefox
- Optimisation du temps de chargement avec intégration judicieuse de résolutions d'images adaptées aux différents supports
- Utilisation majoritaire de flexbox pour optimiser le responsive design
- Usage de balises sémantiques appropriées pour faciliter l'accessibilité et le référencement du site

Temps de réalisation du projet : environ 3 semaines
