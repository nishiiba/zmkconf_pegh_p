# Peghammer – ZMKカスタムファームウェア

このディレクトリには、Bluetooth対応左手デバイス「Peghammer」用のZMKファームウェア設定ファイルとカスタムファイルが含まれています。

## DYA Studioへの対応について

本ファームウェアは、USB接続およびBluetooth（BLE）接続経由でのリアルタイムなキーマップ書き換えアプリ **DYA Studio** に対応しています。

### 接続・使用方法
1. Google ChromeやMicrosoft Edgeなど、Web Bluetooth APIに対応したブラウザでDYA Studioを開きます。
2. DYA Studio画面上の **Connect（接続）** ボタンを押し、デバイスを選択してペアリングを行ってください。

※Bluetooth接続時は、BLEの通信帯域制限によりデバイス情報の読み取り（同期）に数十秒ほどの時間がかかりますが  
これは仕様による正常な動作です。

---

## 帰属表示とライセンス

このディレクトリにあるZMKの設定ファイルは、主にsekigon-gonnoc氏が管理するコード  
およびcormoran氏が開発したDYA Studio対応モジュールを基に作成されています。
オリジナルのコードベースとサンプルを提供してくださった開発者の方々に感謝いたします。

### ソースリポジトリのフォークおよび参考元:
* https://github.com/sekigon-gonnoc/zmk-bmp-boost-sample
* https://github.com/cormoran

### ライセンス

このディレクトリの内容はMITライセンスに基づいてライセンスされています｡  
このライセンスはこのディレクトリに含まれるZMK設定ファイルとカスタムファイルにのみ適用されます。  
このリポジトリ内のその他のファームウェア実装やハードウェア設計は、別途ライセンスされています。  
ライセンス全文については、LICENSE ファイルを参照してください。

### サードパーティ製ソフトウェアおよびライセンス

このファームウェア構成は、以下のサードパーティ製プロジェクトに依存しています。
* ZMK Firmware – MIT License (Copyright (c) 2020 Pete Johanson)
* Zephyr RTOS – Apache License 2.0
* sekigon-gonnoc/zmk-component-bmp-boost – MIT License
* DYA Studio modules – MIT License (Copyright (c) 2024 cormoran)

これらの依存関係にあるすべてのライセンス条項を遵守します。

### 免責事項

このファームウェア構成は、いかなる保証もなく「現状のまま」提供されます。
