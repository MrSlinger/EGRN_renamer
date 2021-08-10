# EGRN_renamer
Переименовщик ЕГРН от Росреестра

Позволяет переименовывать ТОЛЬКО .pdf файлы, которые приходят в паре с файлами .xml, поставляемые Росреестром. Так как у этих xml отсутствует xsl схема в публичном доступе, то эти xml файлы приходят уже вместе с соответствующими pdf. Однако, оба файла имеют корявые имена и в работе в сыром виде не могут быть использованы.

Как использовать:

Закинуть файл egrn_pdf_renamer.py в папку с xml и .pdf файлами Росреестра и запустить. Будут созданы копии всех .pdf файлов, которые удалось ассоциировать друг с другом.
