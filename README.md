# yomiage

画面の文字を読み取り、VOICEVOX の声で読み上げる Windows 用のフリーのアプリです。

[リリース](https://github.com/tarou-imokenpi/yomiage-releases/releases/latest) から `yomiage-setup-<版>.exe` をダウンロードして実行してください。

## ライセンス

yomiage は [CC BY-NC-SA 4.0](LICENSE)（表示・非営利・継承）で公開しています。**営利目的では使えません。**

### アプリに同梱しているもの

| もの | 使いみち | ライセンス |
|---|---|---|
| [YomiToku](https://github.com/kotaro-kinoshita/yomitoku) の文字検出・文字認識モデル（作者: Kotaro Kinoshita） | 文字の読み取り（OCR） | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.ja)（非営利のみ） |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) | OCR の推論 | MIT License |
| [DirectML](https://www.nuget.org/packages/Microsoft.AI.DirectML) | GPU で OCR を動かす | Microsoft のライセンス |
| [lindera](https://github.com/lindera/lindera) と IPADIC | ふりがなの読み | MIT License / IPADIC のライセンス |
| [DotGothic16](https://fonts.google.com/specimen/DotGothic16) | ドット文字の訳文の書体 | SIL Open Font License 1.1 |
| [M PLUS Rounded 1c](https://fonts.google.com/specimen/M+PLUS+Rounded+1c) | アイコンの文字 | SIL Open Font License 1.1 |
| gpui ほか Rust のライブラリ | アプリ本体 | MIT / Apache-2.0 など |

### はじめて使うときに、利用規約に同意してダウンロードするもの

| もの | 使いみち | ライセンス |
|---|---|---|
| [VOICEVOX CORE](https://github.com/VOICEVOX/voicevox_core) | 読み上げ | MIT License |
| [VOICEVOX 音声モデル](https://github.com/VOICEVOX/voicevox_vvm) | 読み上げの声 | VOICEVOX 音声モデル 利用規約と、各キャラクターの利用規約 |
| [VOICEVOX 版 ONNX Runtime](https://github.com/VOICEVOX/onnxruntime-builder) | 読み上げ | VOICEVOX ONNX Runtime 利用規約 |
| [Open JTalk 辞書](https://github.com/r9y9/open_jtalk) | 読み上げ | Modified BSD License |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | ほんやく | MIT License |
| [PLaMo 3 Translate](https://huggingface.co/pfnet/plamo-3-translate-0.8b)（株式会社 Preferred Networks） | ほんやく | PLaMo Community License（Built with PLaMo） |

### 読み上げた音声を公開するとき

動画や配信などで使うときは、「VOICEVOX:ずんだもん」のように **「VOICEVOX:キャラ名」のクレジット表記** が必要です。キャラクターごとの利用規約も確認してください（[VOICEVOX](https://voicevox.hiroshiba.jp/)）。

各ライセンスの全文は、インストールしたフォルダの `licenses` と、アプリの「ライセンス」にあります。
