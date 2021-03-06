渡辺さん 論文


## アブスト
フォルト攻撃は暗号の脆弱性をつく攻撃である
この論文は楕円曲線暗号状ので新しいフォルト攻撃の手法を示す

## 結論
提案された攻撃手法は、既存の攻撃手法よりも高い成功確立があることがわかった。
NIST標準パラメータ

## 実験
本研究では, ペアリング暗号の Miller algorithm に対する反復回数をフォールト導入対象とした攻撃手法を, 楕円曲線暗号の高速スカラー倍算アルゴリズムに適用する.

以下の条件において, 試行回数に対して攻撃成功となる確率を測定する.
• Double and add, Double and add always, Montgomery ladder アルゴリズムのループ回数 n を変更する.
• 復元した k が, 秘密鍵 k と一致した際に攻撃成功とする.
• 試行回数 m は 100 回とする.
• 使用するパラメータは, NIST(米国国立標準技術研究所) が推奨する楕円曲線のシステムパラメータ P-192,
P-256[15] を用いる.


## 課題
• 本手法と他の手法との組み合わせる (途中から他の離散対数問題の解法を用いるなど).
• 反復回数がランダムである場合の対抗策の付加.
• デバイスを用いた実験.

## 関連研究

-------------------------------------------

## どんなもの？
新しいFault攻撃の提案

## 先行研究と比べてどこがすごい？
NIST標準パラメータを使った攻撃は既存手法より、攻撃成功確率が高い

##  技術や手法のキモはどこ？
ペアリング暗号の Miller algorithm に対する反復回数をフォールト導入対象とした攻撃手法を, 楕円曲線暗号の高速スカラー倍算アルゴリズムに適用


##  どうやって有効だと検証した？
反復回数を減らす手法

##  議論はある？
防御さくは、ペアリング暗号に対する　フォールト攻撃と変わらない

##  次に読むべき論文は？

## search word
ペアリング暗号とは？
ペアリング暗号に対する攻撃とは？
フォルト攻撃とは？

Total 40分くらい
