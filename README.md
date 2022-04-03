# Dataset for Spring 2022 UF Audio Engineering Society Software Project
our data


## How to use
We have been using google colab notesbooks as our development enviroment
* when in colab you can run the code `!git clone https://github.com/aesuf/orchestral_samples`
to download the dataset
### /data
* the data/ folder contains 10,000+ wav files,
  of different orchestral instruments playing single notes: 16 different instruments being represented
 * samples sourced from https://philharmonia.co.uk/resources/sound-samples/
You can also just download the dataset to your local computer.
### /.npz
* the .npz file is a compressed file of three precomputed numpy arrays.
* The x data are precomputed mel spectrograms
* labels are the names of the instruments
* y values is a array of a number corresponding to each intrument mapped ot all the samples
