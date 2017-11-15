# README

Проект, посвящённый прокачиванию компетенций, знаний и умений.
Пока в демонстрационных целях.
Содержит пример применения компетенций:
* Настройка маршрутизации Action Dispatch
* Использование контроллеров Action Controller
* Настройка внешнего вида с помощью bootstrap и Action View
* Создание моделей ActiveRecord
* Связывание моделей между собой
* ...


Версия Ruby MRI 2.4.2. Версия Rails 5.1.4.
Для тестов используется RSpec. Приведены некоторые виды тестов - интеграционные, контроллеров и моделей.
Запуск тестов:
$ rspec spec/

Для развёртывания используется Github.

Используется ActionCable, который можно запустить отдельно, при необходимости, например, используя Puma.