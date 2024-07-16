# Project iyase
<p align="center">
Project iyaseはsoundsphereとosu!に対応した機能豊富なスキンです！
<p align="center">
  Project iyase is a feature-rich skin compatible for soundsphere and osu!
</p>

![Project-iyase-Title](https://github.com/user-attachments/assets/6a2dcd47-e9b1-4a8f-ac42-1de8f04e5d89)

![Project-iyase-Cover-Final](https://github.com/user-attachments/assets/f39f4cdc-22ba-4c30-925f-3c30154e8c45)


![Skin_Banner](https://github.com/iyaseotoge/Project-iyase/assets/168723509/13a1049a-c195-4469-9281-d67e738eb185)

キーモード / Keymode：1K ~ ∞

※スキンはどのキーモードにも対応しており、「vsrg.skin.lua → columnNoteImage」で設定することができます。

The skin supports any keymode, it can be configured in vsrg.skin.lua: columnNoteImage


## おすすめ / Recommendation
PauseとFail画面のバグを修正するために、このスキンは[Irizz-Theme](https://github.com/Thetan-ILW/Irizz-Theme)と一緒に使うことをお勧めします。

※soundsphereを最新バージョンにアップデートすることをお忘れなく。

It is recommended to use this skin with [Irizz-Theme](https://github.com/Thetan-ILW/Irizz-Theme) for the pause and fail bug fix.

※Do not forget to update soundsphere to the latest version.


## 使い方 / Usage

**アイコンを除去する方法 / Removing profile icon**

![pfp icon](https://github.com/user-attachments/assets/b926f8d5-c339-44c9-ba7a-29c08474c346)

```
Path: iyase/Extra/selection-mode/Clean

「selection-mode」ファイルを置き換えてください。
Replace "selection-mode" file.
```

**キーモードを追加する方法 / Adding Keymodes**
```
Path: vsrg.skin.lua → columnNoteImage

例 / Example:
[20] = {3, 1, 2, 1, 2, 3, 1, 2, 1, 3, 3, 1, 2, 1, 3, 2, 1, 2, 1, 3}

説明 / Legend:
[20] = キーモード (Keys)
Y = 欲しいノートイメージ / Preferred Note Image (1/2/3)
1 = 白ノート (White Notes)
2 = 青ノート (Blue Notes)
3 = 黄色ノート (Yellow Notes)
```
**レーンを追加する方法 / Adding Lanes**
```
Path: vsrg.skin.lua → columnLineWidth

例 / Example:
[8] = {0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0}
これは弐寺のスクラッチレーンを真似た設定です。
This will result into something similar to IIDX scratch lanes.

説明 / Legend:
[8] = キーモード
0 = なし
1 = ライン
```
![iidx](https://github.com/iyaseotoge/Project-iyase/assets/168723509/cfd44fee-fe98-46fe-ac6b-4ad37d00af2f)

**ノートスキンを変更する方法 / Changing Note Skins** (soundsphereのみ / for soundsphere only)
```
Path: CTRL+S → Skin:iyase → iyase skin settings → Note images: mania/mania2/mania3

mania: LNフェードあり (w/Percy Cut)
mania2: LNフェードあり (w/Percy Cut)
mania3: LNフェードあり (w/Percy Cut)
mania4: LNフェードなし (No Percy Cut)

※osu!maniaプレイヤーの方は、「mania」フォルダ内のイメージファイルを入れ替えてください。
For osu!mania players you can replace the images in "mania" folder.
```
**Note image:** mania
![mania](https://github.com/iyaseotoge/Project-iyase/assets/168723509/5dcd3522-1b77-4efc-bd76-95c411854050)

**Note image:** mania2
![mania2](https://github.com/iyaseotoge/Project-iyase/assets/168723509/88a0626e-a85f-438a-a88e-03d7d94daa9e)

**Note image:** mania3
![mania3](https://github.com/iyaseotoge/Project-iyase/assets/168723509/873fc4da-210b-4462-9571-99b97a71ab28)

**Note image:** mania4
![mania4](https://github.com/iyaseotoge/Project-iyase/assets/168723509/b40fbe9c-020c-46cf-ab48-578fb95570de)

**判定カウンターを変更する方法 / Changing Judge Counter** (soundsphereのみ / for soundsphere only)
```
Path: 設定(Settings) → Scoring → Score system (+Judgement)

非表示にしたい場合は、スキンの「hide」ボタンを押してください。
To hide press the 「hide」button

Path: CTRL+S → Skin:iyase → Judge counter → Hide
```

**プレイスタート音を変更する方法 / Customizing Start Sound** (soundsphereのみ / for soundsphere only)
```
Path: soundsphere\moddedgame\Irizz-Theme\irizz\ui_sounds\start
soundsphere → UI → Start Sound: 欲しい音 (Desired sound)

欲しい音(.WAV)ファイルを「start」フォルダに入れてゲーム中のstart soundで欲しい音を選んでください。
Place your desired sound in the "start" folder, it must be in .wav format. Then select your sound ingame at "UI Start sound"

※Irizz-Themeがインストールされている必要があります。
Irizz-Theme must be installed.
```

**他のスキン設定 / Other Features** (soundsphereのみ / for soundsphere only)
```
Circle progress bar
Measure line
Show lightings
Hide UI
Judge animation
Accuracy
Hit error
Judge counter
Keyboard overlay
Early/Late (-/+) position
Circle progress bar position
Stage images
osu!PP position

※これはスキン設定にあります (CTRL+S → Skin:iyase)
These features can be found in the skin's settings.
```
![Button](https://github.com/iyaseotoge/Project-iyase/assets/168723509/7768291a-5380-4199-ab18-54110553149c)

※変更を適用するにはこのボタンを押す必要があります。

## 貢献者 / Contributors
Retsukiya → LNデザイナーとクオリティコントロール (LN Designer and Quality Control)

Thetan → プログラマーとヘルパー (Programmer and Helper)

## アップデート / Update
新しアップデートを受け取る為に、このレポか[YouTube](https://www.youtube.com/@iyase_otoge)でフォローしてください。

[iyaseの音ゲーディスコ鯖](https://discord.gg/sxNMa5eWD3)に入ることもできます。ニュース以外では、音ゲーのガイドチャンネルなどが沢山あります。

To be notified of new updates please follow this repository or subscribe to my [YouTube Channel](https://www.youtube.com/@iyase_otoge)
Alternatively, you can also join my [Discord server](https://discord.gg/sxNMa5eWD3) which contains not only skin news but things such as rhythm game guides for every rhythm game and other improvement tools.

## サポーター・パッケージ / Supporter Package
プロジェクトiyaseを気に入って応援してくださる方は、ぜひサポーターパッケージをご購入ください。

※無料版には含まれていない追加ファイルが含まれています。

If you like Project iyase and would like to support me you can purchase the supporter package below. It contains additional files that are not included in the free version.

[Supporter Package #1](https://www.patreon.com/iyase_otoge/shop/project-iyase-v2-3-supporter-package-1-271381?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=productshare_creator&utm_content=join_link) ($5)

[Supporter Package #2](https://www.patreon.com/iyase_otoge/shop/project-iyase-v2-3-supporter-package-2-271403?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=productshare_creator&utm_content=join_link) ($10)

[Supporter Package #3](https://www.patreon.com/iyase_otoge/shop/project-iyase-v2-3-supporter-package-3-271407?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=productshare_creator&utm_content=join_link) ($15)

[Supporter Package #4](https://www.patreon.com/iyase_otoge/shop/project-iyase-v2-3-supporter-package-4-271416?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=productshare_creator&utm_content=join_link) ($20)
