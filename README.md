# ravdess_song
Song emotion recognition on RAVDESS song dataset   

A simple tutorial/demonstration on deep learning application for emotion recognition from song data.  

## Tested on:  
Tensorflow:  2.5 and 2.6  
Librosa: 8.1  

## Dataset 
The dataset is included in this repo. This is a part of RAVDESS [1] dataset with song data only.
Since it has a license "CC BY-NC-SA 4.0", we can provide it here.

## Dataset partition
*Speaker-dependent:*    
Train: 910 files / 90 %   
Test: 102 files / 10 %    
*Speaker-independent:*  
Train: 20 speakers (1-20) / 836 files /  83 %  
Test: 4 speakers (21-24) / 176 files / 17 %   

## What will you learn
In this tutorial you will learn:  
1. How to extract acoustic features  
2. How to build classifier: NN/MLP/FCN/Dense, LSTM, CNN  
3. How to split dataset into training and test  
4. How to make speaker-independent partition  

## Accucary result  
*Speaker-independet:* 93.%  
*Speaker-independet:* 74.%  

## Next
Life after this (based on problem you're facing):    
1. Try to extract other acoustic features
2. Try other classifiers
3. Try to other datasets

### If you encounter a problem, submit an [issue](https://github.com/bagustris/ravdess_song/issues)

Reference:  
[1] S. R. Livingstone and F. A. Russo, “The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS),” PLoS One, pp. 1–35, 2018, doi: 10.5281/zenodo.1188976.
