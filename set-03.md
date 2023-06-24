### @hideIteration true
# QureoMinecraft

## エージェントをつかって、ブロックをおいてもらおう！

``||agent.エージェントにまえへおかせる||``ブロックと``||agent.エージェントをまえに1ブロックいどうさせる||``ブロックとくみあわせてエージェントにブロックをおいてもらおう！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.place(FORWARD)
    agent.move(FORWARD, 1)
})
```

```template
player.onChat("run", function () {})

```