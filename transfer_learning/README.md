#Hands-On Transfer Learning with Python





The code will look like the following:
```
import glob
import numpy as np
import os
import shutil
from utils import log_progress
np.random.seed(42)
```
데이터 저장소
https://drive.google.com/open?id=15fmF_etMqGprv87m-lF1VZKFlmev4rh8

### Software and Hardware List

Python 3.6, 
TensorFlow 1.10, 
Keras 2.2.0 
GraphViz
Windows, Mac OS X, and Linux (Any)
              
* 필요 Python 패키지

pip install xlrd seaborn matplotlib numpy scipy sklearn jupyter pydot 

* 원본 Source Repository와의 차이점

1. 최근 버전의 tensorflow와 keras를 사용하기로 하였습니다. 그에 따라서 ipynb의 파일들이 책 또는 원본 Repository와 다를 수 있습니다.
2. Keras 사용 부분의 경우 tensorflow의 keras 패키지(tf.keras)를 사용하도록 변경하였습니다. 
3. ipynb에서 사용한 '%matplotlib inline'의 위치를 ipynb에 처음에 나오도록 바꾸었습니다.