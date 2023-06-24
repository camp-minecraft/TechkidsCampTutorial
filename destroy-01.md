### @hideIteration true
# QureoMinecraft

## エージェントをつかって、ブロックをはかいしよう！

エージェントをつかってブロックをはかいするには、
``||agent.エージェントにまえをはかいさせる||``ブロックをつかうよ！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.destroy(FORWARD)
})
```

```template
player.onChat("run", function () {})

```