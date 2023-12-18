# Mod6_MachineLearning

Project ini menggunakan EfficientNetB3 sebagai model pretrain yang diambil menggunakan pustaka tensorflow.

## Instalasi python version >= 3.10 
[![Python](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)]([https://github.com/hanifahsantoso/Mod6_ML/issues/2#issue-2042129722)

## Environment
1. Path : 3.10
2. Vscode 

### Web yang diakses
[Klik disini!](http://127.0.0.1:2000)

Dataset Project ini menggunakan dataset rock paper scissor dengan jumlah data sebanyak 2520 file. 
Load image menggunakan image_dataset_from_directory dari pustaka tensorflow dengan pembagian train validation 80% dan test validation 20% dengan seed 123. 
Dataset menggunakan label categorical sehingga label dalam bentuk one hot encoding.

