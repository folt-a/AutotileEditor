このリポジトリはGodotのアドオン[AutotileEditor](https://github.com/newold3/AutotileEditor)をForkして、
日本語翻訳や一部機能を追加したものです。

# AutotilesEditor

RPGツクール形式のオートタイル画像をGodotのTileMap、Tilesetsに変換できます。

水面のアニメーションオートタイルにも対応しています

![GitHub Logo](screenshots/preview1.png)

## 対応バージョン

Plugin version: Godot v3.4

## 機能特徴

* 1クリックでタイルセット全体を作成
* 個々のオートタイルを作成
* オートタイルアニメーションを作成
* シングルタイル/シングルアニメーションタイルを作成

## インストール

通常のアドオンと同じ方法でインストールします。

1. ↑のCode→Downloadボタンを押してこのリポジトリをダウンロードし、解凍する。
2. Godot プロジェクト内の **addons** ディレクトリへ、  このリポジトリの **addons** ディレクトリに入っている **RPG_maker_Autotile2_3x3** ディレクトリをコピーする。
3. Godot エディタで プロジェクト→プロジェクト設定→プラグインタブを開き、  **Create Autotile from RPG Makers tilesets** のステータス欄の☑にチェックを入れて有効にする。
4. プロジェクト→ツール→**Autotile Editor** が追加されているのでクリックする。  
または、**res://addons/RPG_maker_Autotile2_3x3/CreateAutoTile.tscn**をシーン実行する。

## 更新

* 01/20/2022
	* 日本語翻訳を追加
	* オート床タイルのパレットサムネイル用の部分が塗られてしまう問題を修正(floor.dat)
	* Navigationを作成できるように追加

## ライセンス

MIT License.

---

↓Fork元Readme原文

---

# AutotilesEditor

Convert tilesets, autotiles and autotiles animated from RPG Maker to tilesets of Godot

A simple demonstration video: https://www.youtube.com/watch?v=YMDOobC4Jyg

![GitHub Logo](screenshots/preview1.png)

## Compatibility

Plugin version: Godot v3.2

## Features:

* Create a whole tileset with 1 click
* Create individual autotiles
* Create Autotiles animated
* Create single tiles / single animated tiles

## Installation:

You'll need the Godot Engine to run this.

To use AutotilesEditor as an Addon:

1. Copy the "addons" folder to your project.
2. Enable **Create Autotile from RPG Makers tilesets** addon on "Project Settings".
3. Now will appear a new item menu in "Project/Tools" called **Autotile Editor** and you can click it to open the Autotiles Editor.

Done!

## Updates:

* 01/09/2020:
	* Update to version 1.1
	* Added Auto-collision
	* Added Auto-occlusion
	* Added option to set level of compress of images before be saved
	* Fixed minor bugs
* 12/07/2020:
	* Setup of the finished project on GitHub.

## License:

MIT License.
