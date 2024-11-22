# Espace déco

# Sommaire

- [Modop](#modop)
- [Infos & liens utiles](#infos-et-liens-utiles)

## MODOP

- [Aller dans l'espace CONTENT sur le BO Drupal](https://www.pointp.fr/admin/content)
- Créer une "Page éditoriale"
- Configuration :
    - Général => Titre => Renseigner le titre de la page
    - Menu latéral droit
        - Metatags => Basic Tags :
            - Page title => Renseigner le titre de la page
            - Description => Renseigner la description de la page
        - Alias d'URL
        - Décocher "*Générer automatiquement un alias d'URL*"
        - Alias d'URL => Renseigner l'url de la page : "/espace-deco/avant-apres/{mots-clés-du-titre}"
- Intégration du contenu => Sections
    - Section 1 = **Titre h1**
        - Mise en page => Mise en page Desktop => 100
        - Gestion des couleurs => Couleur du titre => #ffffff
        - Blocs => 1 bloc HTML Libre => `HTML + CSS` = `espace_deco/pages_avant_apres/section_1/header.html`
    - Section 2 = **Sommaire**
        - Mise en page => Mise en page Desktop => 25
        - Gestion des couleurs => Couleur du titre => #ffffff
        - Blocs => 1 bloc HTML Libre => `HTML + CSS` = `espace_deco/pages_avant_apres/section_2/summary.html`
    - Section 3 = **Contenu principal**
        - Mise en page => Mise en page Desktop => 75
        - Gestion des couleurs => Couleur du titre => #ffffff
        - Blocs :
        -   Bloc HTML Libre 1 = `CSS` = `espace_deco/pages_avant_apres/section_3/css.html`
        -   Bloc HTML Libre 2 = `HTML` = `espace_deco/pages_avant_apres/section_3/section_3.html`
    - Section 4 = **Blocs de maillage**
        - Mise en page => Mise en page Desktop => 100
        - Gestion des couleurs => Couleur du titre => #ffffff
        - `HTML + CSS` = `espace_deco/pages_avant_apres/section_4/section_4.html`

## Infos et liens utiles

### Suivi

[Roadmap](https://docs.google.com/spreadsheets/d/1ww1uhOs1wec5JJ3mUsHpMVi6EE7-XfTmBFajqXXwMR8/edit?usp=sharing)

### Récupérer le contenu

[SharePoint pour récupérer les images + le contenu](https://saintgobain.sharepoint.com/sites/AVANTAPRESTEAM/Documents%20partages/Forms/AllItems.aspx?csf=1&web=1&e=abAPfp&OR=Teams%2DHL&CT=1731502378842&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiI0OS8yNDEwMjAwMTMxNiIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D&CID=f2eb7ead%2D4a71%2D41b9%2D9306%2D90a82fb67826&FolderCTID=0x012000EFD29225D090064C828BBF59DB3EB1E1&id=%2Fsites%2FAVANTAPRESTEAM%2FDocuments%20partages%2FGeneral)

### Déposer les visuels sur le server partagé

- [Avant/Après](\\x98sl051psmb0ap.dtc3.cf.saint-gobain.net\IMPULSE_PROD_PAGES_pointp\imgs\efficience\avant-apres)
- [Tendances](\\x98sl051psmb0ap.dtc3.cf.saint-gobain.net\IMPULSE_PROD_PAGES_pointp\imgs\efficience\page_tendances)

### HUB

- [Hub avant/après - BO](https://www.pointp.fr/node/5141/edit?destination=/admin/content%3Ftitle%3Davant%26type%3DAll%26status%3DAll%26langcode%3DAll)
- [Hub avant/après - FO](https://www.pointp.fr/espace-deco/avant-apres/les-projets-de-renovation-realises-avec-nos-produits)

### Avant/Après

- [Exemple de page sur le BO](https://www.pointp.fr/node/8846/edit?destination=/admin/content)
- [Exemple de page sur le FO](https://www.pointp.fr/avant-apres-une-salle-deau-familiale-au-look-vintage)

### Infos

[MEMO](https://saintgobain.sharepoint.com/:b:/r/sites/Webmastering/Documents%20partages/General/Fiches%20r%C3%A9cap%20et%20doc/M%C3%A9mos/Int%C3%A9gration/Avant-Apr%C3%A8s/M%C3%A9mo%20-%20Avant-Apr%C3%A8s%20%20POINT.P.pdf?csf=1&web=1&e=SPWQZR)

### Contacts

- Questions intégration : Sarah Güngör ou Maëlle Eveno
- Questions contenu / process : Carine Kouassi ou Charlotte Thizy