# Env

## 系统软件

主要是为了打开 nc 文件相关

```
apt-get update && apt-get install -y libeccodes0 libeccodes-dev
```

## conda

```
conda create -n aqi_gpu python=3.11.9

pip install torch==2.3.1+cu121 torchvision==0.18.1 torchaudio==2.3.1 --index-url https://download.pytorch.org/whl/cu121
pip install torch_geometric==2.5.3 pyg_lib==0.4.0 torch_scatter==2.1.2 torch_sparse==0.6.18 torch_cluster==1.6.3 torch_spline_conv==1.2.2 -f https://data.pyg.org/whl/torch-2.3.1+cu121.html

pip install -r requirements_aqi.txt
```
