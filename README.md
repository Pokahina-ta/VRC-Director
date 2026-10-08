# VRC Director

VRChatのカメラ撮影とOBS録画を操作するWindowsアプリです。

[最新版をダウンロード](https://github.com/Pokahina-ta/VRC-Director/releases/latest)

## 機能

- カメラの画角保存・呼び出しとルート撮影
- OBSの録画開始・停止、自動再接続
- VR録画パネル
- Unityから取り込んだエクスプレッションメニューの操作

## プロジェクトの分離

従来の統合版から撮影機能を分離し、VRC Director 1.0として再スタートしました。

## はじめかた

Windows ZIPをすべて展開し、VRC-Director.exeを起動してください。
撮影ギミックを使用する場合はDirector.unitypackageをUnityへ取り込み、Modular Avatarを導入したアバターへDirectorのPrefabを配置してください。
エクスプレッションメニューの取り込みだけを使用する場合は、Director-Expression-Import-Only.unitypackageを選べます。
OBSの録画にはOBS側のWebSocketサーバー設定が必要です。

## 更新方法

Windows ZIPをすべて展開し、これまでと同じアプリフォルダーへ上書きしてください。
旧統合版でFakeVRを準備している場合は、旧版の「通常のSteamVRに戻す」を実行してから更新してください。
カメラ版の設定は専用の保存先へ移行します。従来の標準保存先にある撮影設定・OBS接続情報・取り込んだメニューは初回起動時にコピーされます。

同梱ライブラリのライセンスは配布ZIP内のlicensesフォルダーに収録しています。
