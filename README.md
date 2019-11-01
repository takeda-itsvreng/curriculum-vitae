# 業務経歴書

## 基本情報

| key | value |
----|----
| HN | たけだ |
| 住所 | ミャンマーのヤンゴン |
| 資格 | 基本情報、応用情報 |
| 英語力 | TOEIC 685点 (2019/3) |
| ブログ | https://takeda-itsvreng.com/ |
| Twitter | https://twitter.com/takeda_itsvreng |
| Facebook | https://web.facebook.com/hiroki.takeda.9216 |

## 現在の転職希望度

ミャンマーに来て一か月ほど経ちましたが、半年のプロジェクト契約更新のタイミングでやめようかなと、すでに思っています。  
主に銀行系のシステム構築プロジェクトなのですが、言語が英語なだけで日本とあまり変わらない厳しさだなと。  
どうせ厳しくてそこまでリターンも無いのなら、国際協力系のプロジェクトを探した方が有意義かなと。

そのため特に国際協力系でなくてもいいのですが、何か私でお力になれそうなことがありましたら、TwitterのDMなどでお気軽にご連絡ください。

## 概要

- 2007年度入社のSIerよりスキルセットのインフラエンジニアです。ただネットワーク機器はほとんど触ったことがないため、サーバエンジニアと呼ばれるものかもしれません。

- 基本参画させていただいたプロジェクトで必要なことをやっていくスタイルです。いちおう10年以上やっているため大体のことはできますが、このスタイルかつ固いプロジェクトが多いためパブリッククラウドやコンテナといった技術はチュートリアル程度です。

- 上述のスタイルおよび全体を見る目があるのか、プロジェクト全体の緊急度を考慮して以下のような対応を自ら実施するため、参画したほとんど(1件だけ志半ばで離任)のプロジェクトで評価していただいています(はずです)。
  - リーダがまわっていなかったため、ベンダから受領した設計書のレビュー担当範囲を細分化し、各担当者に振り分け・取りまとめ
  - みんなが消極的になっている障害に、よくわからないけどとりあえず首を突っ込み自分にできることはないかを探す

- リーダタイプではないため、何歳までいけるかわかりませんが、いちエンジニアとしてやっていきたいと考えています。なお上述のことからリーダのサポートは得意です。

- 最近興味があるのはインフラ構築・テスト・運用の自動化です。正直、みんなの自動化ナレッジをインターネットで共有していけば、かなりの数のインフラエンジニアが不要になると感じています。不毛な作業で無理やり雇用を生むよりは、自動化やAIで淘汰されていく方が個人的には賛成です。たとえ自分が淘汰されようが。。。

## 業務経歴

以下は全てSESのような契約で参画しています。  
これは。。。書ききれない。。。

#### ミャンマーのSIer(日本の会社とミャンマーの会社の合弁会社) 2019/10 ～

現在、技術アドバイザーのような立ち位置で参画中。

---

#### 放送局グループ会社(ユーザ企業のようなもの) 2016/05 ～ 2019/09

<details>
<summary>この会社での各プロジェクトで関わった製品(折りたたみ)</summary>
<pre>
<code>
OS
 - RHEL7系
 - WindowsServer 2012R2/2016
仮想化
 - ESXi 6.0/6.5/6.7
 - vCSA 6.0/6.5/6.7
DBMS
 - Oracle 12c
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
 - AppHA
Windows管理
 - ActiveDirectory
 - WSUS
その他
 - Bash shell
 - Powershell
 - VMware PowerCLI
 - ansible
 - AWX
 - gitlab
 - Serverspec
 - molecule
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

- 地方局システム更改
  - 時期：2018/07 ～ 2018/12
  - 役割：メンバ
  - 業務内容：各地方局のシステムを同じようなHW・SWを用いて更改していく
  - 特記事項：
    - 東京にてオンプレである程度まで構築し、現地まで持っていって設置・最終調整を、各局で実施していく
    - 現地ではお客様が使用するPC端末のキッティングや設置のようなことも実施
    - 私が担当したのは3局ぐらいで、そのうち現地まで行ったのは1局
    - 各局の中にも本社と支社があり、本社と支社間でNW回線の遅い曲があったため、以下のような帯域制御を実施

---

#### SIer 4 2015/09 ～ 2016/04

---

#### SIer 3(SIer 4と同じ会社だが事業部が少し違う) 2014/10 ～ 2015/08

---

#### SIer 1(いわゆる出戻り) 2013/07 ～ 2014/09

---

#### SIer 2 2013/01 ～ 2013/6

---

#### SIer 1 2007/08 ～ 2012/12

