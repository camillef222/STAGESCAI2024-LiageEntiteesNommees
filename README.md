# STAGESCAI2024-LiageEntitesNommees
 Stage SCAI 2024 sur le liage d'entités nommées

Dans le dossier "Entitylinking_spacy", vous trouverez un programmme détaillé sous le format .ipynb et également .py qui permet d'effectuer un liage avec l'outil entitylinker de Spacy, ainsi qu'un calcul de similarité entre l'entité traitée et l'entité wikidata avec la/lesquelle(s) elle est liée. 

Dans l'exemple mis à disposition, le traitement est effectué avec un modèle de langue en français, mais il est tout à fait possible de le fair avec une autre langue (par exemple l'anglais). Le code reste le même peu importe la langue utilisée, et les lignes où des changements doivent être effectués sont commentées (notamment lors de l'import du modèle et de ses appels). 

Vous effectuerez dans un premier temps la REN effectuée par spacy ainsi que le liage avec l'outil entitylinker qui fonctionne avec la base de données Wikidata. Cette première sortie sera stockée dans le dossier "SORTIEJSON_LINKING" (modifier la variable "output_dir" si souhait d'un autre nom de dossier).
Dans un second temps, on effectue le calcul de similarité en récupérant les données crées précédemment dans "SORTIEJSON_LINKING" et on les stocke dans "Resultat_entity-linking".

Les imports nécessaires sont effectués au début du traitement (version 3.7.5 pour spacy et spacy-entity-linker).
