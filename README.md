# php_modules_dolibarr
Modules php afin de générer des devis, factures, expéditions... en PDF par le biais de Dolibarr.

git clone mon répertoire

## Propale :

- Copier le fichier propale/pdf_propale.modules.php 
- Coller le fichier dans le répertoire de votre Dolibarr : htdocs/core/modules/propale/doc/

Afin que votre modèle sois visible dans votre Dolibarr vous devrez modifier votre base de données (exemple : à l'aide d'une plateforme de gestion de base de donnée comme pgadmin4 ou bien directement en console pour les plus expérimentés).
Vous devrez modifier le fichier llx_document_model et ajouter une nouvelle ligne pour votre nouveau modèle qui se nommera 'propale'.

## Facture :

- Copier le fichier invoice/pdf_invoice.modules.php 
- Coller le fichier dans le répertoire de votre Dolibarr : htdocs/core/modules/propale/doc/

Afin que votre modèle sois visible dans votre Dolibarr vous devrez modifier votre base de données (exemple : à l'aide d'une plateforme de gestion de base de donnée comme pgadmin4 ou bien directement en console pour les plus expérimentés).
Vous devrez modifier le fichier llx_document_model et ajouter une nouvelle ligne pour votre nouveau modèle qui se nommera 'invoice'.

## Expédition :

- Copier le fichier shipment/pdf_shipment.modules.php 
- Coller le fichier dans le répertoire de votre Dolibarr : htdocs/core/modules/propale/doc/

Afin que votre modèle sois visible dans votre Dolibarr vous devrez modifier votre base de données (exemple : à l'aide d'une plateforme de gestion de base de donnée comme pgadmin4 ou bien directement en console pour les plus expérimentés).
Vous devrez modifier le fichier llx_document_model et ajouter une nouvelle ligne pour votre nouveau modèle qui se nommera 'shipment'.
