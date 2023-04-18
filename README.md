# atari-rl
Testing Various RL Methods on Atari Games

Built off of https://github.com/MushroomRL/mushroom-rl/blob/dev/examples/atari_dqn.py

Each algorithm can be run with ```python mushroomatari.py --algorithm [algorithm name] ```, or ```python mushroomatari.py --algorithm [algorithm name] --debug ``` for very short training time for debugging purposes

Options for algorithm names are ```['dqn', 'ddqn', 'adqn', 'mmdqn', 'cdqn', 'dueldqn', 'ndqn', 'qdqn', 'rainbow']```

Running with no algorithm specified uses DQN.