# BDO Forge для Windows

Приложение портала [bdo-forge.com](https://bdo-forge.com) для Black Desert: весь портал в своём
окне, живой трекер добычи через OBS, режим стримера и Чёрный дух на рабочем столе.

Здесь лежат только выпуски — установщик и история версий. Исходный код приложения в репозиторий
не входит.

## Скачать

**[Последняя версия →](https://github.com/zo1tanv/BDO-Forge-App/releases/latest)**

Тот же файл отдаётся и с сайта: [bdo-forge.com/app](https://bdo-forge.com/app). Оба места —
одна и та же сборка с одинаковой контрольной суммой; выбирайте, что быстрее открывается.

## Установка

1. Скачайте `BDO-Forge-Setup-<версия>.exe` со страницы выпуска.
2. Запустите. Права администратора не нужны — приложение ставится в профиль пользователя.
3. Windows SmartScreen предупредит о неизвестном издателе: установщик пока не подписан
   сертификатом Authenticode. «Подробнее» → «Выполнить в любом случае».

Требуется Windows 10 или 11, 64 бита.

### Проверка файла

У каждого выпуска рядом с установщиком лежит `SHA256SUMS.txt`. Сравните с тем, что посчитает
Windows:

```powershell
Get-FileHash BDO-Forge-Setup-1.1.0.exe -Algorithm SHA256
```

## Обновления

Приложение обновляется само: оно проверяет подписанный манифест на bdo-forge.com, скачивает
установщик и проверяет подпись выпуска и контрольную сумму перед запуском. Файлы отсюда нужны
только для первой установки — следить за выпусками вручную не требуется.

## Что нового

История версий — в [CHANGELOG.md](CHANGELOG.md) и на странице каждого выпуска.

## О проекте

BDO Forge — фан-проект сообщества. Не связан с Pearl Abyss и не аффилирован с ней. Black Desert
и связанные названия принадлежат их правообладателям.

Ошибки и предложения: [bdo-forge.com/feedback](https://bdo-forge.com/feedback).

---

**English.** BDO Forge for Windows is the desktop app of [bdo-forge.com](https://bdo-forge.com),
a community fan project for Black Desert. This repository hosts the releases only. Download the
[latest release](https://github.com/zo1tanv/BDO-Forge-App/releases/latest) or get the same build
from [bdo-forge.com/app](https://bdo-forge.com/app). Windows 10/11, 64-bit. The installer is not
yet signed with Authenticode, so SmartScreen shows an unknown-publisher warning. Not affiliated
with Pearl Abyss.
