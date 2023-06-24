### @hideIteration true
# TechkidsCAMP

## エージェントのまわりのブロックによってめいれいをかえよう！ @unplugged

エージェントはまわりのブロックのしゅるいによってうごきかたをかえることができるよ！
プログラムをみてみよう！

## エージェントのまわりのブロックによってめいれいをかえよう！

エージェントのまえのブロックがみずいろのブロックのときにみずいろのブロックをこわそう！

``||logic.もし～なら||``ブロックをつかえば、エージェントのまわりのブロックにおうじて、ブロックをこわすかこわさないかをきめることができるんだね！

```template
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (agent.inspect(AgentInspection.Block, FORWARD) == DIAMOND_BLOCK) {
            agent.destroy(FORWARD)
        }
        agent.turn(RIGHT_TURN)
    }
})


```