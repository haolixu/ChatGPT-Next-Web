./
├── CODE_OF_CONDUCT.md
├── Dockerfile
├── LICENSE
├── README.md
├── README_CN.md
├── app
│   ├── api
│   │   ├── anthropic
│   │   │   └── [...path]
│   │   │       └── route.ts
│   │   ├── auth.ts
│   │   ├── common.ts
│   │   ├── config
│   │   │   └── route.ts
│   │   ├── google
│   │   │   └── [...path]
│   │   │       └── route.ts
│   │   ├── openai
│   │   │   └── [...path]
│   │   │       └── route.ts
│   │   ├── upstash
│   │   │   └── [action]
│   │   │       └── [...key]
│   │   │           └── route.ts
│   │   └── webdav
│   │       └── [...path]
│   │           └── route.ts
│   ├── azure.ts
│   ├── client
│   │   ├── api.ts
│   │   ├── controller.ts
│   │   └── platforms
│   │       ├── anthropic.ts
│   │       ├── google.ts
│   │       └── openai.ts
│   ├── command.ts
│   ├── components
│   │   ├── auth.module.scss
│   │   ├── auth.tsx
│   │   ├── button.module.scss
│   │   ├── button.tsx
│   │   ├── chat-list.tsx
│   │   ├── chat.module.scss
│   │   ├── chat.tsx
│   │   ├── emoji.tsx
│   │   ├── error.tsx
│   │   ├── exporter.module.scss
│   │   ├── exporter.tsx
│   │   ├── home.module.scss
│   │   ├── home.tsx
│   │   ├── input-range.module.scss
│   │   ├── input-range.tsx
│   │   ├── markdown.tsx
│   │   ├── mask.module.scss
│   │   ├── mask.tsx
│   │   ├── message-selector.module.scss
│   │   ├── message-selector.tsx
│   │   ├── model-config.tsx
│   │   ├── new-chat.module.scss
│   │   ├── new-chat.tsx
│   │   ├── settings.module.scss
│   │   ├── settings.tsx
│   │   ├── sidebar.tsx
│   │   ├── ui-lib.module.scss
│   │   └── ui-lib.tsx
│   ├── config
│   │   ├── build.ts
│   │   ├── client.ts
│   │   └── server.ts
│   ├── constant.ts
│   ├── global.d.ts
│   ├── icons
│   │   ├── add.svg
│   │   ├── auto.svg
│   │   ├── black-bot.svg
│   │   ├── bot.png
│   │   ├── bot.svg
│   │   ├── bottom.svg
│   │   ├── brain.svg
│   │   ├── break.svg
│   │   ├── cancel.svg
│   │   ├── chat-settings.svg
│   │   ├── chat.svg
│   │   ├── chatgpt.png
│   │   ├── chatgpt.svg
│   │   ├── clear.svg
│   │   ├── close.svg
│   │   ├── cloud-fail.svg
│   │   ├── cloud-success.svg
│   │   ├── config.svg
│   │   ├── confirm.svg
│   │   ├── connection.svg
│   │   ├── copy.svg
│   │   ├── dark.svg
│   │   ├── delete.svg
│   │   ├── down.svg
│   │   ├── download.svg
│   │   ├── drag.svg
│   │   ├── edit.svg
│   │   ├── export.svg
│   │   ├── eye-off.svg
│   │   ├── eye.svg
│   │   ├── github.svg
│   │   ├── image.svg
│   │   ├── left.svg
│   │   ├── light.svg
│   │   ├── lightning.svg
│   │   ├── loading.svg
│   │   ├── mask.svg
│   │   ├── max.svg
│   │   ├── menu.svg
│   │   ├── min.svg
│   │   ├── pause.svg
│   │   ├── pin.svg
│   │   ├── plugin.svg
│   │   ├── prompt.svg
│   │   ├── reload.svg
│   │   ├── rename.svg
│   │   ├── return.svg
│   │   ├── robot.svg
│   │   ├── send-white.svg
│   │   ├── settings.svg
│   │   ├── share.svg
│   │   ├── three-dots.svg
│   │   └── upload.svg
│   ├── layout.tsx
│   ├── locales
│   │   ├── ar.ts
│   │   ├── bn.ts
│   │   ├── cn.ts
│   │   ├── cs.ts
│   │   ├── de.ts
│   │   ├── en.ts
│   │   ├── es.ts
│   │   ├── fr.ts
│   │   ├── id.ts
│   │   ├── index.ts
│   │   ├── it.ts
│   │   ├── jp.ts
│   │   ├── ko.ts
│   │   ├── no.ts
│   │   ├── pt.ts
│   │   ├── ru.ts
│   │   ├── sk.ts
│   │   ├── tr.ts
│   │   ├── tw.ts
│   │   └── vi.ts
│   ├── masks
│   │   ├── cn.ts
│   │   ├── en.ts
│   │   ├── index.ts
│   │   └── typing.ts
│   ├── page.tsx
│   ├── polyfill.ts
│   ├── store
│   │   ├── access.ts
│   │   ├── chat.ts
│   │   ├── config.ts
│   │   ├── index.ts
│   │   ├── mask.ts
│   │   ├── prompt.ts
│   │   ├── sync.ts
│   │   └── update.ts
│   ├── styles
│   │   ├── animation.scss
│   │   ├── globals.scss
│   │   ├── highlight.scss
│   │   ├── markdown.scss
│   │   └── window.scss
│   ├── typing.ts
│   ├── utils
│   │   ├── checkers.ts
│   │   ├── clone.ts
│   │   ├── cloud
│   │   │   ├── index.ts
│   │   │   ├── upstash.ts
│   │   │   └── webdav.ts
│   │   ├── cors.ts
│   │   ├── format.ts
│   │   ├── hooks.ts
│   │   ├── merge.ts
│   │   ├── model.ts
│   │   ├── object.ts
│   │   ├── store.ts
│   │   ├── sync.ts
│   │   └── token.ts
│   └── utils.ts
├── docker-compose.yml
├── docs
│   ├── cloudflare-pages-cn.md
│   ├── cloudflare-pages-en.md
│   ├── cloudflare-pages-es.md
│   ├── cloudflare-pages-ja.md
│   ├── cloudflare-pages-ko.md
│   ├── faq-cn.md
│   ├── faq-en.md
│   ├── faq-es.md
│   ├── faq-ja.md
│   ├── faq-ko.md
│   ├── images
│   │   ├── cover.png
│   │   ├── enable-actions-sync.jpg
│   │   ├── enable-actions.jpg
│   │   ├── head-cover.png
│   │   ├── icon.svg
│   │   ├── more.png
│   │   ├── settings.png
│   │   ├── upstash-1.png
│   │   ├── upstash-2.png
│   │   ├── upstash-3.png
│   │   ├── upstash-4.png
│   │   ├── upstash-5.png
│   │   ├── upstash-6.png
│   │   ├── upstash-7.png
│   │   └── vercel
│   │       ├── vercel-create-1.jpg
│   │       ├── vercel-create-2.jpg
│   │       ├── vercel-create-3.jpg
│   │       ├── vercel-env-edit.jpg
│   │       └── vercel-redeploy.jpg
│   ├── synchronise-chat-logs-cn.md
│   ├── synchronise-chat-logs-en.md
│   ├── synchronise-chat-logs-es.md
│   ├── synchronise-chat-logs-ja.md
│   ├── synchronise-chat-logs-ko.md
│   ├── translation.md
│   ├── user-manual-cn.md
│   ├── vercel-cn.md
│   ├── vercel-es.md
│   ├── vercel-ja.md
│   └── vercel-ko.md
├── next.config.mjs
├── package.json
├── public
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   ├── macos.png
│   ├── prompts.json
│   ├── robots.txt
│   ├── serviceWorker.js
│   ├── serviceWorkerRegister.js
│   └── site.webmanifest
├── scripts
│   ├── delete-deployment-preview.sh
│   ├── fetch-prompts.mjs
│   ├── init-proxy.sh
│   ├── proxychains.template.conf
│   └── setup.sh
├── src-tauri
│   ├── Cargo.lock
│   ├── Cargo.toml
│   ├── build.rs
│   ├── icons
│   │   ├── 128x128.png
│   │   ├── 128x128@2x.png
│   │   ├── 32x32.png
│   │   ├── Square107x107Logo.png
│   │   ├── Square142x142Logo.png
│   │   ├── Square150x150Logo.png
│   │   ├── Square284x284Logo.png
│   │   ├── Square30x30Logo.png
│   │   ├── Square310x310Logo.png
│   │   ├── Square44x44Logo.png
│   │   ├── Square71x71Logo.png
│   │   ├── Square89x89Logo.png
│   │   ├── StoreLogo.png
│   │   ├── icon.icns
│   │   ├── icon.ico
│   │   └── icon.png
│   ├── src
│   │   └── main.rs
│   └── tauri.conf.json
├── tree.txt
├── tsconfig.json
├── vercel.json
└── yarn.lock

34 directories, 247 files
