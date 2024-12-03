---
theme: ./
title: Beardy Theme
info: Beardy Slidev theme by Piyo Puffin
fonts:
  provider: google
  sans: M PLUS 1
---

# Beardyテーマ

Presentation slides for developers

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" flex="~ justify-center items-center gap-2" hover="bg-white bg-opacity-10">
    次のページへ <div class="i-carbon:arrow-right inline-block"/>
  </span>
</div>

---
layout: default
---
# 目次
<Toc columns="2"></Toc>
---
layout: default
---

# Slidevとは?
Slidevは、以下の機能を備えた、開発者のために設計されたスライドメーカーとプレゼンテーションツールです。

- 📝 **Text-based** - マークダウン記法で執筆に集中し、後からスタイリングができます
- 🎨 **Themable** - npmパッケージでテーマを共有し、再利用できます
- 🧑‍💻 **Developer Friendly** - コードハイライティング、自動補完のついたライブコーディング
- 🤹 **Interactive** - Vueコンポーネントが埋め込み可能で表現力を高めることができます
- 🎥 **Recording** - built-inの録画、カメラ機能
- 📤 **Portable** - PDF、PPTX,、PNGまたはホスティング可能なSPAとしてエクスポートできます
- 🛠 **Hackable** - ウェブページで可能なことはほとんどすべてSlidevで可能です。

<br>
<br>

Slidevの特長についてもっと知りたい方は [こちら](https://sli.dev/guide/why)

---

# ナビゲーション

下左辺の角にマウスオーバーすると、ナビゲーションコントロールパネルを開くことができます。

## キーボードショートカット

|     |     |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | 次のアニメーションまたはスライドへ |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | 前のアニメーションまたはスライドへ |
| <kbd>up</kbd> | 前のスライドへ |
| <kbd>down</kbd> | 次のスライドへ |

---
layout: quote
---
# hogehoge
---
layout: image-right
image: https://cover.sli.dev
---

# コード

コードスニペットを書くだけでコードハイライティングを適用できます。

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: quote
class: "text-center"
---

# Learn More

[Documentation](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
