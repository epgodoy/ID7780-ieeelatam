# ID7780-ieeelatam
Arquivos e dados adicionais relacionados ao artigo ID7780 - IEEE Latin America Transactions

Este repositório contém arquivos e dados adicionais referentes ao artigo "Advanced Metering Infrastructure for Industrial Natural Gas Smart Management" (ID7780) do IEEE Latin America Transactions:         
- https://latamt.ieeer9.org/index.php/transactions/article/view/7780              
- https://ieeexplore.ieee.org/document/10255447      

A arquitetura da AMI para gestão inteligente de gás natural em clientes industriais mostrada na Fig. 1 do artigo é composta de quatro elementos: corretor de volume de gás PTZ, hardware eletrônico de aquisição de dados e comunicação, servidor de rede LoRaWAN e plataforma de IoT da ProIoT.
![Figura 1__](https://user-images.githubusercontent.com/31543410/236536649-9b8ee694-8b11-4b07-9478-299f43dd91b5.jpg)

Sobre o módulo desenvolvido - hardware eletrônico de aquisição de dados e comunicação, disponibiliza-se:
- código fonte compilado para o microcontrolador ESP32 da fabricante Espressif
- esquemático do projeto eletrônico
- projeto (layout) da placa de circuito impresso
- projeto para impressora 3D do invólucro

A licença é GPL-3.0. Em caso de uso, cite nosso trabalho.     
E. Camoleze de Araújo, N. C. de Almeida and E. P. Godoy, "Advanced Metering Infrastructure for Industrial Natural Gas Smart Management," in IEEE Latin America Transactions, vol. 21, no. 10, pp. 1081-1087, Oct. 2023, doi: 10.1109/TLA.2023.10255447 
Abstract: One of the challenges within the utilities sector is the development of robust, scalable and low-cost methods for the remote management of customers usage and billing. Considering the advances related to the Internet of Things (IoT), an Advanced Metering Infrastructure (AMI) is the basis for utilities smart management. This AMI bring together the automation of remote metering and communication infrastructures with the processing and analysis of distributed data using advanced techniques and cloud computing. This paper presents the development of an AMI for the smart management of natural gas industrial customers using IoT. The AMI architecture is based on the LoRaWAN communication for remote metering and a cloud-based smart management system including supervisory control, continuous monitoring, anomalies detection and alarm notification. Experimental results shown the LoRaWAN fulfilled the communication requirements for industrial natural gas metering and the smart management system can analyze historical data and detect anomalies in gas consumption.
