# Rede estrela com switch

Diferente dos hubs, que simplesmente retransmitem dados para todos os dispositivos da rede, os switches operam na Camada 2 (Enlace) do modelo OSI e utilizam endereços MAC (físico) para encaminhar os pacotes de forma inteligente, reduzindo colisões e otimizando o tráfego.

![switch-live](https://github.com/user-attachments/assets/f16b1f12-68ce-444e-8b43-127f0bf53012)


Características dos Switches:

 - Comutação Inteligente: Encaminha pacotes apenas para o dispositivo de destino, melhorando o desempenho da rede.
 - Aprendizado de Endereços MAC: Mantém uma tabela interna com os endereços MAC dos dispositivos conectados, agilizando a comunicação.
 - Capacidade de Full Duplex: Permite a transmissão e recepção simultânea de dados, eliminando colisões.
 - Gerenciáveis e Não Gerenciáveis: Os switches gerenciáveis oferecem configuração e monitoramento avançado, enquanto os não gerenciáveis funcionam de forma automática.

Vantagens:
 - Melhora no desempenho: A comunicação direcionada reduz congestionamentos e aumenta a velocidade da rede.
 - Segurança aprimorada: Em switches gerenciáveis, é possível configurar VLANs, restringindo o acesso entre dispositivos.
 - Menor colisão de pacotes: Como cada dispositivo recebe pacotes apenas quando necessário, há menor chance de colisões.
 - Escalabilidade: Permite fácil expansão da rede, adicionando novos dispositivos sem impactar significativamente o desempenho.

Desvantagens:
 - Custo maior: Comparado a hubs, switches são mais caros, especialmente os modelos gerenciáveis.
 - Configuração complexa: Em redes grandes, a configuração de VLANs e protocolos de segurança pode exigir conhecimento técnico avançado.
 - Dependência de energia: Como são dispositivos eletrônicos ativos, quedas de energia podem comprometer sua funcionalidade.

Os switches são a espinha dorsal das redes locais modernas, proporcionando comunicação eficiente, segura e escalável. 

Seu uso é essencial para redes que demandam alto desempenho e gerenciamento de tráfego, sendo uma escolha superior em relação a hubs para a maioria dos cenários, corporativos e domésticos.

## Configuração da rede

Neste caso, a rede é composta por 5 dispositivos, conectados via cabo de rede direto (straight-through) a um switch central, que possui configurações padrão, sem autenticação ativada.

A rede é /24, e os aparelhos foram setados com os seguintes endereços:

 - PC0 = 192.168.20.2
 - PC1 = 192.168.20.3
 - PC2 = 192.168.20.4
 - PC3 = 192.168.20.5
 - PC4 = 192.168.20.6
