# U-NET

Create environment 
```python
conda create -n u-net pip python=3.7 
conda activate u-net
conda/pip install tensorflow==2.5.0
conda/pip install scikit-image
pip install imgaug

```
При использовании conda install imgaug возникают конфликты библиотек


Чтобы конверитировать json-files нужно запустить на выполнение блокнот JsonToMask.ipynb. Он создаст изображения и маски, которые после будут использоваться для обучения модели.