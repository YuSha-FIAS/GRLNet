# Regional-Local Adversarially Learned One-Class Classifier Anomalous Sound Detection in Global Long-Term Space (GRLNet)

![img1](https://github.com/CavitationDetection/GRLNet/blob/main/Image/framework.png)
## Requirements

- Python 3.8.11
- torch 1.9.1
- torchvision 0.10.1

Note: our model is trained on NVIDIA GPU (A100).

## Code execution

- train.py is the entry point to the code.
- main.py is the main function of our model.
- network.py is the network structure of local generator, regional generator and the discirminator of our method.
- opts.py is all the necessary parameters for our method (e.g. comprehensive output factor, learning rate and data loading path and so on).
- Execute train.py

Note that, for the current version. test.py is nor required as the code calls the test function every iteration from within to visualize the performance difference between the baseline and the GRLNet. However, we also provide a separate test.py file for visualising the test set. For that, the instructions can be found below.

- Download trained generators and discirminator models from [here] and place inside the directory ./models/
- run test.py


## Updates

[11.2.2022] For the time being, test code (and some trained models) are being made available. Training code will be uploaded in some time.


For any queries, please feel free to contact YuSha et al. through yusha20211001@gmail.com

If you find this code helpful, please cite our paper: 
