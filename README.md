# Getting Started with Flatland

![Flatland](https://i.imgur.com/0rnbSLY.gif)

> **Flatland** is an environment for developing and comparing multi-agent reinforcement learning algorithms in gridworlds.

This repository contains notebooks to get you started on the right track with the Flatland environment, in order to take part in the [AIcrowd Flatland Challenge](https://www.aicrowd.com/challenges/flatland-challenge).

If you want to dive into challenge baselines right away, [check out the various approaches below](#challenge-baselines). 

Discovering Flatland
---

**Part 1: The Rail Environment**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_1.ipynb)

- Create a `RailEnv` environment and render it
- Check out the default observations
- "Train" a random agent

**Part 2: Observations & Predictions**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_2.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_2.ipynb)

- Finding suitable observations
- Using predictions
- Crafting custom observations and predictions

**Part 3: Level Generation**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_3.ipynb)

- Creating random rail networks
- Creating schedules
- Adjusting size and difficulty

**Part 4: Malfunctions**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_4.ipynb)

- Introducing stochastic malfunctions
- Handling malfunctions

**Part 5: Speed Profiles**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_5.ipynb)

- Handling agent speed
- Handling partial moves


Challenge Baselines
---

The Flatland Challenge can be approached in different ways - for example using methods from **operations research**, **reinforcement learning**, or anything else!

The following notebooks show how to approach the problem using each of these methods.

**Reinforcement Learning: DDQN**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_5.ipynb)

Solve simple rail problems using Double DQN.

**Operations Research**

[![Open In Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MasterScrat/getting-started/master?filepath=notebook_1.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MasterScrat/getting-started/blob/master/notebook_5.ipynb)

Solve simple rail problems using OR methods.