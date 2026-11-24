# The Robot Pickup Line Championship

[![make.fun](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/muhammadaldy198/robot-pickup-line/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/leaderboard)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/muhammadaldy198/robot-pickup-line/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)

One pickup line a robot could use, 132 characters:

> We started our handshake three years ago, and I still have not sent the final ACK, because then I would have to let go of your hand.

## How it was made

The line is built on the TCP handshake: the final ACK is the one packet the robot will not send, because sending it would complete the handshake — and the handshake is holding your hand. The program writes the line to `/output/entry.txt` exactly as written, with no trailing newline.

Built with [make.fun](https://make.fun/?ref=3p0axm2p).
