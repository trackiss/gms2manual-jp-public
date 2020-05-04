---
layout: default
title: エラーの報告
nav_order: 9
parent: セットアップ
---

## エラーの報告

*GameMaker Studio 2* は、安定して信頼性の高いツールになるよう細心の注意をはらって制作されていますが、ソフトウェアである以上は、実行する OS によって問題が生じる可能性があります。ほとんどのエラーは *GameMaker Studio 2* によって検出され、プロジェクトを保存したのちプログラムを閉じて再起動するように求められます。その場合は、YoYo Games のヘルプデスクへバグを報告してください。[ヘルプ メニュー]({{ site.baseurl }}/docs/1_overview/2_quick_start/menus/help_menu.md) の **バグを報告する** オプションからバグを報告することができます。このとき、なるべく多くの情報を解析できるように、*GameMaker Studio 2* の <tt>ui.log</tt> ファイルへのリンクを提供してください。このファイルは、OS に応じて次の場所へ配置されています:

<ul class="mx-8">
<li><b>Windows</b> の場合 - <tt>C:\ProgramData\GameMakerStudio2</tt></li>

<li><b>macOS</b> の場合 - <tt>/Users/Shared/GameMakerStudio2/</tt>
(Macintosh HD &gt; Users &gt; Shared &gt; GameMakerStudio2)</li>
</ul>

ごくまれに、エラーが非常に深刻なものであった場合、上記の警告を出さずにクラッシュしてしまうことがあります。このとき、次のウィンドウが表示されます:  
![クラッシュ レポート ウィンドウ]({{ site.baseurl }}/assets/images/demo-large.png){: .center}

このウィンドウには *GameMaker Studio 2* によってコンパイルされたクラッシュ レポートの一部が表示されます。YoYo Games へ送信された情報から何が起こったのかを調べ、可能であれば将来のアップデートで問題を修正します。送信されているデータについてもっとよく知りたい場合は、YoYo Games ヘルプデスクの [この記事](https://help.yoyogames.com/hc/en-us/articles/360028120992){: target="_blank" rel="noopener"} を参照してください。
