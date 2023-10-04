# Using Deep Q-Learning to win Breakout

![Winning GIF](https://github.com/masskro0/dqn_breakout/blob/master/output/ATARI_frame_13642878_reward_419.0.gif)

Simple and efficient way to win Breakout using Deep Q-Learning.

I didn't include the weights of the winning rounds because I generated too many weights and lost track. But within 16 hours of training, you should be able to get them by yourself.

## Evaluation Results
![Training Results](docs/training_results.png "Training Results")
![Evaluation Results](docs/evaluation_results.png "Evaluation Results")
![Loss Values](docs/loss_values.png "Loss Values")

## Setup
- Python 3.8.10
- NVidia GPU (GTX 1060, RTX 3060)
- Ubuntu 20.04 & Windows

## Installation
`pip install -r requirements.txt`

## Launching
Run `jupyter-notebook` in your terminal. Then select `main.ipynb` and start running the blocks from top to bottom. You should visually see the output.
