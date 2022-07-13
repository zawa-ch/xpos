# XPOS

eXtensible Primitive-Object Structure

高い移植性を持ち、大きな仕様上のキャパシティを持つデータ交換用の形式、XPOSのフォーマット定義

## 概要

XPOSはRIFFのような既存のデータ交換用形式の置換え、およびJSONやYAMLといったデータ記述言語のバイナリによる代替を目的として策定されたデータ交換用フォーマットです。

## 現在の状態

現在、文書はドラフト段階です。必要に応じて仕様が追加、または削除される可能性があります。

## 特徴

-	プラットフォーム非依存

-	高い空間効率とスキャン効率の両立

-	事実上無制限の大規模バイナリ・文字列を扱うことができる(最大 2.47x10^611 バイト程度)

-	必要に応じて拡張可能

## リポジトリの内容

-	README.md

-	docs

	-	[specification.md](https://github.com/zawa-ch/xpos/blob/main/docs/specification.md)  
		XPOSデータフォーマット定義の本文

-	[examples](https://github.com/zawa-ch/xpos/tree/main/examples)  
	XPOSおよび他フォーマットとの比較用の例示用データ
