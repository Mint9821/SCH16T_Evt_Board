# SCH16T_Evt_Board

Murata製IMUであるSCH16Tシリーズの開発ボード

## システム構成図

## 1S LiPoバッテリの充電回路

## IMU周辺回路

## 回路図

## PCBレイアウト

## KiCadライブラリ
本開発ボードではKiCadの既存ライブラリに加えて、SCH16XXとESP32-C6-MINI-1-N4を使用しています。
KiCadファイルを編集する際は、各自でライブラリを適用してください。

### SCH16XX
自作です、じゆうにつかっていいよ(一応、MITライセンスに従います)。

>MIT License
>
>Copyright (c) [2024] [Mint9821]
>
>Permission is hereby granted, free of charge, to any person obtaining a copy
of this library and associated files, to deal in the library without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the library...


### ESP32-C6-MINI-1-N4
公開されているライブラリを使用。
KiCadの回路図およびPCBを開く際は下記URLからライブラリをダウンロードした後に適用してください。

>https://www.snapeda.com/parts/ESP32-C6-MINI-1-N4/Espressif%20Systems/view-part/

>このリポジトリには、SnapMagic Search, Inc. が提供するモデルを含んでいます。
モデルの使用にあたっては、[SnapMagic Model License](URL) に従ってください。
モデル単体での再配布は禁止されています。

### その他ライブラリ

>本設計はKiCad公式ライブラリを使用しています。
ライブラリはCC BY-SA 4.0のライセンスの下に配布されています。
https://creativecommons.org/licenses/by-sa/4.0/
