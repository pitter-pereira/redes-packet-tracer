# Servidor DHCP

Um servidor DHCP (Dynamic Host Configuration Protocol) é responsável por atribuir dinamicamente endereços IP e outras configurações de rede (como gateway e DNS) para dispositivos em uma rede. Isso elimina a necessidade de configuração manual, facilitando a administração e evitando conflitos de IPs.

Quando um dispositivo se conecta à rede, ele envia uma solicitação DHCP (broadcast). O servidor responde com um IP disponível dentro de um intervalo definido, além de outras configurações essenciais para a comunicação na rede. 

![dhcp-live](https://github.com/user-attachments/assets/fb3db50d-dde2-4da7-b9cf-238b948d7691)

O DHCP é amplamente utilizado em redes corporativas e domésticas, garantindo eficiência e escalabilidade na gestão de endereços IP.

## Configuração da rede

Neste caso, a rede é composta por 5 dispositivos, conectados via cabo de rede direto (straight-through) a um switch central, que possui configurações padrão e que está conectado a um servidor DHCP.

A rede é /24 e seus endereços são distribuídos pelo servidor DHCP em Server0, ficando os endereços a partir de 192.168.100.25, dando uma faixa de IPs iniciais para outros serviços que, por ventura, venham a ser instalados.
