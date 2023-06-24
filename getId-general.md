### @hideIteration true
# TechkidsCAMP

## ここからさきは、じぶんでプログラムをつくってみよう！
わからないことがあったらメンターさんをよんでね！

```ghost
player.onChat("run", function () {
    for (let index = 0; index < 4; index++) {
        if (agent.inspect(AgentInspection.Block, FORWARD) == DIAMOND_BLOCK) {
            agent.destroy(FORWARD)
        }
        agent.turn(RIGHT_TURN)
        agent.move(FORWARD)
    }
})

```

```template
player.onChat("run", function () {})

```