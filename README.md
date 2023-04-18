# atari-rl
Testing Various RL Methods on Atari Games

Built off of https://github.com/MushroomRL/mushroom-rl/blob/dev/examples/atari_dqn.py

Each algorithm can be run with ```python mushroomatari.py --algorithm [algorithm name] ```, or ```python mushroomatari.py --algorithm [algorithm name] --debug ``` for very short training time for debugging purposes

Options for algorithm names are ```['dqn', 'ddqn', 'adqn', 'mmdqn', 'cdqn', 'dueldqn', 'ndqn', 'qdqn', 'rainbow', 'sarsa']```

Running with no algorithm specified uses DQN.

I added and am debugging the sarsa option, which uses Using SARSALambdaContinuous. It is continuous, but lots of other RL algorithms (e.g. standard Q learning) are discrete, but there may be additional options to add here https://mushroomrl.readthedocs.io/en/dev/_modules/index.html

New Algorithms can be added by adding it to imports at line 12, adding its argument name at line 156, and specifying the agent (in the elifs beginning at line 347). Specifying the agent is still in progress for sarsa
