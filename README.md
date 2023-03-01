# Detection-Of-DDoS-Attack-Using-Machine-Learning-Model


## Overview

Here my objective is to develop a model that can accurately identify DDoS attacks in network traffic data. This will help the **organizations** detect and respond to DDoS attacks in a timely manner, protect their digital assets, prevent revenue loss and maintain their reputaion by detecting and mitigation DDoS attacks quickly and effectively. Furthermore, this model has the potential to improve internet access for **individuals** by reducing the impact of DDoS attacks on internet infrastructure and services.

## Tools and Technologies Used

* **Kali Linux**
* **hping3**
* **Metasploitable 2**
* **Wireshark***
* **Google Colab IDE**
* **Python, Pandas Lib**
* **ML Algo:- SVM(Support Vector Machine)**

## Methodology



![Flowchart](https://user-images.githubusercontent.com/97841784/221419166-2c22e2b8-9220-445c-a94f-301a38da00e4.png)

## Dataset

The dataset used in this project is a collection of network traffic data captured during simulated DDoS attacks. 
The data was captured using Wireshark, a popular network protocol analyzer tool. The dataset contains various 
features such as packet size, protocol type, source and destination IP addresses, timestamp, destination port,Info.

## DDoS Attack Launching

#### Normal User Case:

#### Attacker Case:
![tcp_syn flood attack](https://user-images.githubusercontent.com/97841784/222155170-1c818fea-8984-4dce-87f6-5fc37baf68dc.jpg)


###### I used the hping3 command-line tool to launch a TCP SYN flood attack, which is a type of DDoS attack, to the target IP address by sending a massive amount of fake requests/packets using a spoofed IP address. Before launching the attack, I analyzed the packets in Wireshark. After launching the attack, the target server would not work.


![Inked7th_12_LI](https://user-images.githubusercontent.com/97841784/222158124-c46e186d-90ad-4905-8ae6-53ebea50ddcc.jpg)
                    
                   **Here You see that, it's shown connection timeout**
                   
* Then our important work is creating dataset from wireshark that captured.
* for that need to convert into "**.csv**" format using wireshark







