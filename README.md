# Browser MCU Core

* Browser MCU Core is MCU library using a browser for video/audio processing
* Browser MCU Core is designed for MediaStreams from WebRTC
* Signaling and handling of PeerConnection are not a part of Browser_MCU Core
* Browser MCU Core is a part of Browse MCU Series
* Browser MCU Core はブラウザの映像/音声処理を活用した、MCUライブラリです
* Browser MCU Core は WebRTC でやり取りする MediaStream を扱うために作成されています
* シグナリングや PeerConnection の処理は、Browser MCU Core には含まれていません
* Browser MCU Core は Browse MCU シリーズの一部です

## Confirmed Environment / 動作確認環境

* Chrome  58.0.3029.110 (64-bit) for MacOS X
* Firefox (not yet)


## Samples / サンプル

### video mix sample

* view source on GitHub / ソースを見る
* try GitHub pages / GitHub pages で試す

#### How to use sample / サンプル操作手順

* Prepare
  * copy mix_sample.html, js/browser_mcu_core.js to your local web server
* Open http://localhost:your_port/your_path/mix_sample.html with Chrome/Firefox
* Click [Add Video] Button and allow access to Camera / Michrophone
* Click [Add Video] Button many times (up to 25)
* Then, videos are mixed

--

* 事前準備
  * ローカルマシンのWebサーバーに、mix_sample.html, js/browser_mcu_core.js を配置します
  * Chrome か Firefox 
* Chrome/Firefoxブラウザで http://localhost:あなたのポート/あなたのパス/mix_sample.html を開きます
* [Add Video]ボタンを押します。カメラ/マイクのアクセス許可を求められたら、許可してください
* [Add Video]ボタンを何度か押します。（最大25）
* 映像/音声が合成されます

## Usage / 利用方法

#### Prep

* Load browser_mcu_core.js in HTML

```
<script src="js/browser_mcu_core.js"></script>
```

#### Initialization / 初期化

#### Start Mix Video/Audio / 合成の開始
 
#### Stop  Mix Video/Audio / 合成の停止


### Code Samples / コード例

```
```

## License / ライセンス

* Browser MCU Core is under the MIT license
* Browser MCU Core はMITランセンスで提供されます



