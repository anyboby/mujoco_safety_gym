# mujoco_safety_gym

A repo with the evaluation environments accompanying the paper Safe Continuous Control with Constrained Model-Based Policy Optimization [https://arxiv.org/abs/2104.06922](https://arxiv.org/abs/2104.06922).
This repository contains safety constrained environments for the ant- and halfCheetah robot. 

<p align="center">
	<!-- <img src="https://drive.google.com/uc?export=view&id=1DcXi5wY_anmtlNeIErl1ECgKGsGi4oR1" width="80%"> -->
	<img src="https://drive.google.com/uc?export=view&id=1DcXi5wY_anmtlNeIErl1ECgKGsGi4oR1" width="80%">
</p>


## Prerequisites
This repository is based on OpenAI gym and the mujoco physics simulator. To install, execute the following commands in a virtual environment of your choice:

```bash
pip install gym
pip install mujoco-py
```

## Installation
To install the environments, simply clone this repository and import the 'mujoco_safety_gym' module. 

```bash
git clone https://github.com/anyboby/mujoco_safety_gym.git
```

## Usage
The environments are registered upon importing the "mujoco_safety_gym" module. An example of the usage is provided in [example.py](example.py).

```python
import gym
import mujoco_safety_gym

ant_env=gym.make("AntSafe-v2")
hc_env=gym.make("HalfCheetahSafe-v2")

```
