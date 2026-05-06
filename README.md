# The implementation of "Objective Shaping with Hard Negatives: Windowed Partial AUC Optimization for RL-based LLM Recommenders" (TAWin).

## File Description

- sft.py: the SFT code
- TAWin.py: the TAWin code
- TAWin_trainer.py: the GRPO trainer tailored for recommendation

The training instructions can be seen in TAWin.sh and sft.sh, while the evaluation instructions are in evaluate.sh.

## Quickstart

- Create a virtual Python environment.

```bash
conda create -n TAWin
```

- Install required packages.

```bash
pip install -r requirements.txt
```

- Execute the TAWin the training bash.

```bash
bash TAWin.sh
```

- Run the evaluation bash.

```bash
bash evaluation.sh
```
