Privet
Файл gigtignore в корне репозитория не будет игнорировать ничего, так как он пуст.
Файл gitignore в директории terraform будет игнорировать следующие фалы и при чем ОТНОСИТЕЛЬНО директории terraform
**/.terraform/*
*.tfstate
*.tfstate.*
*.tfvars
*.tfvars.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json
.terraformrc
terraform.rc