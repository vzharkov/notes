# Что не нравится в рельсах:
1. Callbacks. Со временем превращаются в неподдерживаемые условия, загромождая модель.
2. Concerns на контроллеры и в целом. как правило туда запихивается код, который зависит от каких-то инстанс-переменных.
Это в итоге приводит к тому, что сильно возрастает связность кода. Зачастую задачу вполне можно решить с помощью Dependency injection или простого вызова сервисного класса.
3. Не предлагается механизма миграции данных. часто пишут миграции данных в миграции схемы.
