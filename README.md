# PoliInfo4-DryRun-Stance-Classification-2

## 目的
Stance Classification-2では，明示的な賛否表現をマスクした討論発言から，議案への賛否を推定します。

- 入力
    - 以下に示すCSVのstanceを除く各列 (文字コードはUTF-8)
- 出力
    - 議案への賛否（CSVの[stance]列）
    
## CSVの列
- id	識別子 [自治体コード(6桁)]-[通し番号(5桁)]
- prefecture 都道府県名
- assembly	自治体名
- meeting	議会名
- date		日付
- speaker	発言者名
- utterance	賛成、反対を[STANCE]に置換した発言文
- target	議案番号
- stance	賛成、あるいは、反対　# Test dataは空欄にする
