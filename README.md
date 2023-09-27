# FedNIDS: A Federated Learning Framework for Packet-based Network Intrusion Detection System

This repository contains the code for the project "Empirical Evaluation of Autoencoder Models for Anomaly Detection in Packet-based NIDS". The code and proposed framework are provided that can be used to reproduce our work for anomaly detection using Autoencoder in packet-based NIDS.

## Dataset
https://usf.box.com/s/3hj01f8hslsdazoqmr03tgmbxqk4oroy

## Paper abstract

**<p align="center">Figure 1: Network traffic anomaly detection framework using autoencoders.</p>**
<p align="center">
<img src="https://github.com/quocnh/FedNIDS/blob/main/fig_framework.png"/>
</p>

Network Intrusion Detection Systems (NIDS) play a vital role in safeguarding modern computer networks by identifying malicious activities. Deep Neural Networks (DNNs) have shown promise in enhancing the accuracy of NIDS by capturing intricate patterns within network traffic data. However, the distributed and privacy-sensitive nature of network data, coupled with the limitations of flow-based data in NIDS, poses challenges in training robust and accurate models. To address this, we propose the Federated Network Intrusion Detection System (FedNIDS), a novel framework that combines the power of Federated Learning and DNNs to enhance NIDS accuracy, robustness, and privacy preservation using packet-based data. FedNIDS comprises two key stages: Federated DNN Pre-training and Federated Adversarial Fine-tuning. In the pre-training stage, a global DNN model is collaboratively trained on distributed data, while the fine-tuning stage adapts the model to adversarial attacks. Through comprehensive experiments on real-world datasets, we demonstrate that FedNIDS effectively detects various attack patterns while maintaining high accuracy on benign samples. Our framework showcases robustness against adversarial attacks and the capability to adapt to emerging threats. FedNIDS represents a promising approach for enhancing the security of network infrastructures while respecting data privacy constraints.

## Project Structure
```
|---- Dataset
|---- Source
|---- README.md
```

## Reproduce Exp1:
```
|---- nids_fedavg.ipynb
|---- nids_centralized.ipynb
|---- nids_fedprox.ipynb
```
## Reproduce Exp2:
```
|---- nids_fedavg_2017_2018_silo0more80.ipynb
|---- nids_fedavg_2017_2018_silo1more80.ipynb
|---- nids_fedavg_2017_2018_silo2more80.ipynb
|---- nids_fedavg_2017_2018_silo3more80.ipynb
```


## Citation
If you find this repository useful in your research, please cite the following articles as: 

```
@article{
  title={FedNIDS: A Federated Learning Framework for Packet-based Network Intrusion Detection System},
  author={QUOC H. NGUYEN∗, SOUMYADEEP HORE∗, ANKIT SHAH, and TRUNG LE},
  journal={ACM Digital Threats: Research and Practice},
  year={2023}
}

```

