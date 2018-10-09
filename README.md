# ARKitBook

ARKitの実践入門書「[実践ARKit](https://shu223.booth.pm/items/1038241)」のサンプルコードです。

一部サンプルはモデルファイルのダウンロードが必要です。`mlmodels/readme.md` を参照してください。

## 書籍の概要

作りながら学ぶネイティブARKitアプリケーション開発の実践入門書です。はじめの一歩として3行で書ける最小実装のARから始めて、平面を検出する方法、その平面に仮想オブジェクトを設置する方法、そしてその仮想オブジェクトとインタラクションできるようにする方法・・・と、**読み進めるにつれて「作りながら」引き出しが増えていき**、最終的にはARKitを用いたメジャーや、空間に絵や文字を描くといった、ARKitならではのアプリケーションの実装ができるよう構成しています。

A5版、全92ページ。ARKit 2.0 (iOS 12), Xcode 10, Swift 4.2対応。

## 書籍の目次

第1章 入門編その1 - 最小実装で体験してみる

- 1.1 手順1:プロジェクトの準備
- 1.2 手順2:ViewControllerの実装
- 1.3 基本クラスの解説

第2章 入門編その2 - 水平面を検出する

- 2.1 水平面を検出するためのコンフィギュレーション
- 2.2 平面検出に関するイベントをフックする - ARSessionDelegate
- 2.3 平面検出に関するイベントをフックする - ARSCNViewDelegate
- 2.4 検出した平面を可視化する

第3章 入門編その3 - 検出した水平面に仮想オブジェクトを置く

- 3.1 3Dモデルを読み込む
- 3.2 仮想オブジェクトとして検出した平面に置く

第4章 ARKit 開発に必須の機能

- 4.1 トラッキング状態を監視する
- 4.2 デバッグオプションを利用する
- 4.3 トラッキング状態をリセットする / 検出済みアンカーを削除する

第5章 平面検出の基礎

- 5.1 垂直平面の検出
- 5.2 検出した平面のアラインメントを判別する
- 5.3 平面ジオメトリの取得
- ARPlaneGeometry と ARSCNPlaneGeometry

第6章 AR 空間におけるインタラクションを実現する

- 6.1 ヒットテスト(当たり判定)を行う
- 6.2 デバイスの移動に対するインタラクション

第7章 AR 体験の永続化と共有

- 7.1 ARWorldMap
- 7.2 ワールドマップを取得する
- 7.3 ワールドマップを永続化・共有する
- 7.4 ワールドマップからセッションを復元する
- 7.5 ワールドマップ取得タイミング

第8章 フェイストラッキング

- 8.1 フェイストラッキングを開始する - ARFaceTrackingConfiguration
- 8.2 検出した顔のアンカーを取得する - ARFaceAnchor
- 8.3 顔の動きを可視化する
- ブレンドシェイプでアニ文字風3Dアバター

第9章 特徴点を利用する

- 9.1 特徴点を可視化する
- 9.2 フレームに含まれる特徴点群データ
- 9.3 ワールドマップに含まれる特徴点群データ 

第10章 デプスを利用する

- 10.1 ARFrameからデプスデータを取得する
- 10.2 デプスを取得可能なコンフィギュレーション 

第11章 ビデオフォーマット

- 11.1 ARConfiguration.VideoFormat
- 11.2 ビデオフォーマットを指定する
- 11.3 使用可能なビデオフォーマット
- 現行デバイスで使用可能なビデオフォーマット一覧
- ビデオフォーマットはどう使い分けるのか?

第12章 アプリケーション実装例1: 現実空間の長さを測る

- 12.1 ARKitにおける座標と現実のスケール
- 12.2 現実空間における二点間の距離

第13章 アプリケーション実装例2: 空中に絵や文字を描く

- 13.1 スクリーンの中心座標をワールド座標に変換する
- 13.2 頂点座標の配列から、線としてのカスタムジオメトリを構成する 
- 13.3 その他の実装のポイント

第14章 アプリケーション実装例3: Core ML + Vision + ARKit

- 14.1 CoreML・Vision・ARKit連携のポイント

第 15 章 Metal + ARKit

- 15.1 その1-マテリアルをMetalで描画する 
- 15.2 その2-Metalによるカスタムレンダリング