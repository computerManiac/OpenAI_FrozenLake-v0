# OpenAI FrozenLake-v0

OpenAI Frozen Lake v0 solved using Q-Learning. The Q table and hyper-parameters are stored in *qtable.pickle* and *hyper_params.pickle* respectively.

For loading *hyper_params.pickle*, use: 
``` python
hyper_params = pickle.load(open('hyper_params.pickle','rb'))
learning_rate = hyper_params['learning_rate']
epsilon = hyper_params['epsilon']
gamma = hyper_params['gamma']
```
