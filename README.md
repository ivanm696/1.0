# 1.0
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
Полезные ссылки и документация
Официальная документация Magisk — https://topjohnwu.github.io/Magisk/
Guides по созданию модулей — https://topjohnwu.github.io/Magisk/guides.html#magisk-modules
Zygisk объяснение — https://github.com/Dr-TSNG/ZygiskNext или https://topjohnwu.github.io/Magisk/guides.html#zygisk
Module template от Magisk — https://github.com/topjohnwu/Magisk/tree/master/scripts/module_installer.sh
MIT License — https://opensource.org/licenses/MIT
Если модуль выполняет конкретные функции (например, твик системы, daemon-сервис) — уточните в Issues или обновите README!
Если найдёте баги или хотите внести улучшения — открывайте Issue или PR! 😊
