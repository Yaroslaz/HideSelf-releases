# HideSelf Releases

Public release repository for signed Windows builds and updater artifacts of HideSelf.

This repository is used only for distribution:

- NSIS installers
- updater signatures (`.sig`)
- `latest.json` manifest for Tauri updater

The main development repository may remain private, but updater artifacts must stay publicly accessible so installed clients can download updates without GitHub authentication.

## What Users Download

Users normally need only:

- `HideSelf_<version>_x64-setup.exe`

Updater-enabled clients may also consume:

- `HideSelf_<version>_x64-setup.exe.sig`
- `latest.json`

## Update Channel

HideSelf desktop clients check this repository for the latest published updater manifest and signed installer artifacts.

## Notes

- Releases are published automatically by GitHub Actions from the main HideSelf repository.
- Source code, development workflow, and issue tracking are not hosted here.
- If you need the main project repository, contact the maintainer.

---

# HideSelf Releases

Публичный репозиторий релизов для подписанных Windows-сборок и updater-артефактов HideSelf.

Этот репозиторий используется только для распространения:

- NSIS-инсталляторов
- updater-подписей (`.sig`)
- манифеста `latest.json` для Tauri updater

Основной репозиторий разработки может оставаться приватным, но updater-артефакты должны быть публично доступны, чтобы установленный клиент мог получать обновления без авторизации в GitHub.

## Что скачивают пользователи

Обычно пользователю нужен только:

- `HideSelf_<version>_x64-setup.exe`

Для встроенного updater также используются:

- `HideSelf_<version>_x64-setup.exe.sig`
- `latest.json`

## Канал обновлений

Desktop-клиенты HideSelf проверяют этот репозиторий на наличие свежего updater-манифеста и подписанных установочных файлов.

## Примечания

- Релизы публикуются автоматически через GitHub Actions из основного репозитория HideSelf.
- Исходный код, разработка и issue tracking ведутся не здесь.
- Если нужен основной репозиторий проекта, свяжитесь с владельцем.
