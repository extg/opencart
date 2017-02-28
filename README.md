# OpenCart

Русская сбока с сайта http://opencart-russia.ru/

Взял `.gitignore` из [оригинального репозитория][opencart] Сделал изменения в `.gitignore` т.к. в русской сборку было что-то в папке `upload/system/storage/modification/`

```diff
@@ -15,7 +15,7 @@
 !/upload/system/storage/cache/index.html

 # Modification Files
-# /upload/system/storage/modification/*
+/upload/system/storage/modification/*
 !/upload/system/storage/modification/index.html

 # Templates Files
 ```

 [opencart]: https://github.com/opencart/opencart