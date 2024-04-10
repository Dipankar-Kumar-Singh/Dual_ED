
# Dual_ED


## Installation
This code needs Python-3.7 or higher.
```bash
pip3 install torch==1.8.1+cpu torchvision==0.9.1+cpu torchaudio===0.8.1 -f https://download.pytorch.org/whl/torch_stable.html
pip3 install -r requirements.txt
```

## Dataset Preprocessing
Preprocess all datasets using the command
```bash
python3 preprocess.py SMAP MSL SWaT WADI SMD MSDS UCR MBA NAB
```
