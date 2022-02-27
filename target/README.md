Это результат выполнения команд (из родительского каталога):
   $ helm template users-rest-api . > target/manifests-to-deploy.yaml
   $ helm package --destination ./target/ .