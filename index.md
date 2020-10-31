---
layout: default
---

**Niconama comment viewer** alternative for **Mac OS X**.

<a href="https://twitter.com/share" class="twitter-share-button" data-text="Hakumai - Mac用ニコ生コメントビューア">Tweet</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>

<a href="https://hakumai.s3.amazonaws.com/Hakumai.{{site.binary_version}}.zip" class="button button-primary"><i class="fa fa-download"></i> Download</a>
v{{site.binary_version}}, {{site.binary_date}} (for Mac OS X 10.10-)

## About Hakumai

<img src="./image/main.png" width="550px">

* Hakumai は Mac OS X で動作するニコニコ生放送用のコメントビューア(コメビュ)です。
    * 自分が使えればいい程度に作っているので、いろいろ手抜きです。
    * 今後予告なく後方互換性のないバージョンアップがされる可能性があります。

## Main Features

* Chrome と Safari の Session クッキー共有に対応
* アリーナから立ち見まで1ウィンドウ内に表示
* ユーザー生放送、チャンネル放送の両方に対応
* コテハンの自動登録機能
* ユーザーIDおよび単語ベースのコメント Mute 機能
<!-- * 棒読み対応 (<a href="http://www.yukkuroid.com/" target="_blank">ゆっくろいど</a>連携) -->

## System Requirements

* Mac OS X 10.10 (Yosemite) 以降に対応

## How to Completely Uninstall Hakumai

~~~
rm /path/to/Hakumai.app
rm ~/Library/Preferences/com.honishi.Hakumai.plist
rm -r ~/Library/Application\ Support/com.honishi.Hakumai/
Keychain Accessで"com.honishi.Hakumai.account"のエントリを削除(あれば)
~~~

<!--
## App Also Available

* Mac 用ニコ生アラート Ankoku Alert [<a href="https://itunes.apple.com/jp/app/ankoku-alert/id447599289" target="_blank">AppStore</a>] [<a href="https://github.com/honishi/AnkokuAlert" target="_blank">github</a>]
-->

## Special Thanks To

* 飯塚健一郎, らみあ, 田口潤, 森一真
* ジャスティス名川, 係長, 松原理央, 진
* 中嶋勇樹, 伊藤僚貴, 大原直人, 桜ほたる
* とろみ, ヘクトパスカル山田, うんさい
* Daijiro Wachi, econa77, macneko-ayu

## Contacts

* <a href="http://twitter.com/d3d7x" target="_blank">@d3d7x</a> (aka <a href="http://twitter.com/honishi" target="_blank">@honishi</a>)

<div class="github-fork-ribbon-wrapper right fixed" style="width: 150px;height: 150px;position: fixed;overflow: hidden;top: 0;z-index: 9999;pointer-events: none;right: 0;"><div class="github-fork-ribbon" style="position: absolute;padding: 2px 0;background-color: #333;background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.15));-webkit-box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0.5);-moz-box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0.5);box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0.5);z-index: 9999;pointer-events: auto;top: 42px;right: -43px;-webkit-transform: rotate(45deg);-moz-transform: rotate(45deg);-ms-transform: rotate(45deg);-o-transform: rotate(45deg);transform: rotate(45deg);"><a href="https://github.com/honishi/Hakumai" style="font: 700 13px &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif;color: #fff;text-decoration: none;text-shadow: 0 -1px rgba(0, 0, 0, 0.5);text-align: center;width: 200px;line-height: 20px;display: inline-block;padding: 2px 0;border-width: 1px 0;border-style: dotted;border-color: rgba(255, 255, 255, 0.7);" target="_blank">Fork me on GitHub</a></div></div>
