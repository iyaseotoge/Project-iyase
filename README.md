# Project iyase
Project iyaseはsoundsphereとosu!に対応した機能豊富なスキンです！

Project iyase is a feature-rich skin compatible for soundsphere and osu!

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

キーモードを追加する方法 / Adding Keymodes
```
vsrg.skin.lua → columnNoteImage

例 / Example:
[20] = {Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y, Y}

説明 / Legend:
[20] = 20キー (Keys)
Y = 欲しいノートイメージ / Preferred Note Image (1/2/3)
1 = 白ノート (White Notes)
2 = 青ノート (Blue Notes)
3 = 黄色ノート (Yellow Notes)
```

ノートスキンを変更する方法 / Changing Note Skins (soundsphereのみ / for soundsphere only)
```
CTRL+S → Skin:iyase → iyase skin settings → Note images: mania/mania2/mania3

mania: LNフェードあり (w/Percy Cut)
mania2: LNフェードあり (w/Percy Cut)
mania3: LNフェードあり (w/Percy Cut)
mania4: LNフェードなし (No Percy Cut)

※osu!maniaプレイヤーの方は、「mania」フォルダ内のイメージファイルを入れ替えてください。
For osu!mania players you can replace the images in "mania" folder.
```

判定カウンターを変更する方法 / Changing Judge Counter (soundsphereのみ / for soundsphere only)
```
設定(Settings) → Scoring → Score system + Judgement

To hide press the 「hide」button
```

他のスキン設定 / Other Features (soundsphereのみ / for soundsphere only)
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

## アップデート / Update
新しアップデートを受け取る為に、このレポか[YouTube](https://www.youtube.com/@iyase_otoge)でフォローしてください。
[iyaseの音ゲーディスコ鯖](https://discord.gg/sxNMa5eWD3)に入ることもできます。音ゲーのガイドチャンネルなどがたくさんあります。

To be notified of new updates please follow this repository or subscribe to my [YouTube Channel](https://www.youtube.com/@iyase_otoge)
Alternatively, you can also join my [Discord server](https://discord.gg/sxNMa5eWD3) which contains not only skin news but things such as rhythm game guides for every rhythm game and other improvement tools.
