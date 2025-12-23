# ЗАПУСК
- в главной директории прописать docker-compose up -d
- docker exec OnlyTestWeb composer install для установки через докер всех зависимостей
- docker exec OnlyTestWeb composer update чтобы сгенерировать модели из схемы бд и обновить саму схему (можно отдельно прописать docker exec OnlyTestWeb composer run-script propel:reverse, затем docker exec OnlyTestWeb composer run-script propel:build)
