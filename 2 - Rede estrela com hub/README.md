# Rede estrela com hub

Em uma rede estrela com hub, todos os dispositivos estão conectados a um único dispositivo central, o hub, que age como ponto de concentração do tráfego de dados.

O hub recebe dados de um dispositivo e os retransmite para todos os outros dispositivos conectados a ele, exceto para o dispositivo que enviou.

O hub não distingue o destinatário dos dados, resultando em tráfego desnecessário e diminuindo a eficiência da rede, principalmente em redes de grande porte.

Desta forma, é cada vez mais raro ver uma rede que ainda utiliza hub.

![hub-live](https://github.com/user-attachments/assets/996d810d-ccc3-46f4-8f47-7229e2efed7d)

## Configuração da rede

Neste caso, a rede é composta apenas por 4 computadores, ligados a um hub central via cabos cross-over.

A rede é /24, e os computadores foram setados com os seguintes endereços:

- PC0 = 192.168.0.2
- PC1 = 192.168.0.3
- PC2 = 192.168.0.4
- PC3 = 192.168.0.5
