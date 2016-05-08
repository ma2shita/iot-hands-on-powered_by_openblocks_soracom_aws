.. -*- coding: utf-8; -*-

=======================================================
IoTハンズオン Powered by OpenBlocks IoT | SORACOM | AWS
=======================================================

Auhtor: `Kohei MATSUSHITA <https://twitter.com/ma2shita>`_

概要
====

OpenBlocks IoT BX1 (以下 BX1) を使用し、富士通コンポーネント社製 温度・加速度センサーデバイス "FWM8BLZ02" のデータを "SORACOM Air" の回線で "AWS IoT" に送信し、Amazon Elasticsearch Service(以下 Amazon ES)上のKibanaでグラフ化するところまでを解説します

.. toctree::
   :hidden:
   :maxdepth: 2
   :numbered:

   00
   01
   02
   03
   04
   05
   06
   07
   08

:doc:`00` へ進む

時間配分
~~~~~~~~

#. [10m] 冒頭説明
#. [20m] BX1のWi-Fi AP設定とSORACOM Air(3Gネットワーク)設定
#. [20m] センサーとBX1の接続
#. [10m] Amazon ESのインスタンス作成と設定
#. [20m] AWS IoTの設定
#. [20m] BX1とAWS IoTの接続
#. [10m] 片付け＆まとめ

※冒頭説明から片付け＆まとめまで約120分のコンテンツです

- [20m] 自習室: SORACOM BeamでAWS IoTの認証処理をオフロード
- [20m] 自習室: Thing Shadowでパトライトを制御
