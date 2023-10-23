### @hideIteration true
# TechkidsCAMP

## エージェントにトンネルをほってもらおう！

みぎしたの![](https://raw.githubusercontent.com/camp-minecraft/TechkidsCampTutorial/master/images/playbutton.png)をおしたあと、tキーをおして「run」とチャットににゅうりょくしてプログラムをうごかしてみよう！

```ghost
player.onChat("run", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 7; index++) {
        agent.destroy(FORWARD)
        agent.move(FORWARD, 1)
        for (let index = 0; index < 2; index++) {
            agent.destroy(RIGHT)
            agent.destroy(LEFT)
            agent.destroy(UP)
            agent.move(UP, 1)
        }
        agent.destroy(RIGHT)
        agent.destroy(LEFT)
        agent.move(DOWN, 2)
    }
})
```

```template
player.onChat("run", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 7; index++) {
        agent.destroy(FORWARD)
        agent.move(FORWARD, 1)
        for (let index = 0; index < 2; index++) {
            agent.destroy(RIGHT)
            agent.destroy(LEFT)
            agent.destroy(UP)
            agent.move(UP, 1)
        }
        agent.destroy(RIGHT)
        agent.destroy(LEFT)
        agent.move(DOWN, 2)
    }
})

```