### @hideIteration true
# QureoMinecraft

## エージェントをつかって、ブロックをはかしよう!

``||agent.エージェントにまえをはかいさせる||``ブロックと``||agent.エージェントをまえに1ブロックいどうさせる||``ブロックとくみあわせてエージェントにブロックをこわしてもらおう！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.destroy(FORWARD)
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("run", function () {})

```