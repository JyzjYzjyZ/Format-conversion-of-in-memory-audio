# Format-conversion-of-in-memory-audio
A simple tool class to compensate for the extremely slow loading of librosa, the inability to convert soundfiles to raw, and the difficulty of using wave

Audio object interconversion of librosa wave torchaudio soundfile
***
Usage scenarios Audio libraries are inconsistent when using multiple pre-trained models, making them always available on a single load

Support: loading audio resamples and converting to mono at a speed of approximately 46s/130min

input:audioPath or nparray:float64

output:tensor:shape(1,x)

&emsp;&emsp;numpy:interest6 [shap(x) or shape(x,1)]
       
&emsp;&emsp;wave binary:int16

![image](https://raw.githubusercontent.com/JyzjYzjyZ/Format-conversion-of-in-memory-audio/main/readme_ing/img_low_1.jpg)
## install
```
python 3.8.12

pip install soundfile
pip install librosa
pip install torch
pip install copy
```
