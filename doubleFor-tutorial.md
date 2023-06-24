### @hideIteration true
# TechkidsCAMP

## くりかえしをくみあわせよう！ @unplugged
``||loops.くりかえし||``ブロックでおなじうごきをくりかえさせることができたね！
くりかえしをくみあわせると、もっとふくざつなうごきをさせることができるよ！
プログラムをかくにんしよう！

## くりかえしを２つくみあわせよう！

``||loops.くりかえし||``ブロックのなかに``||loops.くりかえし||``ブロックをいれよう！
ここでは、ブロックをこわすプログラムを４かいくりかえしたら、1つうえにいっておなじことをもういちどくりかえしているね！

```template
player.onChat("run", function () {
    for (let index = 0; index < 2; index++) {
        for (let index = 0; index < 4; index++) {
            agent.destroy(FORWARD)
            agent.turn(RIGHT_TURN)
        }
        agent.move(UP, 1)
    }
})

```