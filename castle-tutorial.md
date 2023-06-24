### @hideIteration true
# TechkidsCAMP

## コマンドをじっこうする

みぎしたの「▶」ボタンをおしてから、「t」キーをおして「run」とチャットににゅうりょくしてエージェントにめいれいしてみよう！

エージェントがスタートポータルをひらいてくれるよ！

```template
player.onChat("run", function () {
    agent.turn(LEFT_TURN)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 1)
    }
    agent.destroy(DOWN)
    agent.move(DOWN, 1)
    agent.destroy(RIGHT)
    agent.destroy(LEFT)
    for (let index = 0; index < 2; index++) {
        agent.destroy(FORWARD)
        agent.move(FORWARD, 1)
        agent.destroy(RIGHT)
        agent.destroy(LEFT)
    }
})

```