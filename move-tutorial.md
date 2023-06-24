### @hideIteration true
# TechkidsCAMP

## ダンジョンをたんけん！ @unplugged

プログラムをつかってエージェントにめいれいして、ダンジョンをクリアしよう！
まずはエージェントをうごかすほうほうをまなんでみよう！

## エージェントをうごかしてみよう！

``||agent.エージェントをまえに１ブロックいどうさせる||``ブロックは、エージェントをうごかすことができるよ！
みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおして、「run」とチャットらんににゅうりょくしてプログラムをうごかしてみよう！

プログラムをうごかすにはどのようにすればよかったかな？

```template
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
```