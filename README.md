                                                    ![Welcome](https://user-images.githubusercontent.com/97841784/222218212-6aa5b278-4bcd-4c00-b404-a421344bfe13.png)
                                

## Hi I'm Akash !!  


Hi, my name is Akash and I am a computer science student. I am also interested in the field of cybersecurity and have been working on this project to develop a model for detecting DDoS attacks. In my free time, I enjoy learning about new technologies and exploring the latest developments in the field of computer science

## Connect With Me

[![Screenshot 2023-03-01 230432](https://user-images.githubusercontent.com/97841784/222218069-91f2f6c2-c7af-4c8d-b828-865ef49843e4.png)
](https://www.linkedin.com/in/akash-chandra-sahu-54016818a/)   


# Detection-Of-DDoS-Attack-Using-Machine-Learning-Model


## Project Overview

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

## 3-Way Handshaking Mechanism
 #### Before went to DDoS Attack, we should know about 3-way handshaking mechanism where user sent the syn packet to the server for communication puposes. 
 * Normal User:
     * --> The client sends a SYN packet to the server.
     * --> The server responds with a SYN-ACK packet to the client.
     * --> The client sends an ACK packet to the server, completing the 3-way handshake and establishing a connection.
 
  ![3-way handshaking](https://user-images.githubusercontent.com/97841784/222208847-f88439b8-7c52-4417-988a-d9207639b38a.png)

     
 * Malicious User:
     
     --> But in this case attacker sent massive amount of fake request by sending SYN packets using spoofed ip address so that server will get busy on sending reply
         and leave it's port open for waiting of ACK from User.
         
         
  ![Spoof 3-way handshak](https://user-images.githubusercontent.com/97841784/222208939-5ac089de-f67a-46d3-a690-0763b47c6a5d.png)


## DDoS Attack Launching

![tcp_syn flood attack](https://user-images.githubusercontent.com/97841784/222155170-1c818fea-8984-4dce-87f6-5fc37baf68dc.jpg)


###### I used the hping3 command-line tool to launch a TCP SYN flood attack, which is a type of DDoS attack, to the target IP address by sending a massive amount of fake requests/packets using a spoofed IP address. Before launching the attack, I analyzed the packets in Wireshark. After launching the attack, the target server would not work.


![Inked7th_12_LI](https://user-images.githubusercontent.com/97841784/222158124-c46e186d-90ad-4905-8ae6-53ebea50ddcc.jpg)
                    
                   **Here You see that, it's shown connection timeout**
                   
* Then our important work is creating dataset from wireshark that captured.
* for that need to convert into "**.csv**" format using wireshark






#### I am always open to feedback and suggestions, and if you have any queries regarding this project or anything related to computer science, please feel free to reach out to me.
