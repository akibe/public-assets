## ガムラン（gamelan/）
- 出典: Digitópia Casa da Música, "Casa da Música's Javanese Gamelan" sample library（録音: Pedro Augusto & Rui Penha、編集: Pedro Augusto）
  https://github.com/Digitopia/CDM-GAMELAN-SAMPLE-LIBRARY （ポルト、カサ・ダ・ムジカが所有するジャワのガムラン）
- ライセンス: Artistic License 2.0（同じフォルダの LICENSE-Artistic-2.0.txt）
- 変更点（元のファイルからの加工。この版は元のライブラリとは別のもの）:
  - スレンドロの組から、曲で使う楽器・音だけを選び、フォルダとファイル名を変えた（下の表）。
  - 1組全体を +91 セント高くした（再標本化。スレンドロの 1 を C# に合わせるため。音同士の音程は変えていない。高くした分だけ短い）。
  - 冒頭の無音を詰めた（音の 2ms 前から、1ms のフェードイン）。組ごとに、一番大きいファイルのピークが -1dB になるよう音量を変えた。
  - エフェクト（残響など）は掛けていない。
- 作成: github.com/akibe/bgm01 の tools/build_gamelan.py

| 組 | n | ファイル | 元のファイル | 音 |
|---|---|---|---|---|
| jw_kenong | 0 | 01.wav | KENONG/KSL1h.wav | 1（高） |
| jw_kenong | 1 | 02.wav | KENONG/KSL2.wav | 2 |
| jw_kenong | 2 | 03.wav | KENONG/KSL3.wav | 3 |
| jw_kenong | 3 | 04.wav | KENONG/KSL5.wav | 5 |
| jw_kenong | 4 | 05.wav | KENONG/KSL6.wav | 6 |
| jw_kempul | 0 | 01.wav | GONG/GKSL1p.wav | 1 |
| jw_kempul | 1 | 02.wav | GONG/GKSL2p.wav | 2 |
| jw_kempul | 2 | 03.wav | GONG/GKSL3p.wav | 3 |
| jw_kempul | 3 | 04.wav | GONG/GKSL5p.wav | 5 |
| jw_kempul | 4 | 05.wav | GONG/GKSL6p.wav | 6 |
| jw_gong | 0 | 01.wav | GONG/GSp.wav | ゴング・スウカン（弱） |
| jw_gong | 1 | 02.wav | GONG/GAp.wav | ゴング・アグン（弱） |
| jw_gong | 2 | 03.wav | GONG/GAf.wav | ゴング・アグン（強） |
| jw_kethuk | 0 | 01.wav | KETHUK/KtSL2s.wav | クトゥッ 2（止めた音） |
| jw_kethuk | 1 | 02.wav | KETHUK/KtSL2.wav | クトゥッ 2 |
| jw_gambang | 0 | 01.wav | GAMBANG/GSL1l.wav | 1（低） |
| jw_gambang | 1 | 02.wav | GAMBANG/GSL2l.wav | 2（低） |
| jw_gambang | 2 | 03.wav | GAMBANG/GSL3l.wav | 3（低） |
| jw_gambang | 3 | 04.wav | GAMBANG/GSL5l.wav | 5（低） |
| jw_gambang | 4 | 05.wav | GAMBANG/GSL6l.wav | 6（低） |
| jw_gambang | 5 | 06.wav | GAMBANG/GSL1.wav | 1 |
| jw_gambang | 6 | 07.wav | GAMBANG/GSL2.wav | 2 |
| jw_gambang | 7 | 08.wav | GAMBANG/GSL3.wav | 3 |
| jw_gambang | 8 | 09.wav | GAMBANG/GSL5.wav | 5 |
| jw_gambang | 9 | 10.wav | GAMBANG/GSL6.wav | 6 |
| jw_gambang | 10 | 11.wav | GAMBANG/GSL1h.wav | 1（高） |
| jw_saron | 0 | 01.wav | SARON/SPSL6l.wav | ペキン 6（低） |
| jw_saron | 1 | 02.wav | SARON/SPSL1.wav | ペキン 1 |
| jw_saron | 2 | 03.wav | SARON/SPSL2.wav | ペキン 2 |
| jw_saron | 3 | 04.wav | SARON/SPSL3.wav | ペキン 3 |
| jw_saron | 4 | 05.wav | SARON/SPSL5.wav | ペキン 5 |
| jw_saron | 5 | 06.wav | SARON/SPSL6.wav | ペキン 6 |
| jw_saron | 6 | 07.wav | SARON/SPSL1h.wav | ペキン 1（高） |
