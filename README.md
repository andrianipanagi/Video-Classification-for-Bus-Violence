# Video-Classification for Bus-Violence forked by ciampluca/bus-violence-benchmark-eval

## 📂 Dataset
During training the [bus-violence dataset](https://zenodo.org/records/7044203#.Yxm7hmxBxhE) was used. It contains videos that are classified as:
- VIOLENCE 
- NONVIOLENCE
  
The dataset has the structure:
```
bus-violence/
├── videos/
│ ├── NONVIOLCNE_1.mp4
│ ├── VIOLENCE_2.mp4
│ └── ...
```

## Modify the yaml files

Modify the config.yaml file in the conf directory to change the model during training. 


## Start Training

python train.py
