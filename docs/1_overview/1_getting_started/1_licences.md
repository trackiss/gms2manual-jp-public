---
layout: default
title: GameMaker Studio 2 のライセンス
nav_order: 1
parent: セットアップ
---

## GameMaker Studio 2 のライセンス

*GameMaker Studio 2* にはさまざまなライセンスが用意されています。単にゲーム制作を楽しみたいのか、あるいはゲームを販売・配布したいのか、またはターゲットとなるユーザー層によっても、あなたが選ぶべきライセンスは大きく異なってきます。次に、各ライセンスの詳細を示します。

<details>
<summary>Trial</summary>

<p>YoYo アカウントに登録すると、<i>GameMaker Studio 2</i> を30日間起動できる無料の Trial ライセンスが付与されます。ここから必要に応じてさまざまなアップグレードを購入できます。Trial ライセンスでは、<i>GameMaker Studio 2</i> の提供するほとんどの体験に加え、<b>macOS</b> または <b>Windows</b> PC で実行することができるかわりに、30日間の試用期限が定められています。30日が経過してからも引き続き製品を使用するには、いずれかの有料ライセンスへアップグレードする必要があります。Trial ライセンスには次の制限があることに注意してください:</p>

<ul class="mx-8">
<li>確認メールを通して YoYo アカウントへアクティベートした日から30日間のみ GMS2 にアクセスできます。</li>

<li>各ターゲット プラットフォームの実行ファイルをコンパイルすることはできません。</li>

<li>よりパフォーマンスに優れる "YYC" ターゲットへのエクスポートをテストすることはできません。</li>

<li>Trial ライセンスの試用期限が迫っていることを示す IDE 通知をオフにすることはできません (環境設定から通知をオフにすることで、それ以外の通知を無効化することは可能です).</li>

<li>Marketplace パブリッシャー アカウントを作成することはできません (YoYo アカウントを使用して Marketplace から無料または有料のアセットを購入することは可能です).</li>
</ul>
</details>

<details>
<summary>Creator</summary>

<p><i>GameMaker Studio 2</i> の <b>Creator</b> バージョンでは、Trial ライセンス (上記参照) の30日間の制限が撤廃され、<b>macOS</b> か <b>Windows</b> のどちらかのプラットフォームへ向けてゲームをエクスポートすることができます。利用可能なターゲット プラットフォームは購入した IDE (<i>Creator for macOS</i> または <i>Creator for Windows</i>) によって異なり、VM (ランナー + インタープリター コード) を使用してゲームを実行およびエクスポートします。セットアップに関する詳細は、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> または <a href="http://help.yoyogames.com/hc/en-us/sections/207157668" target="_blank" rel="noopener">デスクトップ ターゲット</a> のセクションを参照してください。Creator ライセンスには、次の2つの制限があることに注意してください:</p>

<ul class="mx-8">
<li>ゲーム読み込み時のスプラッシュ スクリーンをデフォルトから変更することはできません。</li>

<li>より高性能な "YYC" ターゲットへ向けてプロジェクトをビルドすることはできません。</li>
</ul>
</details>

<details>
<summary>Desktop</summary>
<p><i>GameMaker Studio 2</i> の <b>Desktop</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを次のデスクトップ ターゲットへコンパイルできます:</p>

<ul class="mx-8">
<li><span translate="no">Windows</span>
</li>

<li>macOS</li>

<li>Ubuntu</li>
</ul>

<p>いずれのターゲットにも2つのコンパイル オプションが用意されています。1つめはランナーとインタープリター コードを使用する <b>VM</b> で、もうひとつはネイティブコードとコンパイル済みの実行ファイルを作成する <b>YYC</b> (YoYo Compiler) です。YYC オプションでは追加の設定が必要になることに注意してください。詳細については、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> のセクションまたは <a href="http://help.yoyogames.com/hc/en-us/sections/207157668"target="_blank" rel="noopener">デスクトップ ターゲット</a> のヘルプを参照してください。</p>
</details>

<details>
<summary>Web</summary>

<p><i>GameMaker Studio 2</i> の <b>Web</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを <b>HTML5</b> ターゲットへコンパイルできます。ゲームは JavaScript を使用してコンパイルされます。詳細については、YoYo Games ヘルプを参照してください: <a href="https://help.yoyogames.com/hc/en-us/articles/115000992307" target="_blank" rel="noopener">Web 用のセットアップ (HTML5)</a></p>
</details>

<details>
<summary>Amazon Fire</summary>

