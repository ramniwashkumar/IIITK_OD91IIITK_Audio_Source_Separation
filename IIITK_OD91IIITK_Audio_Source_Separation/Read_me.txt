Instructions to run the files

Each of the vocals.ipynb, bass.ipynb, drums.ipynb and others.ipynb are to be run separately.

These Libraries are required to download before running the model:
These are available in requirement.txt

File directories to create in google drive:

data - for storing the dataset

app/test - to store models

numpy - to store numpy arrays after preprocessing the data

The notebook will be used on a dataset half preprocessed, i.e. on wav files extracted from stem mp3 files. 

The link to download datasets:

Training data - https://drive.google.com/drive/folders/1q7n9NnY7r5herMnYoDz0efFVxh4vDP5i?usp=sharing

Testing Data - https://drive.google.com/drive/folders/1mhou1AAeNTzpSFymNSrH1YKqe5hUgGjh?usp=sharing

These paths are particularly defined for using the model extraction of the dataset using google Colab;
if you are running model on the local machine we need to create same files for working with the dataset.

For giving the model name we need to manually check for the best model in the epochs becausue the names are relative from training. 

While running in the local machine ignore the google.colab part. 

The final prediction of each audio file(one file per iteration) is named with test1.wav.

File location in local machine-

Training -  data/musdb18_train/
Testing - data/musdb18_testrain/

Models - app/test

Numpy arrays - numpy/

The outputs of Vocals, Bass, Drums and Others are listed in the respective folders.

The samples of vocals and instrument noise are there in VOCALS directory.


Every step of preprocessing to model are also provided as a seperate jupyter notebooks - mp3_to_wav.ipynb, stempeg.ipynb, audio_source_preprocess.ipynb


