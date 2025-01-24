# RKD01 v1.0

## 概要

Choc v1の分割キーボード

## 発注内容

ファイル|内容|PCB幅
:--|:--|:--
AZFoot.zip|az1uball搭載用板|1.2 -- 1.6mm
Assemble\_L.zip|左手基板(GNDが細いので再設計が必要)|1.6mm
Assemble\_L\_BOM\_JLCSMT.csv|左手用BOM|-
Assemble\_L\_JLCSMT\_CPL1.csv|左手用CPL|-
Assemble\_R\_SP.zip|右手基板|1.6mm
Assemble\_R\_SP\_BOM\_JLCSMT.csv|右手用BOM|-
Assemble\_R\_SP\_JLCSMT\_CPL1.csv|右手用CPL|-
Bottom.zip|ボトムプレート 左右兼用|0.8 -- 1.6mm
Guard.zip|マイコンガード 左右兼用|0.8--1.6m
Top\_L.zip|左手トッププレート|**1.2mm**
Top\_R.zip|右手トッププレート|**1.2mm**

## 注意点

* 配線に問題があるのか、AZ1UBALLを壊した
* トッププレートは1.2mm chocのプレートマウントスタビライザを使用するため
* ChocV2を使いたかったが、以下誤りがあるためChocV1でしか使えない
  * スタビライザーがChocV1専用
  * スイッチステム幅が狭い(ChocV2が刺さらない)
