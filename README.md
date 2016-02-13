jQueryGantt for Kintone
===========

Roberto Bicchierai と Silvia Chelazzi作った<a href="https://github.com/robicch/jQueryGantt"> jQueryGantt</a>をKintoneに導入しました。

このプロジェクトのJSとCSSをKintoneに配置すれば以下のようなGanttChartを利用できます。

<img src="https://cloud.githubusercontent.com/assets/13725634/13010367/d926b282-d1e4-11e5-87c9-0e38dc567e14.png" alt="Kintone1" border="0" />

<img src="https://cloud.githubusercontent.com/assets/13725634/13010381/e6924bfc-d1e4-11e5-9393-b1334245cc1f.png" alt="Kintone2" border="0" />

オリジナル版以下の特徴を持っています:
* jquery based
* MIT licensed: you can reuse everywhere
* json import-export
* internationalizable
* manage task status –> project workflow
* manage dependecies
* manage assignements (resources, roles efforts)
* server synchronization ready
* full undo-redo support
* cross browser (at least for recent versions)
* keyboard editing support
* SVG visual editor
* print friendly
* collapsible branches

Kintone版は以下のように最適化した
* 日付をローカルライズ
* ステータスに緊急（Emergency）を追加
* Kintoneにデータ保存
* ImageをInline化
