# Q-Learning Frozen Lake Game

- Applying Q-learning algorithm into solving the Frozen Lake game
- Explore the usage of reinforcement learning on games

## Frozen Lake

Winter is here. You and your friends were tossing around a frisbee at the park when you made a wild throw that left the frisbee out in the middle of the lake. The water is mostly frozen, but there are a few holes where the ice has melted. If you step into one of those holes, you'll fall into the freezing water. At this time, there's an international frisbee shortage, so it's absolutely imperative that you navigate across the lake and retrieve the disc. However, the ice is slippery, so you won't always move in the direction you intend. The surface is described using a grid like the following:

```
SFFF
FHFH
FFFH
HFFG
```

State | Description | Reward |
----- | ------------ | ---------- |
```S``` | Agent’s starting point - safe | 0 |
```F``` | Frozen surface - safe | 0 | 
```H``` | Hole - game over | 0 |
```G``` | Goal - game over | 1 |

## Demo

[Youtube Link](https://youtu.be/nf5CmRxlB9s)
![](src/demo.gif)

