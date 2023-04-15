# Spatial-Temporal Multi-Scale Representation for Bus Ridership Prediction

![Dynamic Spatio-Temporal Multi-Scale Representation for Bus Ridership Prediction](figures/Overall.jpg "Model Architecture")


## Requirements

Dependency can be installed using the following command:
```shell
pip install -r requirements.txt
```
## Data Preparation
Download ASBUS from https://pan.baidu.com/s/1jjM2Ax09poiu1CDX-sFMOg?pwd=2520 Uncompress them and move them to the raw_data folder.

## Run the Pre-trained Model on ASBus
```shell
python run_model.py  --task traffic_state_pred --model DSTMR --dataset AGBUS --train False --exp_id ("id of experiment")
```
## Model Training

```shell
python run_model.py  --task traffic_state_pred --model DSTMR --dataset AGBUS
```
