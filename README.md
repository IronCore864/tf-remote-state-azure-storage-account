# Remote State Files for Terraform in Azure Storage Account

## Deploy

```
./tfstate_storage.sh
``` 

Save the output, which is needed in the next step

## config.tf

Create a config.tf file for the env you choose to deploy, according to the template `config.tf.template`.

You need subscription, service principal related info, as well as the storage account info generated in the previous step.

