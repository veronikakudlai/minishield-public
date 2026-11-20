# MiniShield

**Язык:** Русский · [English](README.md)

**Бесплатная защита Safari для iPhone и iPad.**

MiniShield помогает блокировать известную рекламу и отслеживающие запросы, скрывать cookie-баннеры и навязчивые предложения входа, а также очищать ссылки от известных параметров отслеживания. При желании можно включить подтверждение перед открытием других приложений по ссылкам из Safari. Эта настройка по умолчанию выключена, и её можно изменить в любой момент. Некоторые переходы iOS не удаётся перехватить. Доступны три режима защиты: **Basic**, **Balanced** и **Strict**.

> MiniShield работает только в Safari, а не во всех приложениях. Это не VPN и не средство анонимности. Скрытие cookie-баннера не означает отказ от cookies или прекращение всех видов отслеживания.

## Как начать

После установки MiniShield:

1. Откройте **Настройки iOS → Приложения → Safari → Расширения** и включите MiniShield Web Extension и Content Blocker.
2. При запросе Safari разрешите веб-расширению доступ к сайтам, которые хотите защищать.
3. Откройте **MiniShield**, выберите режим защиты и при необходимости настройте обработку cookie-баннеров.

Работа защиты зависит от разрешений Safari, выбранного режима и особенностей сайта. Некоторые баннеры могут оставаться видимыми, чтобы не нарушать работу важных элементов страницы.

## Конфиденциальность и поддержка

- [Политика конфиденциальности — русский](https://veronikakudlai.github.io/minishield-public/privacy/)
- [Политика конфиденциальности — английский](https://veronikakudlai.github.io/minishield-public/privacy/en/)
- [Поддержка и сообщения об ошибках — GitHub Issues](https://github.com/veronikakudlai/minishield-public/issues)
- [Частные обращения по вопросам конфиденциальности — email](mailto:privacy_policy.ios@proton.me)

**Обращения в GitHub Issues общедоступны.** Не публикуйте персональные данные, историю посещений, содержимое приватных страниц или значения cookies. Для конфиденциальных вопросов используйте электронную почту.

MiniShield обрабатывает сведения со страниц локально. При загрузке обновлений фильтров сервис размещения файлов может получать обычные сетевые метаданные (например, IP-адрес). Подробности приведены в политике конфиденциальности.

## Что находится в этом репозитории?

Это **публичный репозиторий информации о MiniShield и данных фильтров**, а не установщик приложения или репозиторий его исходного кода.

| Содержимое | Где найти |
| --- | --- |
| Политики конфиденциальности | [Русский](privacy/index.md) · [Английский](privacy/en/index.md) |
| Фильтры EasyList Cookie | Подписанные данные: [stable.json](stable.json) / [stable.sig](stable.sig); версии — в [releases](releases/) |
| Списки доменов Steven Black | Подписанные данные и версии — в [hosts](hosts/) |
| Авторство EasyList и условия использования | [Лицензия набора данных](LICENSE) |
| Лицензия Steven Black (MIT) | [Уведомление об авторстве](hosts/LICENSE-StevenBlack.txt) |

MiniShield самостоятельно загружает и проверяет подписанные данные. Пользователю не нужно вручную скачивать JSON, подписи или файлы доменных списков. Закрытые ключи подписи здесь не публикуются.

**Лицензии:** адаптированные фильтры EasyList Cookie распространяются по лицензии **CC BY-SA 3.0**, а данные Steven Black — с отдельным уведомлением **MIT**. Эти лицензии не распространяются автоматически на независимо разработанный исходный код MiniShield.

<!-- MINISHIELD EASYLIST PROVENANCE BEGIN -->
## Происхождение EasyList Cookie

Текущий подписанный набор: **v000004**, **6965** правил. Источник — EasyList Cookie List.

- Исходный commit EasyList: [70605720dcca215d4df6871fac30272338ec8d30](https://github.com/easylist/easylist/commit/70605720dcca215d4df6871fac30272338ec8d30)
- Адаптированные правила: [v000004 rules.json](releases/v000004/rules.json)
- Подписанный манифест: [stable.json](stable.json)
- Происхождение выпуска: [v000004 SOURCE.md](releases/v000004/SOURCE.md)
- Лицензия: [CC BY-SA 3.0](LICENSE)
<!-- MINISHIELD EASYLIST PROVENANCE END -->

<!-- MINISHIELD HOSTS PROVENANCE BEGIN -->
## Происхождение StevenBlack hosts

Текущий подписанный набор hosts: **v000001**. Источник — Steven Black.

- Исходный commit: [681b61eceef1cabaa434394a97babef5d57bdc78](https://github.com/StevenBlack/hosts/commit/681b61eceef1cabaa434394a97babef5d57bdc78)
- Подписанный список: [v000001 hosts.txt](hosts/releases/v000001/hosts.txt)
- Подписанный манифест: [hosts/stable.json](hosts/stable.json)
- Происхождение выпуска: [v000001 SOURCE.md](hosts/releases/v000001/SOURCE.md)
- Лицензия: [MIT](hosts/LICENSE-StevenBlack.txt)
<!-- MINISHIELD HOSTS PROVENANCE END -->
