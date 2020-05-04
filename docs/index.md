---
layout: default
title: GameMaker Studio 2 マニュアル
nav_order: 2
---

## GameMaker Studio 2 マニュアル

*GameMaker Studio 2* ユーザー マニュアルへようこそ！ このドキュメントは3つのセクションに分かれています。まずは *GameMaker Studio 2* のインターフェースや基本的な操作方法について、その次により高度な使い方について、最後に、オリジナルの言語である [GML](#gml) と、ビジュアル スクリプティング ツールである [Drag and Drop](#dnd) で利用可能な機能について紹介していきます。また、簡単に操作ができるように、便利で手軽な [クイック スタート ガイド]({{ site.baseurl }}/docs/1_overview/2_quick_start/1_introduction/) を用意してあります。もしあなたがほかのゲーム制作ツールに精通している場合でも、このガイドを読んで *GameMaker Studio 2* の動作について理解しておくことをおすすめします。簡単で直感的に操作できる *GameMaker Studio 2* を使えば、あなたのスキルに関係なく、思うがままのゲームをすばやく作り上げることができるでしょう。

**注:** *GameMaker Studio 2* はモジュール化されており、なかにはこのユーザー マニュアルには記載されていない項目もあります。サポートされている各デバイスの設定やその接続方法については特に注意してください。さまざまなターゲット プラットフォームに関しての最新情報とトラブルシューティングのヒントについては、[YoYo Games Help Center](http://help.yoyogames.com/categories/20153017){: target="_blank" rel="noopener"} を参照してください。
{: .fs-3 .mx-8}

---

## 入門
{: name="getting_started" id="getting_started"}

このセクションは、*GameMaker Studio 2* のしくみを理解するための大切なファースト ステップです。*GameMaker Studio 2* は直感的かつシンプルな操作性なので、これまでにこういったツールを使った経験がない人でも、このセクションを読むことでゲーム制作をすんなりと始められることでしょう。基本的な部分を理解したあとは、次の [インターフェース](#interface) セクションで *GameMaker Studio 2* のコンポーネントについて詳しく見ていきます。

<details>
<summary>セットアップ</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/1_licences/"><span class="list_link"><i>GameMaker Studio 2</i> のバージョン</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/2_installation/"><span class="list_link">インストール</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/3_updating/"><span class="list_link">アップデート</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/4_release_notes/"><span class="list_link">リリース ノート</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/5_required_sdks/"><span class="list_link">必要な SDK</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/6_licensing/"><span class="list_link">ライセンス認証</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/7_preferences/"><span class="list_link">総合環境設定</span></a></li>

<li><a href="{{ site.baseurl }}docs/1_overview/1_getting_started/8_input/"><span class="list_link">IDE の入力</span></a></li>
</ol>
</details>

<details>
<summary>クイック スタート ガイド</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/1_introduction/"><span class="list_link">イントロダクション</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/2_start/"><span class="list_link">スタート ページ</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/3_workspaces/"><span class="list_link">ワークスペース</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/4_resources/"><span class="list_link">リソース</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/5_workflow/"><span class="list_link">ワークフロー</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/6_compiling/"><span class="list_link">コンパイル</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/7_debugging/"><span class="list_link">デバッグ</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/2_quick_start/8_shortcuts/"><span class="list_link">キーボード ショートカット</span></a>
</li>
</ol>
</details>

<details>
<summary>追加情報</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/file_system/"><span class="list_link">ファイル システム</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/using_buffers/"><span class="list_link">バッファーを使う</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/texture_pages/"><span class="list_link">テクスチャー ページ</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/importing_non_bitmap_sprites/"><span class="list_link">ビットマップ以外のスプライトをインポートする</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/command_line/"><span class="list_link">コマンド ライン パラメーター</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/bitwise_operators/"><span class="list_link">ビット演算子</span></a>
</li>

<li><a href=
"{{ site.baseurl }}docs/1_overview/3_additional_information/errors/"><span class=
"list_link">コンパイル エラー</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/jsdoc/"><span class="list_link">JSDoc スクリプト コメント</span></a>
</li>

<li><a href="{{ site.baseurl }}docs/1_overview/3_additional_information/obsolete_functions/"><span class="list_link">廃止された関数</span></a>
</li>
</ol>
</details>

---

<a name="interface" id="interface"></a>

## インターフェース

<i>GameMaker Studio 2</i> IDE (Integrated Development Environment、統合開発環境) を最大限活用するためには、数多く用意されている高度なオプションをうまく使いこなさなければなりません。これらのオプションには、ソース管理の統合、プロジェクト構成、高度なデバッグ、そしてゲーム アセットを変更および操作するためのさまざまなツールが含まれます (使用する <a href="{{ site.baseurl }}docs/1_overview/1_getting_started/1_licences/"><i>GameMaker Studio 2</i> のバージョン</a> によっては使用できるツールが異なる場合もありますので気をつけてください)。

<details>
<summary>エディター</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/sprites/"><span class=
"list_link">スプライト</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/images/"><span class=
"list_link">画像</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/tilesets/"><span class=
"list_link">タイルセット</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/sounds/"><span class=
"list_link">サウンド</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/paths/"><span class=
"list_link">パス</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/scripts/"><span class=
"list_link">スクリプト</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/shaders/"><span class=
"list_link">シェーダー</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/fonts/"><span class=
"list_link">フォント</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/timelines/"><span class=
"list_link">タイムライン</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/objects/"><span class=
"list_link">オブジェクト</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/rooms/"><span class=
"list_link">ルーム</span></a><br>
</li>

<li><a href=
"{{ site.baseurl }}docs/2_interface/1_editors/included_files/"><span class="list_link">
埋め込みファイル</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/extensions/"><span class=
"list_link">拡張機能</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/1_editors/notes/"><span class=
"list_link">メモ</span></a><br>
</li>
</ol>
</details>

<details>
<summary>その他</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/sound_mixer/"><span class=
"list_link">サウンド ミキサー</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/output/"><span class=
"list_link">出力ウィンドウ</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/device_manager/"><span class=
"list_link">デバイス マネージャー</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/remote_worker/"><span class=
"list_link">リモート ワーカー</span></a><br>
</li>

<li><a href=
"{{ site.baseurl }}docs/2_interface/2_extras/project_image_generator/"><span class=
"list_link">プロジェクト画像ジェネレーター</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/debugging/"><span class=
"list_link">デバッグ モジュール</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/source_control/"><span class=
"list_link">ソース管理</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/marketplace/"><span class=
"list_link">Marketplace</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/2_extras/recent_windows/"><span class=
"list_link">最近使用したウィンドウ</span></a><br>
</li>
</ol>
</details>

<details>
<summary>設定</summary>
<ol>
<li><a href="{{ site.baseurl }}docs/2_interface/3_settings/preferences/"><span class=
"list_link">プラットフォームの環境設定</span></a><br>
</li>

<li><a href=
"{{ site.baseurl }}docs/2_interface/3_settings/game_options/index/"><span class=
"list_link">ゲーム オプション</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/3_settings/textures/"><span class=
"list_link">テクスチャー グループ</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/2_interface/3_settings/audio/"><span class=
"list_link">オーディオ グループ</span></a><br>
</li>

<li><a href=
"{{ site.baseurl }}docs/2_interface/3_settings/configurations/"><span class=
"list_link">構成</span></a><br>
</li>
</ol>
</details>

---

<a name="scripting" id="scripting"></a>

## スクリプト

このセクションでは、*GameMaker Studio 2* でのプログラミングに使用するさまざまなスクリプト言語について説明します。プロジェクト作成に使用する言語や方法については、あなた自身のスキルや経験によって左右されます。そこで、なるべく多くのニーズに対応できるよう、*GameMaker Studio 2* では2つのオプションを提供しています:

<details>
<summary>Drag and Drop (DnD™)</summary>
Drag and Drop (DnD™) は、初心者の方であったり、より視覚的で芸術的な表現を好む人に最適です ("ビジュアルスクリプト言語" と呼ばれることもあります)。この方法では、<b>アクション</b> をオブジェクト エディターへドラッグ&ドロップすることで、オブジェクト インスタンスが実行していく関数の羅列を作ります。DnD™ の使い方については、以下のセクションを見てください:

<ol>
<li><a href=
"{{ site.baseurl }}docs/3_scripting_1_drag_and_drop_overview/index/"><span class=
"list_link">Drag and Drop の概要</span></a><br>
</li>

<li><a href=
"{{ site.baseurl }}docs/3_scripting_2_drag_and_drop_reference/index/"><span class=
"list_link">Drag and Drop リファレンス</span></a><br>
</li>
</ol>

</details>

<details>
<summary>GameMaker Language (GML)</summary>
ここでは、GameMaker Language のシンタックスの概要とその使用例、プログラムの構造、そして組み込みの GML 関数の完全なリファレンス ガイドを見ることができます。スクリプト言語をはじめて使用する場合は、まず GML の概要について学ぶことをおすすめします。それ以外の場合は、リファレンス ガイドを活用して必要な関数について調べてください:

<ol>
<li><a href="{{ site.baseurl }}docs/3_scripting_3_gml_overview/index/"><span class=
"list_link">GML の概要</span></a><br>
</li>

<li><a href="{{ site.baseurl }}docs/3_scripting_4_gml_reference/index/"><span class=
"list_link">GML リファレンス</span></a><br>
</li>
</ol>

</details>

<br>

GML と DnD™ は、まったく排他的な方法という訳ではなく、必要に応じて組み合わせて使用することができます。どちらを選ぶかは、あなたのスキルや経験によって決めましょう。
