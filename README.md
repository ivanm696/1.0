# 1.0 – Magisk/Zygisk Module
Это репозиторий с Magisk/Zygisk модулем версии 1.0 для Android. Модуль содержит скрипты установки, конфигурацию и бинарные файлы (APK и daemon).
Проект распространяется под MIT License.
Содержимое репозитория
Скрипты:
customize.sh — кастомизация модуля
action.sh, post-fs-data.sh, service.sh — основные хуки Magisk
uninstall.sh, verify.sh — удаление и верификация
util_functions.sh — утилиты
Конфигурация:
module.prop — метаданные модуля
system.prop — проперти системы
sepolicy.rule — SELinux правила
Бинарники:
daemon, daemon.apk, manager.apk
Папки: META-INF/com/google/android (для Magisk установки), bin, framework, lib
Установка
Скачайте ZIP из репозитория (или соберите самостоятельно).
Установите через Magisk Manager → Modules → Install from storage.
Перезагрузите устройство.
