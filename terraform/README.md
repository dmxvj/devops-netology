# Будут игнорироваться скрытые директории .terraform 
**/.terraform/*

# Будут игнорироваться файлы с расширением .tfstate или содержащие внутри название .tfstate.
*.tfstate
*.tfstate.*

# Будут игнорироваться журналы крэша 
crash.log

# Будут игнорироваться файлы с расширением .tfvars, содержащие приватную информацию
*.tfvars

# Будут игнорироваться файлы содержащие название override
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Укажите файлы, которые вы хотите включить в VCS 
#
# !example_override.tf

# Укажите файлы, которые будут игнорироваться в выводе команды: terraform plan -out=tfplan
# example: *tfplan*

# Игнорировать конфигурационные файлы terraform 
.terraformrc
terraform.rc
