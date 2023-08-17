<h1 align="center">

<br/>

🐻😎⏱️

<div>レ・ジット</div>

**Le JIT**

</h1>

<h2 align="center">

**_/lɪˈdʒɪt/ ("legit")_**:

Node.jsモジュールを使わずにJIT SSR（ジャストインタイム、サーバーサイドレンダリング）で実行されるベアボーンなフルスタックTypeScriptアプリの生成方法

<br/>

🦕 [Deno (ディーノー)](https://deno-ja.vercel.app/manual@v1.9.1/introduction)で作られました。

<br/>

</h2>

## 1. Denoのインストール

[Denoのインストールドキュメント](https://deno-ja.vercel.app/manual@v1.9.1/getting_started/installation)を参照し、お使いの環境に合わせて最も新しいバージョンをインストールしてください。

## 2. エディタまたはIDE用のDeno拡張機能をインストールします。

詳しくは、[Denoの拡張機能インストールドキュメント](https://deno-ja.vercel.app/manual@v1.9.1/getting_started/setup_your_environment#%E3%82%A8%E3%83%87%E3%82%A3%E3%82%BF%E3%83%BC%E3%81%A8ide)をご参照ください。

## 3.Denoで[「Fresh」](https://fresh.deno.dev/)インストールを実行します。

```
deno run -A -r https://fresh.deno.dev .
```

[プロジェクトの作成方法はこちら](https://fresh.deno.dev/docs/getting-started/create-a-project)を参照してください。

上記のコマンドを実行した後、プロンプトに答えると、ターミナルに以下のような出力が表示されます。


```
$ deno run -A -r https://fresh.deno.dev .

 🍋 Fresh: The next-gen web framework. 

The target directory is not empty (files could get overwritten). Do you want to continue anyway? [y/N] y
Let's set up your new Fresh project.

Fresh has built in support for styling using Tailwind CSS. Do you want to use this? [y/N] y
Do you use VS Code? [y/N] y
The manifest has been generated for 5 routes and 1 islands.

Project initialized!

Run deno task start to start the project. CTRL-C to stop.

Stuck? Join our Discord https://discord.gg/deno

Happy hacking! 🦕
```


...

<br/>


以下のドキュメントは、以下の水平ルールの後にFreshによって生成されました：

(日本語の翻訳は以下の下にあります)

---

# Fresh project

Your new Fresh project is ready to go. You can follow the Fresh "Getting
Started" guide here: https://fresh.deno.dev/docs/getting-started

### Usage

Make sure to install Deno: https://deno.land/manual/getting_started/installation

Then start the project:

```
deno task start
```

This will watch the project directory and restart as necessary.

…

最後には上記の翻訳です。


## Fresh・プロジェクト
新しいFreshプロジェクトは準備完了です。フレッシュの "Getting Started"のガイドに従うことができます: https://fresh.deno.dev/docs/getting-started

### 使用方法

Denoがインストールされていることを確認してください: https://deno-ja.vercel.app/manual@v1.9.1/getting_started/installation

次にプロジェクトを開始します：

```
deno タスク開始
```

これはプロジェクト・ディレクトリを監視し、必要に応じて再起動します。
