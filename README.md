В папке terraform будут проигнорированы следующие файлы,

.terraform - директория с кешем и плалинами
*.tfstate - файлы состояния
*.tfstate.* - backup файлы состояний
.terraform.tfstate.lock.info - lock-файлы для блокировки состояния
*.tfvars - файлы переменных (часто содержат пароли, ключи)
*.tfvars.json - JSON версии файлов переменных
.terraformrc - конфигурационные файлы CLI
terraform.rc - альтернативное имя конфигурации
crash.log - логи аварийных завершений
crash.*.log - все crash-логи
override.tf
override.tf.json
*_override.tf
*_override.tf.json

edit readme for fix branch
