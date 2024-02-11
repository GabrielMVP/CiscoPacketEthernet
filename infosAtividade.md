Para o show da banda de Miguel, será necessário configurar uma rede de computadores. A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro, é fundamental para manter todos informados e verificar se nada está fugindo do controle. O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. Para ajudá-los, você deve usar o Cisco Packet Tracer para criar uma topologia de rede estrela que permita a toda a equipe se comunicar facilmente.

Passos:
1. Definir o cenário
- Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

2. Montar a topologia
- Crie uma nova topologia no Cisco Packet Tracer; 
- Arraste um switch para o centro da área de trabalho; 
- Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.

3. Conectar os dispositivos
- Conecte cada PC a uma porta diferente no switch usando cabos ethernet;
- Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

4. Configurar os endereços IP
- Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP;
- Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.

5. Testar a comunicação
- Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.

- Dados Roteador
- IP = 192.168.0.1 - 255.255.255.0 = /24

- IP PC0 = 192.168.0.2 - 255.255.255.0 = /24
- IP PC1 = 192.168.0.3 - 255.255.255.0 = /24
- IP PC2 = 192.168.0.4 - 255.255.255.0 = /24
- IP PC3 = 192.168.0.5 - 255.255.255.0 = /24

![Captura de tela 2024-02-11 094555](https://github.com/GabrielMVP/CiscoPacketEthernet/assets/38257470/bc73fdf4-172f-406e-ba21-3dd0ab7aa4cd)

![Captura de tela 2024-02-11 094212](https://github.com/GabrielMVP/CiscoPacketEthernet/assets/38257470/0443cf00-b741-497f-b3ce-dcaab892b479)

![Captura de tela 2024-02-11 094238](https://github.com/GabrielMVP/CiscoPacketEthernet/assets/38257470/996bb812-1659-4ccf-921e-517b050b0d09)

![Captura de tela 2024-02-11 094259](https://github.com/GabrielMVP/CiscoPacketEthernet/assets/38257470/67bad4f9-8c00-4806-bba0-75c08917bb6d)
