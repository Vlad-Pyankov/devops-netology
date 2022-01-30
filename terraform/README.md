##Предназначение файла .gitignore
###Будут проигнорированны следущие файлы. 

###файлы:
    crash.log  
    override.tf  
    override.tf.json  
    .terraformrc  
    terraform.rc

###файлы с расширением:
    *.tfvars
 
###все файлы во вложенной папке, вне зависимости от глубины вложения:
    **/.terraform/*

###файлы заканчивающиеся на:
    *.tfstate
    *_override.tf  
    *_override.tf.json
###файлы по маске, где звездочкой обозначенны любое количество символов:
    *.tfstate.*  
    crash.*.log
