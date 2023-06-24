### @hideIteration true
# QureoMinecraft

## エージェントをなんほかまえにいどうさせよう！

ひだりにある「エージェント」ボタンをおすと``||agent.エージェントをまえに1ブロックいどうさせる||``ブロックがあるからそれをあおいろの「チャットコマンドrunをにゅうりょくしたとき」のなかにいれてみよう！

そしたらしろいところをクリックしてすきなすうじをいれたらそのぶんエージェントがまえにすすむよ！

さいごにみぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("run", function () {})

```