# azuretemplates

TO DELETE ALL TAGGED RESOURCE GROUPS
az group list --tag delete --query [].name -o tsv | xargs -otl az group delete --no-wait  -n
