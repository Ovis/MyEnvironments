# 開発環境をさらしてみる

全部じゃないけどね。だって恥ずかしいじゃん？

これも入れると便利だよってのがあればIssuesに記入いただけると嬉しいです。必ずしも入れるという訳にも行きませんが。

なんならPRも一緒に貰えると踊って喜びます。

## 環境の前提条件

- よく利用する開発対象は以下の通り
    - WPF
    - ASP.NET Core
    - .NET Core Console Application
    - .NET Core Windows Service
- Azure・・・は趣味で触る程度
- 基本はChocolateryで入れたい
- でもVisual Studioなど無理がある場合は、別途できるだけCLIで入れたい
# Chocolatreyによるインストール

install-choco.cmdを実行するとChocolateryをインストールし、chocolatery.configに設定しているアプリを一括でインストールします。多分。

CubePDFとCubePDF Utilityはハッシュが違うと怒られるけど、一応忘れないように書いておいてあります。

SSMSが英語で入ってしまうのが悩み。最新でもないし。

# Visual Studio

インストーラーを[ダウンロード](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=professional&rel=16&utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=link+cta&utm_content=download+commandline+parameters+vs2019+rc)して「vs_professional.exe」にリネームする。


そのあとinstall-vs-pro.cmdを実行する