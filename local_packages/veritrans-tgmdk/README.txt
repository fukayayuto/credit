################################################################################
# VeriTrans4G
# MDK for PHP 8
# Version 1.1.7
# Copyright(c) 2021 DG Financial Technology, Inc.
# README.txt
################################################################################

このMDKは、PHP 7.4以上、または8.0以上 の環境で動作可能なComposerパッケージです。

================================================================================
 改版履歴
================================================================================

2019/09 MDK for PHP 7 ver 1.1.1 リリース
2020/11 MDK for PHP 7 ver 1.1.2 リリース
2020/12 MDK for PHP 8 ver 1.1.3 リリース
2021/04 MDK for PHP 8 ver 1.1.4 リリース
2021/09 MDK for PHP 8 ver 1.1.5 リリース
2021/11 MDK for PHP 8 ver 1.1.6 リリース

2021/11 MDK for PHP 8 ver 1.1.7 リリース
    楽天ID決済：
      ・オンライン決済（V2）に対応
    Amazon Pay：
      ・加盟店の決済確認画面を利用するケースに対応
    スコア@払い：
      ・決済申込、決済情報修正の応答電文に以下の項目を追加
        ・加盟店注文ID（shopTransactionId）
    検索：
      ・Amazon Pay検索パラメータに以下の項目を追加
        ・決済確認画面種別（payConfirmScreenType）
      ・検索結果の決済オーダー情報に以下の項目を追加
        ・決済確認画面種別（payConfirmScreenType）

================================================================================
 動作環境について
================================================================================
弊社ホームページ、又はダウンロードサイトの動作確認済み環境を参照してください。


================================================================================
 MDKのファイル構成および使用方法について
================================================================================
別途提供している4G開発ガイド、インストールガイドを参照してください。


================================================================================
 依存Composerパッケージ一覧
================================================================================
psr/log          version:1.1.4          license:MIT


================================================================================
 MDKの導入サポートについて
================================================================================
MDKの導入および動作についてサポートを受ける場合は、
以下のメールアドレスにお問い合わせください。

 Mail : tech-support@veritrans.jp

但し、弊社動作確認済み環境以外の環境への導入、環境環境に依存する問題については、
サポートの対象外とさせていただく場合がありますのでご了承ください。
また、緊急時以外の電話対応は受け付けておりません。


・Copyright 2021 DG Financial Technology, Inc.


その他 MDK 内で使用されている名称や商品の名称はそれぞれ各社が
登録商標あるいは商標として使用している場合があります。
