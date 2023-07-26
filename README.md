# ansible-zimbra
Конфигурация zimbra

zmstatuslog.j2 - Увеличивает лимит с 60 секунд до 360 на выполнения команды zmcontrol status для скрипта zmstats, path /opt/zimbra/libexec/zmstatuslog исправляет возможные ошибки в работе крон и агента заббикса для отслеживания состояний служб.
