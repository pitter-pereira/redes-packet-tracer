# 5 - Rede com hub vs Rede com switch

Uma rede baseada em hub e outra utilizando switch apresentam diferenças significativas em desempenho e eficiência, como pode ser visto no gif abaixo:

![hubxswitch-live](https://github.com/user-attachments/assets/7004338b-978c-4a5b-8f61-1896317b642d)

O hub é um dispositivo simples que apenas retransmite os dados recebidos para todas as portas, sem distinção de destino. Isso gera mais colisões, reduz a velocidade da rede e pode comprometer o desempenho conforme o número de dispositivos aumenta.

Já o switch trabalha de forma mais inteligente, encaminhando os pacotes apenas para o dispositivo de destino, baseado no endereço MAC. Isso elimina colisões, melhora a eficiência do tráfego e proporciona maior segurança.

Devido a essas vantagens, o mercado praticamente abandonou o uso de hubs, adotando switches como padrão para redes corporativas e domésticas. 

Atualmente, os switches gerenciáveis, que oferecem configurações avançadas, como VLANs e QoS, estão cada vez mais populares, permitindo maior controle sobre o tráfego de dados.
