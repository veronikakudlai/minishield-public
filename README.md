# MiniShield

**Free Safari protection for iPhone and iPad.**

MiniShield helps block known ads and tracking requests, hide supported cookie notices and intrusive sign-in prompts, and remove recognized tracking parameters from links. You can also choose to confirm supported links to Telegram, WhatsApp and Discord. This setting is off by default and can be changed at any time. System app links and unknown URL schemes are not intercepted by this feature. Some iOS redirects cannot be intercepted. Choose **Basic**, **Balanced**, or **Strict** protection in the app.

> MiniShield works in Safari, not across all apps. It is not a VPN or an anonymity service. Hiding a cookie notice does not mean cookies were rejected or that all tracking stopped.

## Getting started

After installing MiniShield:

1. Open **iOS Settings → Apps → Safari → Extensions** and enable the MiniShield Web Extension and Content Blocker.
2. Grant the Web Extension access to websites you want it to protect when Safari asks.
3. Open **MiniShield**, choose your protection mode, and customize cookie protection as needed.

Protection depends on Safari permissions, the selected mode and the website. Some banners may remain visible to avoid interfering with essential content.

## Privacy and support

- [Privacy Policy](https://veronikakudlai.github.io/minishield-public/privacy/)
- [Support and bug reports — GitHub Issues](https://github.com/veronikakudlai/minishield-public/issues)
- [Private privacy questions — email](mailto:privacy_policy.ios@proton.me)

**GitHub Issues are public.** Do not post personal information, browsing history, private webpage content or cookie values. Use private email for confidential questions.

MiniShield processes webpage information locally for its protection features. Downloading filter updates can reveal normal connection metadata (such as an IP address) to the file host; details are in the privacy policy.

## What is in this repository?

This is **MiniShield's public information and filter-data repository**, not an installer or the app's source-code repository.

| Content | Where to find it |
| --- | --- |
| Privacy Policy | [English](privacy/index.md) |
| EasyList Cookie filter data | Signed metadata: [stable.json](stable.json) / [stable.sig](stable.sig); versioned files in [releases](releases/) |
| Steven Black hosts data | Signed metadata and snapshots in [hosts](hosts/) |
| EasyList attribution and reuse terms | [Dataset LICENSE](LICENSE) |
| Steven Black attribution and MIT notice | [Hosts license](hosts/LICENSE-StevenBlack.txt) |

The signed datasets are downloaded and verified **by MiniShield**. Ordinary users do not need to download JSON, signatures or host files manually. Private signing keys are not published here.

**Licensing:** the adapted EasyList Cookie filter dataset is published under **CC BY-SA 3.0**; Steven Black's contributed hosts data have a separate **MIT** notice. These dataset licenses do not apply automatically to the independently developed MiniShield application.

<!-- MINISHIELD EASYLIST PROVENANCE BEGIN -->
## EasyList Cookie provenance

Current signed dataset: **v000005**, **6980** rules. Original source: EasyList Cookie List.

- Original EasyList commit: [b461e73d2a4903615a17ee15671343888c0f1f84](https://github.com/easylist/easylist/commit/b461e73d2a4903615a17ee15671343888c0f1f84)
- Adapted rules: [v000005 rules.json](releases/v000005/rules.json)
- Signed manifest: [stable.json](stable.json)
- Release provenance: [v000005 SOURCE.md](releases/v000005/SOURCE.md)
- License: [CC BY-SA 3.0](LICENSE)
<!-- MINISHIELD EASYLIST PROVENANCE END -->

<!-- MINISHIELD HOSTS PROVENANCE BEGIN -->
## StevenBlack hosts provenance

Current signed hosts dataset: **v000001**. Original source: Steven Black.

- Original commit: [681b61eceef1cabaa434394a97babef5d57bdc78](https://github.com/StevenBlack/hosts/commit/681b61eceef1cabaa434394a97babef5d57bdc78)
- Signed hosts list: [v000001 hosts.txt](hosts/releases/v000001/hosts.txt)
- Signed manifest: [hosts/stable.json](hosts/stable.json)
- Release provenance: [v000001 SOURCE.md](hosts/releases/v000001/SOURCE.md)
- License: [MIT](hosts/LICENSE-StevenBlack.txt)
<!-- MINISHIELD HOSTS PROVENANCE END -->
