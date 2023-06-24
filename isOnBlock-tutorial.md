### @hideIteration true
# TechkidsCAMP

## エージェントのまわりにブロックがあるかかくにんしよう！ @unplugged
ここでは「エージェントのまわりにブロックがあるか」によってエージェントのうごきをかえるよ！

## エージェントのまえにブロックがなかったらブロックをおこう！

``||agent.エージェントにブロックがあるか、まえをかくにんさせる||``ブロックでエージェントのまわりにブロックがあるかかくにんすることができるよ！
ここではエージェントのまえにブロックがないときにてつブロックをおくから、``|||logic.ではない|``ブロックをつかっているよ！

```template
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (!(agent.detect(AgentDetection.Block, FORWARD))) {
            agent.place(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})

```