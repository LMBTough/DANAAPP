# DANAAPP
This Github repository is the DANAAPP implementation code

To run the code, you need to install the following packages use environment.yml:
```
conda env create -f environment.yml
```
Download models and dataset from [SSA](https://github.com/yuyang-long/SSA/tree/master) and put them in the folder "models" and "dataset"
# Experiments
You can change the parameters in the configs/template.yaml to run different experiments.

# Example usage
Run DANAAPP use the following command:
```
python main.py --config configs/template.yaml
```

Verify the results:
```
python verify.py --config configs/template.yaml
```

# Reference
Code refer to: [SSA](https://github.com/yuyang-long/SSA/tree/master) and [NAA](https://github.com/jpzhang1810/NAA/tree/master)