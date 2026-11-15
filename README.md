# MiniShield

**Free Safari protection for iPhone and iPad.**

MiniShield helps reduce known ads and tracking requests, hide supported cookie notices and optional sign-in prompts, and remove recognized tracking parameters from eligible links. Choose a **Basic**, **Balanced**, or **Strict** protection mode in the app.

**Важно:** MiniShield помогает уменьшать рекламу и отслеживание в Safari. Скрытие cookie-баннера не означает отказ от cookies. [Политика конфиденциальности на русском](https://veronikakudlai.github.io/minishield-public/privacy/).

> MiniShield works in Safari, not across all apps. It is not a VPN or an anonymity service. Hiding a cookie notice does not mean cookies were rejected or that all tracking stopped.

## Getting started

After installing MiniShield:

1. Open **iOS Settings → Apps → Safari → Extensions** and enable the MiniShield Web Extension and Content Blocker.
2. Grant the Web Extension access to websites you want it to protect when Safari asks.
3. Open **MiniShield**, choose your protection mode, and customize cookie protection as needed.

**Как включить:** после установки MiniShield откройте **Настройки iOS → Приложения → Safari → Расширения**, включите Web Extension и Content Blocker и предоставьте доступ к нужным сайтам. Затем откройте MiniShield и выберите режим защиты.

Protection depends on Safari permissions, the selected mode and the website. Some banners may remain visible to avoid interfering with essential content.

## Privacy and support

- [Privacy Policy — English](https://veronikakudlai.github.io/minishield-public/privacy/en/)
- [Политика конфиденциальности — Русский](https://veronikakudlai.github.io/minishield-public/privacy/)
- [Support and bug reports — GitHub Issues](https://github.com/veronikakudlai/minishield-public/issues)
- [Private privacy questions — email](mailto:privacy_policy.ios@proton.me)

**GitHub Issues are public.** Do not post personal information, browsing history, private webpage content or cookie values. Use private email for confidential questions.

MiniShield processes webpage information locally for its protection features. Downloading filter updates can reveal normal connection metadata (such as an IP address) to the file host; details are in the privacy policy.

## What is in this repository?

This is **MiniShield's public information and filter-data repository**, not an installer or the app's source-code repository.

| Content | Where to find it |
| --- | --- |
| Privacy policies | [Русский](privacy/index.md) · [English](privacy/en/index.md) |
| EasyList Cookie filter data | Signed metadata: [stable.json](stable.json) / [stable.sig](stable.sig); versioned files in [releases](releases/) |
| Steven Black hosts data | Signed metadata and snapshots in [hosts](hosts/) |
| EasyList attribution and reuse terms | [Dataset LICENSE](LICENSE) |
| Steven Black attribution and MIT notice | [Hosts license](hosts/LICENSE-StevenBlack.txt) |

The signed datasets are downloaded and verified **by MiniShield**. Ordinary users do not need to download JSON, signatures or host files manually. Private signing keys are not published here.

**Licensing:** the adapted EasyList Cookie filter dataset is published under **CC BY-SA 3.0**; Steven Black's contributed hosts data have a separate **MIT** notice. These dataset licenses do not apply automatically to the independently developed MiniShield application.
