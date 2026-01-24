# skregexp (Fork for NanaTerry)

## 概要
このリポジトリは、Delphi用の正規表現ライブラリ [skregexp](https://github.com/shukomiya/skregexp) のフォークである。
オリジナルは長期間更新が停止しているため、テキストエディタ「NanaTerry」の開発継続に必要なバグ修正および機能維持を目的として、独自にメンテナンスを行っている。

## フォークの目的と位置づけ
本フォークは汎用的な利用を意図したものではなく、以下の特定の環境・目的のために運用されている。

*   **レガシー環境のサポート**: Delphi 2009 環境での動作を保証する（Delphi XE2以降の `System.RegularExpressions` が使用できない環境向け）。
*   **バグ修正**: オリジナル版に含まれる未修正の不具合への対応。
*   **AIペアプログラミング用**: コードベースの把握と修正履歴の明確化。

## 特徴
標準の正規表現ライブラリと比較し、本ライブラリには以下の利点があるため継続利用している。

*   **全角/半角の区別**: 日本語処理において重要な、全角文字と半角文字の厳密な区別が可能。
*   **軽量・高速**: Delphiネイティブ実装であり、外部DLLを必要としない。

## 免責事項
*   Delphi XE2 以降を使用している開発者には、標準ライブラリ `System.RegularExpressions` の使用を推奨する。
*   本リポジトリの変更内容は、NanaTerryの仕様に特化している可能性がある。

---
## Original Credits
Based on skregexp by shukomiya.
Original Readme: [README_ORIGINAL.txt](./README_ORIGINAL.txt)