<p><i>GameMaker Studio 2</i> の <b>Amazon Fire</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを <b>Amazon Fire</b> ターゲットへコンパイルできます。ゲームは <i>Android</i> SDK を使用してコンパイルされ、<b>VM</b> (インタープリターつきのランナー) または <b>YYC</b> (ネイティブコードを生成する YoYo Compiler) のいずれかを使用してコンパイルできます。セットアップに関する詳細は、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> セクションまたは<a href="https://help.yoyogames.com/hc/en-us/sections/115000381071" target="_blank" rel="noopener">Amazon Fire</a> ライセンスのヘルプを参照してください。</p>
</details>

<details>
<summary>Mobile</summary>

<p><i>GameMaker Studio 2</i> の <b>Mobile</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを次のターゲットへコンパイルできます:</p>

<ul class="mx-8">
<li>Android</li>

<li>Amazon Fire</li>

<li>iOS</li>

<li>tvOS</li>
</ul>

<p>いずれのターゲットにも2つのコンパイル オプションが用意されています。1つめはランナーとインタープリター コードを使用する <b>VM</b> で、もうひとつはネイティブコードとコンパイル済みの実行ファイルを作成する <b>YYC</b> (YoYo Compiler) です。YYC オプションでは追加の設定が必要になることに注意してください。セットアップに関する詳細は、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> のセクションまたは <a href="https://help.yoyogames.com/hc/en-us/sections/115000300567" target="_blank" rel="noopener">モバイル ターゲット</a>のヘルプを参照してください。</p>
</details>

<details>
<summary>UWP</summary>

<p><i>GameMaker Studio 2</i> の <b>UWP</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを UWP 準拠の実行ファイルとしてコンパイルできます。実行ファイルは、次の3つの UWP プラットフォームのいずれかで実行できるように構成できます:</p>

<ul class="mx-8">
<li>Windows 10 デスクトップ版</li>

<li>Windows 10 Mobile</li>

<li>Xbox One</li>
</ul>

<p>UWP ターゲットにはそれぞれ2つのコンパイル オプションが用意されています。1つめはランナーとインタープリター コードを使用する <b>VM</b> で、もうひとつはネイティブコードとコンパイル済みの実行ファイルを作成する <b>YYC</b> (YoYo Compiler) です。YYC オプションでは追加の設定が必要になることに注意してください。セットアップに関する詳細は、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> のセクションまたは <a href="https://help.yoyogames.com/hc/en-us/sections/115000309028" target="_blank" rel="noopener">UWP ターゲット</a>のヘルプを参照してください。</p>
</details>

<details>
<summary>Console</summary>

<p><i>GameMaker Studio 2</i> の <b>Consoles</b> バージョンでは、Trial ライセンス (上記参照) のすべての制限が撤廃され、プロジェクトを次のターゲット プラットフォームへコンパイルできます</p>

<ul class="mx-8">
<li>Xbox One</li>

<li>PlayStation 4</li>

<li>Nintendo Switch</li>
</ul>

<p>いずれのコンシューマー ターゲットにも2つのコンパイル オプションが用意されています。1つめはランナーとインタープリター コードを使用する <b>VM</b> で、もうひとつはネイティブコードとコンパイル済みの実行ファイルを作成する <b>YYC</b> (YoYo Compiler) です。YYC オプションでは追加の設定が必要になることに注意してください。セットアップに関する詳細は、<a href="{{ site.baseurl }}/docs/1_overview/5_required_sdks.md">必要な SDK</a> のセクションを参照してください。</p>

<p class="mx-8">
<b>重要！</b> コンシューマーへのエクスポートに関連するさまざまな NDA (秘密保持契約) の制限により、これらのターゲットのセットアップまたはプログラミングについての情報は、この <i>GameMaker Studio 2</i> マニュアル内に存在しません。選択したプラットフォームのデベロッパーとして登録を終えたら、適切なドキュメントへアクセスできるよう <a href="https://account.yoyogames.com/report-bug" target="_blank" rel="noopener">YoYo アカウント</a>を通してヘルプデスクへ連絡してください。
</p>
</details>

<details>
<summary>Education</summary>

<p><i>GameMaker Studio 2</i> は、大学のような環境でも使用できます。詳細については、<a href="https://www.yoyogames.com/education" target="_blank" rel="noopener">YoYo Games 教育向けポータル</a>から YoYo Games へお問い合わせください。</p>
</details>

<br>

**重要!** もしあなたが *GameMaker Studio 2* の Trial ライセンスを試用していて、ほかのライセンス (Creator、Desktop、Amazon Fire、Mobile、UWP、Web または Console) のいずれかを購入した場合は、**一度 IDE からログアウトして、*GameMaker Studio 2* を再起動する必要があります**。プログラムを再起動して再度ログインすると、新しいライセンスが正常に適用されます。ログアウトは [ファイル メニュー]({{ site.baseurl }}/docs/2_quick_start/menus/file_menu.md) から行えます。
{: .fs-3 .mx-8}
