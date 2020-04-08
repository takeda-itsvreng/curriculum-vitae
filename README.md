# 業務経歴書

簡易版は[こちら](https://github.com/takeda-itsvreng/curriculum-vitae/blob/master/cv-jp-simplified.md)  
In English, Click [here](https://github.com/takeda-itsvreng/curriculum-vitae/blob/master/cv-en.md)

**最終更新日：2020/04/08**

## 基本情報

| key | value |
----|----
| HN | たけだ |
| 住所 | 東京 |
| 職業 | フリーランスITインフラエンジニア |
| 資格 | 基本情報、応用情報 |
| 英語力 | TOEIC 685点 (2019/3) |
| ブログ | https://takeda-itsvreng.com/ |
| Twitter | https://twitter.com/takeda_itsvreng |
| Facebook | https://web.facebook.com/hiroki.takeda.9216 |

## 現在の状況

週5の客先常駐で案件に参画しています。  
案件を変える気は今のところありません。

空いている時間でお手伝いできるようなことがあれば、ご相談いただけると幸いです。

## 概要

- 2007年度入社のSIerよりスキルセットのインフラエンジニアです。ただネットワーク機器はほとんど触ったことがないため、サーバエンジニアと呼ばれるものかもしれません。

- 基本参画させていただいたプロジェクトで必要なことをやっていくスタイルです。いちおう10年以上やっているため大体のことはできますが、このスタイルかつ固いプロジェクトが多いためパブリッククラウドやコンテナといった技術はチュートリアル程度です。

- 何ができるのかと聞かれると最近よくわからなくなってきましたが、箇条書きにしてみると以下の通りです。
  - できること
    - ハイパーバイザやOS、ミドルウェアの設計・構築・テストを、マニュアルを参照およびサポートへの問い合わせを利用して完了させる
    - 非機能要件(高可用・バックアップリストア・監視・運用・BCPなど)をシステム全体のレベルで把握・実装する
    - システムの保守・運用でインフラ関連の障害が発生した際の対応(サポートへの問い合わせ、根本原因調査・対処、ほぼミスのない作業)
    - 他者との認識を合わせるためのコミュニケーション(ただしこれは優秀な人との場合はほぼ問題ないが、そうでない人との場合は失敗する可能性あり)
    - 発展途上国に赴任し、現地の人と英語でコミュニケーションを取り、インフラ技術のアドバイスやドキュメントのレビューを行う
  - あまりできない or やったことがないこと
    - PMやPLのような自分が責任者となりメンバーを動かして成果を出す
    - アーキテクチャやソフトウェア選定レベルの設計・見積もり
    - 案件受注のための資料作成
    - ネットワークと業務アプリ関連のタスク

- リーダタイプではないため、何歳までいけるかわかりませんが、いちエンジニアとしてやっていきたいと考えています。全体を俯瞰してみる能力と自分で考えて行動する能力は一般的なエンジニアよりはあるかなと感じているため、リーダのサポートは得意だと考えます。

- 最近興味があるのはインフラ構築・テスト・運用の自動化です。正直、みんなの自動化ナレッジをインターネットで共有していけば、かなりの数のインフラエンジニアが不要になると感じています。不毛な作業で無理やり雇用を生むよりは、自動化やAIで淘汰されていく方が個人的には賛成です。たとえ自分が淘汰されようが。。。

## 業務経歴

以下は全てSESのような契約で参画しています。  

#### ミャンマーのSIer(日本の会社とミャンマーの会社との合弁会社) 2019/10 ～ 2020/03

日本人が2人、ミャンマー人が20人といった体制の会社。  
基本的にはミャンマー人と一緒に仕事。  
ミャンマー人とは英語で会話。

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
DBMS
 - Oracle Database 12.1/12.2
 - Oracle Enterprise Manager Cloud Control 13.3
FCスイッチ
 - Dell EMC PowerSwitch S4148U-ON
</code>
</pre>
</details>

- 各種銀行系システム対応
  - 時期：2019/10 ～ 2020/03
  - 役割：インフラ技術アドバイザ
  - 業務内容：複数のシステムに少しずつ関わっているため、主に実施した内容を記載
  - 特記事項：
    - Oracle DBとOEMCCのインストール・設定をメンバ主動で実施(Windows Server 2012R2上)
      - OEMCCは初だったが、マニュアルを見ながらテスト環境に実装し、それをメンバに伝達
      - ベンダの構築サポート費用を削減
    - Oracle DB障害対応をメンバ主動で実施(RHEL7上)
      - 調査と対応案検討と対応手順作成は実施したが、対応案決定と対応作業はメンバ主動で実施
      - ベンダの障害対応サポート費用を削減
    - 各種ドキュメントのレビューを実施
      - WBSやパラメータシート、手順書のレビューを実施
---

#### 放送局グループ会社(ユーザ企業のようなもの) 2016/05 ～ 2019/09

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - RHEL 7系
 - WindowsServer 2012R2/2016
仮想化
 - ESXi 6.0/6.5/6.7
 - vCSA 6.0/6.5/6.7
DBMS
 - Oracle Database 12c
 - EDB Postgres 10
Web/AP
 - Weblogic
 - Apache
 - Tomcat
監視
 - Zabbix 3/4
 - JP1 Base/IM/AJS/TELStaff
バックアップ
 - Netbackup
 - Veeam Backup & Replication
高可用
 - Symantec ApplicationHA
Windows管理
 - ActiveDirectory
 - WSUS
セキュリティ
 - SEPM
その他
 - Bash shell
 - Powershell
 - VMware PowerCLI
 - Ansible
 - AWX
 - GitLab
 - Serverspec
 - Molecule
</code>
</pre>
</details>

- 開発環境HW更新
  - 時期：2019/01 ～ 2019/07
  - 役割：メンバ
  - 業務内容：開発環境のHW保守期限にともない、HWをリプレースする
  - 特記事項：
    - 30台ぐらいの仮想サーバ(旧HWからの移行および新規構築)が対象
    - 移行時の開発チームとの調整はリーダにやってもらい、その他の実作業はほぼ一人で実施
    - 開発環境かつそこまで緊急ではなかったため、これまでのナレッジの組み合わせや新規作成による自動化構築を実施
    - 最終的にはAWXのワークフローでWeblogicを含んだAPサーバ5台を、ほぼ手放しで同時に新規構築し、かなりの快感を味わうことができた
    - また、Serverspecによるパラメータチェックテスト自動化の土台となるテストコードを作成した(Linuxはshellが使えるため何でもできるが、Windowsはコマンドで設定できないものがあり作成できない項目もあった)

- 地方局営放システム更改
  - 時期：2018/07 ～ 2018/12
  - 役割：メンバ
  - 業務内容：各地方局の営放システムを同じようなHW・SWを用いて更改していく
  - 特記事項：
    - 東京にてオンプレである程度まで構築し、現地まで持っていって設置・最終調整を、各局で実施していく
    - 構築・試験などを特に製品担当など無くまんべんなく実施
    - 現地ではお客様が使用するPC端末のキッティングや設置のようなことも実施
    - 私が担当したのは3局ぐらいで、そのうち現地まで行ったのは1局
    - 現地まで行った1局については、お客様担当者へのインフラ環境説明と質疑応答も実施
    - 各局の中にも本社と支社があり、本社と支社間でNW回線の遅い局があったため、以下のような帯域制御を実施(おそらくもう今後やることはないだろう。。。)
      - RHEL：tcコマンド
      - Windows：NetQoSとWindowsUpdateをBrancheCache分散モードでダウンロード

- ファイル伝送システム更改
  - 時期：2017/11 ～ 2019/07
  - 役割：メンバ
  - 業務内容：ファイル伝送システムのHW保守切れにともない、サーバを更改する
  - 特記事項：
    - 大きな変更はOracleからEDB Postgresへの移行ぐらい
    - サーバ種別は1台のみだが、WEB/JavaAP/DBが入っていた
    - 設計・構築・テストをほぼ一人で担当(相変わらず調整などはリーダに依頼)
    - 設計の基本方針は現行からの踏襲
    - EDB Postgresも現行のOracleと同じ動きとなるように設計
    - 本番稼働後はインフラ部分の保守・運用も他のプロジェクトと並行して担当(といってもこれといった障害は記憶になし)
    - ひとつ心残りがあるとすれば、DBのバックアップ方式があまりイケてない実装となってしまったこと
      - EDB PostgresはBARTというコンポーネントがあり、それを使うと増分バックアップができた
      - ただ検証にあまり時間が取れず、その当時英語のマニュアルしかなくて素早く理解もできなかったため、PostgreSQLのpg_basebackupで日次フル取得することに
      - ちなみに現行もRMANの日次フルであり、取得時間も同じぐらいであったため、リーダの承認は取れた
      - いちおう運用テストのフェーズでBARTの検証を終わらせて組み込んでみようと密かに考えていたが、ひとつ上の案件にアサインされたためそのまま本番稼働を迎えた

- キー局営放システム更改
  - 時期：2016/05 ～ 2019/07
  - 役割：メンバ
  - 業務内容：キー局営放システムのHW保守切れにともない、サーバを更改する
  - 特記事項：
    - 参画時にはすでに本番環境の構築は完了しており(本番稼働はまだ)、BCP環境構築の途中からであった
    - いち担当者として参画
    - BCP環境構築では以下のような作業を実施
      - 本番環境とレプリケーションさせるADサーバを構築
      - ベンダ作成ドキュメントレビュー(基本的な構築作業はベンダが実施)
      - BCP切替テストの実施
    - その後本番稼働まで以下のような作業を実施
      - DWHサーバ追加の設計・構築・テスト
      - JP1AJS運用ジョブ作成
      - Zabbix監視項目見直し
      - 障害通知設定見直し
      - 運用ツール・手順書作成
    - 本番稼働後はインフラ部分の保守・運用も他のプロジェクトと並行して担当

---

#### SIer 4 2015/09 ～ 2016/04

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - RHEL 6.6
 - WindowsServer 2012R2
仮想化
 - Oracle VM VirtualBox
DBMS
 - Oracle Database 12c
監視
 - JP1 Base/IM/AJS/SSO/NNMi
</code>
</pre>
</details>

- 電子債権システム更改
  - 時期：2015/09 ～ 2016/04
  - 役割：メンバ
  - 業務内容：電子債権システムのHW保守切れにともない、サーバを更改する
  - 特記事項：
    - 設計・構築・テストはベンダが担当するため、業務チームへの確認やレビューといったタスクをSIer側で担当
    - いち担当者として参画
    - 現行システムの定期保守作業も実施
    - 詳細設計書レビュー時の確認用にOracle VM VirtualBoxで上記の製品をインストール(インストールしたのみで、あまり利用されなかった記憶あり)
    - 詳細設計書レビュー後の指摘取り込み確認時に、リーダの手が回っておらず担当者が決まっていなかったため、取りまとめて担当者割り振りを実施
    - 現行のログメンテンナンス運用がブラックボックスとなっており、更改後は管理できるようにしたい要望があったため、ベンダと業務チームにヒアリングして一覧資料を作成
    - インフラの結合テストはSIer側担当であったため、SIerの会社に存在していた標準テスト観点、およびシステム全体図を統合して本システム用のテスト観点を作成し、テスト項目作成タスクの各担当者の割り振りを実施

---

#### SIer 3(SIer 4と同じ会社だが事業部が少し違う) 2014/10 ～ 2015/08

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - HP-UX 11i v3
 - RHEL
 - WindowsServer 2008R2
監視
 - JP1 AJS
 - OVO
</code>
</pre>
</details>

- インターネットバンキングシステム保守・運用
  - 時期：2014/10 ～ 2015/08
  - 役割：メンバ
  - 業務内容：インターネットバンキングシステムの保守・運用および機能追加に対応する
  - 特記事項：
    - いち担当者として参画
    - 機能追加にともなうインフラ作業を実施(JP1ジョブ作成、OVOテンプレート追加、スタティックルーティング追加、LVOL作成など)
    - 保守作業を実施(OSパッチ適用、リソース評価資料作成、ピーク日リソース状況監視など)
    - 障害対応を実施(電源モジュール交換、ディスク交換など)
    - 上記作業にともなう各種調整を実施(各業務グループとの作業調整、ハードウェアベンダへの調査依頼・交換作業調整など)

---

#### SIer 1(いわゆる出戻り) 2013/07 ～ 2014/09

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - HP-UX 11i v2
 - RHEL 5.5/5.9
DBMS
 - Oracle Database 11g
監視
 - NEC StorageSaver
 - JP1 AJS
高可用
 - HP Serviceguard
他システム通信
  - HULFT7
その他
 - Bash shell
 - MicroSoft Access
</code>
</pre>
</details>

- 証券会社バックシステム接続先システム更改
  - 役割：メンバ
  - 業務内容：対外システムが更改されるため、接続先などの各種設定を変更する
  - 特記事項：
    - ドキュメント作成：詳細設計書、作業手順書
    - 独自ミドルウェア設定：設定変更、外部システム疎通試験など
    - Serviceguard設定変更：仮想IPアドレス削除、クラスタ・パッケージ再構成など

- 証券会社バックシステム保守・運用
  - 役割：メンバ
  - 業務内容：システムの保守・運用作業を実施する
  - 特記事項：
    - 他のプロジェクトと並行して担当
    - ドキュメント作成：詳細設計書、作業手順書作成
    - OS構築：LVM論理ボリューム作成、Serviceguardロックディスク設定、StorageSaverリビジョンアップなど
    - ユーザからの問い合わせ対応

- 証券取引所システム更改(2システム)
  - 役割：メンバ
  - 業務内容：更改する2システムに対して運用部分の実装を行う
  - 特記事項：
    - ドキュメント作成：詳細設計書、作業手順書、テスト仕様書、障害時運用フロー、運用手順書
    - OracleDataPump検証用環境構築：OS設定、Oracle各種設定(接続識別子、ディレクトリオブジェクトなど)、Oracle各種オブジェクト作成(スキーマ、テーブル、シノニム、マテビュー、DBリンク、トリガー)など
    - 運用bashシェル作成・単体テスト：ミドルウェア(WLS、JP1/Base、JP1/AJS)起動停止、OracleDataPumpによる論理データバックアップ
    - ジョブ設計・構築：全インフラジョブ構築、起動条件付きジョブネット設計・構築
    - 障害時運用フロー作成：片系・全系障害、システムバックアップ戻しなど
    - 運用手順書作成：クラスタ(NEC CLUSTERPRO)状態確認

- 証券会社制度対応システム構築サポート
  - 役割：メンバ
  - 業務内容：ベンダとして顧客が実施する新規システム構築のサポートを行う
  - 特記事項：
    - ドキュメント作成：検討資料
    - HULFT接続先システムとの調整事項サポート：転送モード、文字コード変換、外字変換など
    - 障害時運用設計サポート：障害発生ポイント洗い出し、障害検討チーム整理など
    - ジョブフロー連携サポート：インフラとアプリのジョブフロー連携箇所洗い出しなど
    - MS Access検証作業：外部DB(Oracle)とのODBC接続によるテーブルリンク方法調査、フォーム・VBAなどの使用可能範囲調査

---

#### SIer 2 2013/01 ～ 2013/6

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - HP-UX 11i v3
 - RHEL 6.2
 - WindowsServer 2008R2
Windows管理
 - ActiveDirectory
</code>
</pre>
</details>

- 郵便システム更改
  - 時期：2013/01 ～ 2013/06
  - 役割：メンバ
  - 業務内容：システム更改を行う
  - 特記事項：
    - ドキュメント作成：基本設計書、詳細設計書、作業手順書
    - 検証環境構築：VMware仮想マシン作成、OSインストール・各種設定、ActiveDirectoryインストール・各種設定など
    - NASマウント設定(サーバ約100台)：NetAppチームとのマウントボリューム調整、OS設定など
    - ActiveDirectory基本設計：BINDチーム(既存ドメイン)との調整、基本方針検討など
    - ActiveDirectory詳細設計：各パラメータ洗い出し・設計など(途中で離任)
    - NASのNFSマウントとCIFSマウントの同時利用方法検討

---

#### SIer 1 2007/08 ～ 2012/12

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - HP-UX 11i v2/v3
 - RHEL 5.5
DBMS
 - Oracle Database 11g
Web/AP
 - Oracle WebLogic Server 9
 - Oracle Application Server 10g
他システム通信
 - WebSphere MQ 6/7
 - HULFT 6
その他
 - Bash shell
 - C Shell
 - C言語
 - NEC MCOne
</code>
</pre>
</details>

- 証券会社バックシステム更改
  - 役割：メンバ
  - 業務内容：既存システムの大幅機能追加のため、HWのスケールアップや各種設定変更を行う
  - 特記事項：
    - ドキュメント作成：設計書、作業手順書、テスト仕様書
    - OS構築：インストール、各種設定
    - MQ構築：キューマネージャ作成、MQオブジェクト(チャネル、キュー、リスナーなど)作成、設定ファイル修正、外部システム疎通試験
    - MCOne構築：インストール、設定ファイル修正
    - WLS構築：インストール、管理サーバ・管理対象サーバ作成、管理コンソールによる各種設定(Javaヒープ・パーマネントメモリサイズ、コネクションプール、スレッドプール、アプリケーションデプロイ、タイムアウトなど)
    - 運用モジュール作成：MQのAPIを使用したCのプログラミング、テスト

- 証券会社バックシステムBCP環境構築
  - 役割：メンバ
  - 業務内容：BCP環境を構築する
  - 特記事項：
    - ドキュメント作成：設計書、作業手順書
    - OS構築：インストール・各種設定
    - MQ構築：キューマネージャ作成、MQオブジェクト作成、設定ファイル修正
    - MCOne構築：インストール、設定ファイル修正

- 証券会社バックシステム決済照合システム組み込み
  - 役割：メンバ
  - 業務内容：既存システムに対外システムを組み込む
  - 特記事項：
    - ドキュメント作成：設計書、作業手順書
    - MQ構築：キューマネージャ作成、MQオブジェクト作成、設定ファイル修正、外部システム疎通試験

- 証券会社バックシステム新規接続先外部システム追加
  - 役割：メンバ
  - 業務内容：対外システムが新規追加されるため、接続するための各種設定を行う
  - 特記事項：
    - ドキュメント作成：設計書、作業手順書
    - MQ構築：MQオブジェクト作成、外部システム疎通試験
    - HULFT構築：管理画面からの各種設定(詳細ホスト情報、転送グループなど)

- 証券会社バックシステム保守・運用
  - 役割：メンバ
  - 業務内容：システムの保守・運用作業を実施する
  - 特記事項：
    - 他のプロジェクトと並行して担当
    - ユーザからの問い合わせ対応
    - サポートセンターへの問い合わせ対応
    - ドキュメント作成：設計書、作業手順書
    - 障害の恒久対応：OS個別パッチ適用、ミドルウェアバージョンアップ・設定変更
    - HW障害・交換時の対応：クラスタ・パッケージ・OS起動停止

- 証券会社日銀接続システム更改
  - 役割：メンバ
  - 業務内容：
  - 特記事項：システム更改を行う
    - ドキュメント作成：作業手順書、テスト仕様書
    - MQ構築：キューマネージャ作成、MQオブジェクト作成、設定ファイル修正
    - 運用シェル作成：Cシェル作成、単体テスト

- 証券会社財務会計システム更改
  - 役割：メンバ
  - 業務内容：システム更改を行う
  - 特記事項：
    - 検証環境構築：VMWareServerゲストOS作成、OSインストール・各種設定、OracleDBインストール・各種設定(リスナー、スキーマ、テーブル作成など)
    - ドキュメント作成：詳細設計書、作業手順書
    - OAS設計・構築：インストール、管理コンソールによる各種設定(Javaヒープ・パーマネントメモリサイズ、httpプロセスプール、コネクションプール、スレッドプール、タイムアウトなど)
