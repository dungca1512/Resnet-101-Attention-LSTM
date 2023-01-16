# Image Captioning with LSTM and RNN using PyTorch on COCO Dataset
#### 1. Install requirements

```bash
pip install -r requirements.txt
```


#### 2. Train the model

```bash
python train.py --model_name[your_model_name]
```

#### 3. Test the model 
```bash
python test.py --model_name[your_model_name]
python infer.py --image='data/test/file_name.png' 
```
`test.py` to evaluate on entire dataset and `infer.py` to infer results from one image.
<br>


