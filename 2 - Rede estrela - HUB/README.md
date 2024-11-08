# Rede estrela com hub

Em uma rede estrela com hub, todos os dispositivos estão conectados a um único dispositivo central, o hub, que age como ponto de concentração do tráfego de dados.

O hub recebe dados de um dispositivo e os retransmite para todos os outros dispositivos conectados a ele, exceto para o dispositivo que enviou.

O hub não distingue o destinatário dos dados, resultando em tráfego desnecessário e diminuindo a eficiência da rede, principalmente em redes de grande porte.

Desta forma, é cada vez mais raro ver uma rede que ainda utiliza hub.

## Configuração da rede

Neste caso, a rede é composta apenas por 2 computadores, ligados por um cabo cross-over.

O cabo cross-over é projetado para conectar diretamente dispositivos da mesma categoria, como:

- Computador a computador;
- Switch a switch;
- Roteador a roteador;
- Etc.

A rede é /24, e os computadores foram setados com os seguintes endereços:

- PC0 = 192.168.0.1
- PC1 = 192.168.0.2
