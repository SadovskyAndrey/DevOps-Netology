# DevOps-Netology

editet

будут игнорироваться:

1.Локальные директории терраформа в папке .terraform

2.Файлы с расширением .tfstate

3.Логи ошибок crash.log crash.*.log

4.Файлы содержашие приватную информацию (пароли , логины и прочее) с раширением .tfvars

5.Переопределенные файлы `override.tf override.tf.json`

6.Файлы `example_override.tf`даже если он попадает под исключения описанные выше.

7.Файлы команды `terraform plan -out=tfplan

8.Файлы CLI конфигурации с расширением `.terraformrc  .rc`
