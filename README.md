<div align="center">

# Marketplace WebView — Libermall (Android, archived)

> ⚠️ **Archived 2026-05-25.** This Android WebView wrapper is no longer maintained. The active Libermall surfaces are the Telegram Mini App at [`id.libermall.com/app/`](https://id.libermall.com/app/) and the responsive web at [`libermall.com`](https://libermall.com).

[![Status: archived](https://img.shields.io/badge/status-archived-lightgrey?style=flat-square)](#)
[![Superseded by](https://img.shields.io/badge/superseded%20by-Telegram%20Mini%20App-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://id.libermall.com/app/)

</div>

---

## What this was

A minimal Android WebView wrapper that loaded the Libermall NFT marketplace inside a native Android app shell. It was generated from a standard Android Studio template and used briefly while we evaluated whether to ship a native Android app.

## Why it's archived

In 2026 we chose the Telegram-first strategy. The [Libermall ID Mini App](https://github.com/LiberMall/libermall-id-miniapp), the [Telegram wallet bot](https://github.com/LiberMall/Telegram-Cryptocurrency-Wallet-Libermall) and the responsive web at [`libermall.com`](https://libermall.com) cover the same use-cases without the maintenance burden of a Play Store presence.

## Security notice

> 🚨 **Historical credential leak (disclosed 2026-05-25).** Prior commits of this repository contained the Android **signing keystore** (`key.jks`), a `password.txt` file with the keystore password (`12345678`), `local.properties`, and signed `.apk` / `.aab` build artifacts. These were committed to a public repository and propagated to forks.
>
> All sensitive build artefacts have been **removed from HEAD**. The historical signing key is considered **compromised** and **must not** be reused for any future signed Android build. If a Play Store listing exists, it requires a [Play App Signing key rotation](https://support.google.com/googleplay/android-developer/answer/9842756).
>
> A full git-history rewrite (`git filter-repo`) of the upstream alone cannot neutralise the exposure (forks retain copies), so we rely on **rotation** rather than on history rewriting. The repository is now archived.

## Looking for the active stack?

| Surface | URL | Repo |
|---|---|---|
| Telegram Mini App | [`id.libermall.com/app/`](https://id.libermall.com/app/) | [`LiberMall/libermall-id-miniapp`](https://github.com/LiberMall/libermall-id-miniapp) |
| Telegram identity bot | [`@LibermallIDbot`](https://t.me/LibermallIDbot) | [`LiberMall/libermall-id-bot`](https://github.com/LiberMall/libermall-id-bot) |
| Identity layer / SSO | [`id.libermall.com`](https://id.libermall.com) | [`LiberMall/libermall-id-landing`](https://github.com/LiberMall/libermall-id-landing) |
| Web marketplace | [`libermall.com`](https://libermall.com) | private |
| NFT marketplace front-end (reference) | [`libermall.github.io/TON-Marketplace-NFT-Web-Frontend`](https://libermall.github.io/TON-Marketplace-NFT-Web-Frontend/) | [`LiberMall/TON-Marketplace-NFT-Web-Frontend`](https://github.com/LiberMall/TON-Marketplace-NFT-Web-Frontend) |
| FunC contracts | — | [`LiberMall/Contracts`](https://github.com/LiberMall/Contracts) |
| NFT CLI tool | — | [`LiberMall/tnt`](https://github.com/LiberMall/tnt) |
| DEX | [`dex.libermall.com`](https://dex.libermall.com) | private |
| Payments | [`pay.libermall.com`](https://pay.libermall.com) | private |
| Cards | [`card.libermall.com`](https://card.libermall.com) | private |

## License

[MIT](LICENSE) © 2026 Libermall.

---

<div align="center">

**Part of the [Libermall ecosystem](https://libermall.com).**

[Identity](https://id.libermall.com) · [DEX](https://dex.libermall.com) · [Pay](https://pay.libermall.com) · [Card](https://card.libermall.com) · [Reviews](https://sites.reviews) · [TonChat AI](https://tonchat.ai) · [TON.CEO](https://ton.ceo)

</div>
