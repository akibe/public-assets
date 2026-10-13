## タブラ（tabla/）
- 出典: Subodh Deolekar, "Tabla strokes dataset" (2020), Zenodo. https://doi.org/10.5281/zenodo.4327350
- ライセンス: CC BY 4.0（https://creativecommons.org/licenses/by/4.0/）
- 変更点（元のファイルからの加工）:
  - 打音ごとにテイクを選び、フォルダとファイル名を変えた（元のファイルとの対応は `tabla/sources.json`）。
  - 同じ打音の中で音程と音量を揃えた（音程は最大 ±35 セントの再標本化、音量は冒頭 100ms の RMS）。
  - 末尾 40ms をフェードアウトした（元のファイルは音が鳴っている途中で切れているため）。
- ラベルの意味は Deolekar & Abraham "Tree based classification of tabla strokes"（arXiv 1801.01712）の表1による:
  Da = dha（धा）、Dh = dhin（धीं）、Di = din（दि）、Ge = ge、Ka = ke、N = n（न）、Na = na、T = t/r（त/र）、Ta = ta、Ti = ti、Tin = tin、Tr = tra（त्र）、Tu = tun

| フォルダ | 元のラベル | テイク数 |
|---|---|---|
| na | Na | 5 |
| tin | Tin | 12 |
| tun | Tu | 12 |
| ta | Ta | 12 |
| te | T | 12 |
| ti | Ti | 12 |
| ke | Ka | 5 |
| ge | Ge | 5 |
| tr | Tr | 9 |
| dha | Da | 12 |
| dhin | Dh | 12 |
| di | Di | 5 |
| n | N | 12 |