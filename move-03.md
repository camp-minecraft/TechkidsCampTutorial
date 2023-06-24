### @hideIteration true
# QureoMinecraft

## エージェントをいろんなほうこうにいどうさせよう！

ひだりにある「エージェント」ボタンをおすと``||agent.エージェントをまえに1ブロックいどうさせる||``ブロックがあるからそれをあおいろの「チャットコマンドrunをにゅうりょくしたとき」のなかにいれてみよう！

そしたら「まえ」をクリックしたらメニューがでてくるからほうこうをえらんで、エージェントをどのほうこうにすすめるかきめよう！

さいごにみぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("run", function () {})

```