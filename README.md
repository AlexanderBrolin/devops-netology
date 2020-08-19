# devops-netology
Согласно содержанию файла ./terraform/.gitignore будут проигнорированы при коммите:
Все файлы в локальном каталоге .terraform (на что указывает и окончание шаблона на /*)
Файлы содержащие в расширении .tfstate или названии .tfstate.
Файл лога crash.log
Файлы с раширением .tvars
Файлы override.tf, verride.tf.json, шаблоны содержащие любое количество символов перед override.tf и verride.tf.json
Файлы terraform.rc и его скрытый аналог .terraformrc
