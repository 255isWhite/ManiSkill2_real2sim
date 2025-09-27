# ManiSkill2-Real2Sim

This repository is forked from the [SimplerEnv ManiSkill2 repo](https://github.com/simpler-env/ManiSkill2_real2sim), with the following changes:
- **Controllers**: We introduce an absolute EEF control mode for both the Google Robot and WidowX, implemented in `mani_skill2_real2sim/agents/configs/google_robot/defaults.py` and `mani_skill2_real2sim/agents/configs/widowx/defaults.py`. For consistency, the default control mode for all tasks is set to absolute EEF.

- **Environment**: We align the camera view configuration of PutEggplantInBasketScene-v0 with that of other WidowX scenarios. The modifications are applied in `mani_skill2_real2sim/envs/custom_scenes/base_env.py` and `mani_skill2_real2sim/agents/configs/widowx/defaults.py`.

To install, run `pip install -e .`

(Original ManiSkill2 docs: https://haosulab.github.io/ManiSkill2)