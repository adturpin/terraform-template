template issue de : https://blog.stephane-robert.info/docs/infra-as-code/provisionnement/terraform/introduction/


Le fichier main.tf qui est le fichier principal d’un projet terraform

Le fichier provider.tf pour y définir les fournisseurs

Le fichier variables.tf pour les variables principales

Le fichier terraform.tfvars pour les variables secrètes qui ne sera pas stocké dans votre repository git

Le fichier de variables *.auto.tfvars variables qui sont lues automatiquement

Le fichier outputs.tf pour y définir tout ce qui sera affiché

Les fichiers resources.tf pour un petit projet un simple fichier resources.tf suffira pour de plus prend vous pouvez en créer plusieurs avec des noms explicites.

Les modules