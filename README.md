# devops-netology
1st_line

```
**/.terraform/* - игнор всех файлов в скрытой папке ".terraform", не важно какой путь к папке.
*.tfstate и *.tfstate.* - игнор всех файлов с расширением *.tfstate или  "любые символы.tfstate.другое расширение или символы имени" находящихся в той папке, где лежит .gitignore
crash.log и crash.*.log - любые логи с именем crash или crash.символы.log находящихся в той папке, где лежит .gitignore
*.tfvars и *.tfvars.json - любые файлы с указанными рашсирениями находящихся в той папке, где лежит .gitignore
override.tf override.tf.json *_override.tf *_override.tf.json - аналогично тоу что описано выше
.terraformrc terraform.rc - игнор файлов конфигурации, находящихся в той папке, где лежит .gitignore
```
