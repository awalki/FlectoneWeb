# Комманда /maintenance
Путь `localizations > ru_ru.yml > command.maintenace`

## Пояснение
Сообщения для комманды `/maintenance`
![command maintenance](/commandmaintenance.png)

## Редактирование
```yaml
<ru_ru.command.maintenance>
```

### По умолчанию
```yaml
maintenance:
  not: "<color:#ff7171><b>⁉</b> Технические работы не идут"
  already: "<color:#ff7171><b>⁉</b> Технические работы уже идут"
  server-description: "<color:#ff7171>В настоящее время проводятся технические работы"
  server-version: "Технические работы"
  kick: "<color:#ff7171>★ На сервере ведутся технические работы"
  format-true: "<fcolor:1>★ Ты <fcolor:2>включил</fcolor:2> технические работы на сервере"
  format-false: "<fcolor:1>★ Ты <fcolor:2>выключил</fcolor:2> технические работы на сервере"
```

## Параметры

- [Комманда](/docs/command/maintenance/)
- [Права](/docs/permission/command/maintenance/)

### `not`

Сообщение при попытке отключения технических работ, если они не включены

### `already`

Сообщение при попытке включения технических работ, если они включены

### `server-description`

Сообщения при просмотре сервера, если включены технические работы

### `server-version`

Название версии сервера, если включены технические работы

### `kick`

Причина исключения с сервера при включении технических работ

### `format-true`

Сообщение при включении технических работ

### `format-false`

Сообщение при отключении технических работ