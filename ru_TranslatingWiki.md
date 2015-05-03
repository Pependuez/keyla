Чтобы редактировать описание программы, вам понадобится сначало получить его. Для этого используйте клиент для Subversion. О том, как это сделать, написано [здесь](http://code.google.com/p/keyla/source/checkout) с той разницей, что вместо адреса `http://keyla.googlecode.com/svn/trunk/` надо использовать `http://keyla.googlecode.com/svn/wiki/`.

После того как вы скачали все файлы описания, выберите язык, на который будете опираться, создавая свой перевод. Скопируйте соответствующие файлы и измените префикс на соответствующий языку, на который собираетесь переводить. Например, если вы собираетесь сделать украинский перевод на базе русского, скопируйте все файлы, начинающиеся на _ru_ и переименуйте их, заменив _ru_ на _uk_.

Теперь переведите содержимое файлов. Можно использовать обычный текстовый редактор.

Оформление текста производится с помощью специальных символов (wiki-разметка), описание которых можно найти на странице [WikiSyntax](http://code.google.com/p/support/wiki/WikiSyntax) на Google Code. При переводе оставляйте эти символы без изменений.

После того, как перевод готов, [напишите Issue](http://code.google.com/p/keyla/issues/entry) и вложите изменённые файлы. Если у вас нет аккаунта Google, в порядке исключения можете отправить файлы мне по почте с темой "Keyla wiki localization" (earshinov собака gmail точка com). Сложите все файлы в один архив.