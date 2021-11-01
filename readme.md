# Sergey Sokolov
# change
# change2

change fix

# Local .terraform directories 
**/.terraform/* игнорировать все файлы в скрытой папке терраформ расположенной в любом месте репозитория

# .tfstate files
*.tfstate игнорирует файлы с этим расширением
*.tfstate.* игнорирует скрытые файлы где в названии tfstate в середине с любым расширением

# Crash log files
crash.log игнорирует этот файл

# Exclude all .tfvars files, which are likely to contain sentitive data, such as
# password, private keys, and other secrets. These should not be part of version
# control as they are data points which are potentially sensitive and subject
# to change depending on the environment.
#
*.tfvars игнорирует все файлы с этим расширением

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf  игнорирут все файлы с данным названием и расширением
override.tf.json тоже самое 
*_override.tf игнорирует файлы с любыми знаками перед данным названием и расширением
*_override.tf.json игнорирует файлы с любыми знаками перед данным названием и расширением

# Include override files you do wish to add to version control using negated pattern
#
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc игнорирует такие скрытые файлы
terraform.rc игнорирует файлы данным названием и расширением
