<div align="center">
  <img src="https://github.com/gabrielceravoloo/Aprendendo-Redes/blob/main/Imagens/Banner.png" alt="Capa do Repositorio"> <!-- Adicionar a nova capa -->
</div>

<br>

![Status](http://img.shields.io/static/v1?label=STATUS&message=ESTUDANDO&color=yellow&style=for-the-badge)

## 📝 Descrição sobre o repositório: 

Este repositório foi criado para registrar meus estudos sobre **Rede de Computadores**, com o objetivo de não só me ajudar a fixar melhor meus aprendizados sobre o assunto, mas também ajudar aqueles que procuram entender mais sobre o tema. Nele, além de tópicos sobre a matéria, também abordei alguns exercícios realizados no software [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer), tambem resaltei algumas curiosidades que descobri durante os estudos, trazendo assim uma leitura mais tranquila e interresante 🤓

<hr>

## 🌐 Oque é rede de computadores?

<!-- INICIO -->

Uma rede de computadores é um conjunto de dispositivos interligados entre si por algum tipo de conexão, seja com ou sem fio. O principal objetivo de uma rede é permitir o compartilhamento de recursos e informações entre dispositivos.

<div align="center">
  <img src="https://github.com/gabrielceravoloo/Aprendendo-Redes/blob/main/Imagens/Redes.jpeg" alt="Imagem Ilustrativa sobre a tecnologia NFC">
</div>

No nosso dia a dia, utilizamos redes de computadores o tempo todo, muitas vezes sem perceber. Um exemplo simples é quando sacamos dinheiro em um caixa eletrônico. Ao inserir o cartão e solicitar um saque, o caixa eletrônico se conecta ao sistema do banco para verificar suas informações bancárias e confirmar se há saldo suficiente. Se tudo estiver certo, a transação é autorizada, e o dinheiro é liberado. 

<!-- Adicionar introdução sobre oque é rede de computadores -->

## 🗂️ Classificações de redes quanto à abrangência

### NFC (Near Field Communication)

O NFC, ou Comunicação por Campo Próximo, é uma tecnologia que permite a troca de informações sem fio entre dispositivos próximos uns dos outros. Essa comunicação ocorre a uma distância de apenas alguns centímetros e geralmente utiliza a tecnologia chamada **RFID (Identificação por Radiofrequência)**.

No cotidiano, podemos encontrar essa tecnologia em cartões de crédito, cartões de acesso para ônibus, fechaduras eletrônicas, entre outros. Embora o formato de cartão seja o mais conhecido, a tecnologia NFC também pode ser incorporada em outros dispositivos, como smartphones mais recentes, que a utilizam tanto para pagamentos quanto para a transmissão de dados para outros dispositivos compatíveis.

<div align="center">
  <img src="https://github.com/gabrielceravoloo/Aprendendo-Redes/blob/main/Imagens/NFC.jpeg" alt="Imagem Ilustrativa sobre a tecnologia NFC">
</div>

<hr>

### BAN (Body Area Network)

O BAN, ou Rede de Área Corporal, é uma tecnologia utilizada principalmente em aplicações na área da saúde. Nessa rede, os sensores distribuídos pelo seu corpo se comunicam com dispositivos eletrônicos, que podem estar fixados ao corpo, como smartwatches, ou posicionados próximos a ele, como sensores de batimentos cardíacos.

<!--[ Adicionar uma imagem sobre o BAN ] -->

<hr>

<!-- CONTINUAR

### PAN (Personal Area Network)
### WPAN (Wireless Personal Area Network)
### NAN (Near-me Area Network)
### LAN (Local Area Network)
### WLAN (Wireless Local Area Network)
### HAN (Home Area Network)
### SAN (Storage Area Network)
### CAN (Campus Area Network)
### MAN (Metropolitan Area Network)
### WAN (Wide Area Network)
### GAN (Global Area Network)

### Nuvem
### IAN (Internet Area Network)

### Internet
### WWW (World Wide Web)

<!-- Adicionar uma explicação para diferenciar WEB de Internet -->

<!-- Assuntos antigos que devem ser arrumados para uma melhor compreensão

✔

## Tipos de Redes

| **Tipo de Rede** | **Descrição**                                            | **Exemplo de Uso**                                  |
|------------------|----------------------------------------------------------|-----------------------------------------------------|
| **LAN (Local Area Network)** | Rede local que conecta dispositivos em uma área geográfica limitada, como uma casa, escritório ou campus | Conexão de computadores em um escritório           |
| **MAN (Metropolitan Area Network)** | Rede que cobre uma área maior que uma LAN, geralmente uma cidade ou um campus universitário | Conexão entre diferentes escritórios em uma cidade  |
| **WAN (Wide Area Network)** | Rede que abrange grandes distâncias geográficas, conectando redes locais em diferentes regiões ou países | A Internet é o exemplo mais comum de WAN           |
| **PAN (Personal Area Network)** | Rede de curto alcance, geralmente usada para conectar dispositivos pessoais como smartphones, tablets e laptops | Conexão Bluetooth entre um smartphone e um fone de ouvido |
| **VLAN (Virtual Local Area Network)** | Rede local virtual que agrupa dispositivos em uma rede lógica, independentemente de sua localização física | Segregação de tráfego de diferentes departamentos em uma empresa |
| **WLAN (Wireless Local Area Network)** | Rede local que utiliza tecnologia sem fio para conectar dispositivos | Conexão Wi-Fi em casa ou em um café                |
| **CAN (Campus Area Network)** | Rede que conecta várias LANs em um campus, como uma universidade. | Conexão entre vários prédios de uma universidade    |
| **SAN (Storage Area Network)** | Rede especializada para conectar dispositivos de armazenamento, como servidores e unidades de disco, permitindo acesso eficiente a dados | Armazenamento em rede para servidores de dados      |
| **GAN (Global Area Network)** | Rede que cobre uma área geográfica ampla, geralmente conectando várias WANs. | Conexão de várias redes em diferentes continentes   |

<div align="center">

## Tipos de Cabos de Rede </h1>

<br>

### Cabo Direto (Para equipamentos diferentes)
![Cabo Direto](http://convexnet.com.br/wp-content/uploads/2017/07/cabo_crossover2.jpg)

### Cabo Cross-Over (Para equipamentos iguais)
![Cabo Cross-Over](https://convexnet.com.br/wp-content/uploads/2017/07/cabo_crossover1.jpg)

</div>

## Protocolos de Rede

- **ICMP (Internet Control Message Protocol)**: Protocolo usado para enviar mensagens de erro e informações operacionais
- **CSMA-CD (Carrier Sense Multiple Access with Collision Detection)**: Protocolo de controle de acesso ao meio para redes Ethernet
- **DHCP (Dynamic Host Configuration Protocol)**: Protocolo usado para atribuição dinâmica de endereços IP a dispositivos em uma rede

## Funcionalidades utilizadas em redes de computadores

-**APIPA (Automatic Private IP Addressing)**: Mecanismo que permite a dispositivos em uma rede local atribuírem a si mesmos quando não conseguem obter um endereço IP de um servidor DHCP

## Topologias de Rede

- **Topologia Estrela**: Um equipamento central (como um switch ou hub) interliga todos os dispositivos na rede
- **Topologia Anel**: Os dispositivos são conectados em um anel fechado, onde cada dispositivo tem exatamente dois vizinhos
- **Topologia Barramento**: Todos os dispositivos são conectados a um único cabo central
- **Topologia Hierárquica**: os dispositivos são organizados em uma estrutura em camadas, onde os níveis superiores controlam os níveis inferiores

## Endereços IP Especiais

| **Endereço IP**       | **Descrição**                    | **Função**                                                                                     |
|-----------------------|----------------------------------|------------------------------------------------------------------------------------------------|
| **192.168.1.0**       | Endereço de Rede                 | Identifica a própria rede. Não pode ser atribuído a nenhum dispositivo final                   |
| **192.168.1.1**       | Gateway Padrão (usualmente)      | Usado pelo roteador ou gateway para acesso à internet ou outras redes                          |
| **192.168.1.2 - 192.168.1.253** | Endereços Utilizáveis para Hosts | Endereços disponíveis para atribuição a dispositivos finais (hosts) na rede                    |
| **192.168.1.254**     | Último Endereço de Host Utilizável | Geralmente o último endereço IP disponível para atribuição a dispositivos finais na rede       |
| **192.168.1.255**     | Endereço de Broadcast            | Usado para enviar pacotes de broadcast para todos os dispositivos na rede. Não pode ser atribuído a nenhum dispositivo final |



