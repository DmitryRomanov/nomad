# nomad

Как я это вижу:

1. создаем виртуальные машины, 3 шт
2. применяем ансибл роль на всех.
3. отправляем скрипты "copy hlc" на виртуалки и исполняем их agent-ом, все это ансиблом. Должен собраться кластер Nomad-а.
4. ставим докер на виртуалки копируем файлы-задачи по использованию docker-драйвера. стартуем job.



