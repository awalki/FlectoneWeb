# Комманда /unwarn
Путь `localizations > en_us.yml > command.unwarn`

## Пояснение
Сообщения для комманды `/unwarn`
![command unwarn](/commandunwarn.png)

## Редактирование
```yaml
<en_us.command.unwarn>
```

### По умолчанию
```yaml
unwarn:
  null-player: "<color:#ff7171><b>⁉</b> This player does not exist"
  not-warned: "<color:#ff7171><b>⁉</b> This player is not warned"
  format: "<color:#98FB98>☻ Player <display_name> unwarned"
```

## Параметры

- [Комманда](/docs/command/unwarn/)
- [Права](/docs/permission/command/unwarn/)

### `null-player`

Сообщение, если введённый игрок не найден

### `not-warned`

Сообщение, если введённый игрок не имеет предупреждения

### `format`

Сообщение при снятии предупреждения
