terraform/.gitignore

Благодаря файлу .gitignore в директории terraform будут проигнорированы:

Будут проигнорировано все содержимое директории с название ".terraform"

Будут проигнорированы все файлы со следующими расширениями:
`.tfstate` и `.tfstate.*`
`.tfvars` и `.tfvars.json`
`.log`

Будут проигнорированы все файлы со следующими именами:
`crash.log` и `crash.*.log`
`override.tf`, `override.tf.json`
`.terraform.tfstate.lock.info`
`.terraformrc` или `terraform.rc`

Так же будут игнорироваться файлы в имени которых содержится `_override.tf` или `_override.tf.json`

Будут игнорироваться все файлы начинающиеся с `crash.` и заканчивающиеся на `.log`, 
так же все файлы начинающиеся и заканчивающиется на `_override.tf` и все фыайлы соответствующие `*_override.tf.json`
