Our project de-noises signal data, and is implemented for predicted smoother signals of pulsar telescope data. A full investigation can be found in the file "NN_Final_Project.pdf, which details the problem and results. We create and train two neural networks, an LSTM and Autoencoder, which are both trained on simulated datasets. 

All code is stored in the google-colab attached file "NNProj3.ipbyn" and contains instructions and code to produce simulated data, add noise, train models, and test on new data. The data on which we tested our model is too large to be uploaded to github, but it is obtained from the LAT public data--instructions to obtain the data are found at https://github.com/rsnemmen/Fermi-LAT-tutorial/blob/master/prepare.md and use the coordinates as shown below. 

<img width="561" alt="Screenshot 2025-05-02 at 9 31 29 PM" src="https://github.com/user-attachments/assets/5f028d0e-1bb4-4e41-8854-ba4284e3a660" />

All of the simulated data does produce random results, which should produce relatively the same behaviors but may have slightly different examples and exact results. Otherwise, all analysis from raw data to predictions is included in the code. We obtain code from https://github.com/christianversloot/keras-autoencoders to produce the autoencode, which is a great resource for simple autoencoders for signal denoising. 
