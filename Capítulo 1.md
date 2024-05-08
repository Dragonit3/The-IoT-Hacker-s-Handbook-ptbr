# Capítulo 1 - Internet das Coisas: Um começo

No mundo da tecnologia de comunicação, dois dos acontecimentos que têm um significado especial são a invenção da ARPANET, uma rede informática que permite aos computadores trocar dados mesmo quando estão geograficamente separados, e o surgimento da Internet das Coisas (IoT). Este último, no entanto, foi um processo evolutivo em vez de um evento único. As primeiras implementações do conceito IoT ocorreram quando alguns estudantes da Universidade Carnegie Mellon encontraram uma maneira de monitorar o número de latas restantes em uma máquina de venda automática, permitindo que os dispositivos se comunicassem com o mundo externo. Eles fizeram isso adicionando um fotossensor ao dispositivo que contaria cada vez que uma lata saísse da máquina de venda automática e, assim, calculava-se o número de latas restantes. Hoje em dia, os dispositivos IoT são capazes de monitorar sua frequência cardíaca e até mesmo controlá-la, se necessário, no caso de um evento adverso. Além disso, alguns dispositivos IoT podem agora servir como fonte de provas durante julgamentos em tribunal, como se viu no final de 2015, quando os dados FitBit de uma mulher foram utilizados num julgamento de homicídio. Outros incidentes incluem o uso de dados de marca-passos e gravações do Amazon Echo em vários julgamentos judiciais. A jornada dos dispositivos IoT, desde um dormitório universitário até a presença dentro dos seres humanos, é fascinante, para dizer o mínimo. 

Kevin Aston, quando mencionou pela primeira vez o termo Internet das Coisas, provavelmente não teria imaginado que esses dispositivos logo ultrapassariam em número toda a população humana. Aston mencionou o 

© Aditya Gupta 2019 
A. Gupta, *The IoT Hacker’s Handbook*, https://doi.org/10.1007/978-1-4842-4300-8_1

---

termo em referência à tecnologia de identificação por radiofrequência (RFID), que estava sendo usada para conectar dispositivos entre si. A definição de IoT mudou desde então, com diferentes organizações dando seu próprio significado ao termo. Qualcomm e Cisco criaram o termo chamadoInternet de tudo(IoE), que alguns acreditam ser uma agenda de marketing. O termo, segundo eles, significa estender o conceito de IoT de ser limitado à comunicação máquina a máquina para máquinas que se comunicam tanto com máquinas quanto com o mundo físico. 
O primeiro vislumbre da IoT atual foi visto em junho de 2000, quando o primeiro refrigerador conectado à Internet, o Internet Digital DIOS, foi revelado pela LG. O refrigerador continha uma tela TFT-LCD de alta qualidade com diversas funcionalidades, incluindo exibir a temperatura dentro do refrigerador, fornecer pontuações de frescor dos itens armazenados e usar a funcionalidade de webcam para monitorar os itens armazenados. O primeiro dispositivo que provavelmente chamou mais atenção da mídia e dos consumidores foi o Nest Learning Thermostat em outubro de 2011. Este dispositivo foi capaz de aprender a programação do usuário para ajustar diferentes temperaturas desejadas em diferentes horários do dia. A aquisição desta empresa de termostatos IoT pelo Google por US$ 3,2 bilhões foi o evento que conscientizou o mundo sobre a próxima revolução na tecnologia. 
Em breve, havia centenas de novas startups a tentar interligar todos os diferentes aspectos do mundo físico aos dispositivos e grandes organizações a criar equipas internas especializadas para criar a sua própria gama de dispositivos IoT a serem lançados no mercado o mais rapidamente possível. Esta corrida para criar novos dispositivos ditos inteligentes nos traz ao presente, onde podemos interagir com nossas smart TVs em casa enquanto tomamos uma xícara de café preparada por uma máquina de café controlada pela Internet e controlamos as luzes pela música tocando. no seu assistente inteligente. A IoT, entretanto, não se limita apenas ao nosso espaço físico. Ele também tem inúmeras aplicações em empresas, lojas de varejo, saúde, indústria, redes elétricas e até mesmo em pesquisas científicas avançadas.

---

Os decisores políticos do mundo digital lutaram com o ritmo acelerado do aumento dos dispositivos IoT e não conseguiram criar controlos de qualidade e regulamentos de segurança rigorosos. Isto mudou apenas recentemente, quando organizações como a GSMA criaram diretrizes de segurança e privacidade para dispositivos IoT, e a Comissão Federal de Comércio (FTC) estabeleceu etapas a serem seguidas para garantir a segurança e a proteção. No entanto, o atraso levou à adoção generalizada de dispositivos IoT em todos os setores verticais e também permitiu que os desenvolvedores ignorassem as considerações de segurança quando se tratava desses dispositivos. Somente após o efeito generalizado da botnet Mirai é que as deficiências de segurança desses dispositivos seriam conhecidas. Mirai era uma botnet que atacava dispositivos IoT, principalmente câmeras conectadas à Internet, verificando o status das portas 23 e 2323 e autenticação de força bruta usando credenciais comuns. Não é novidade que muitas das câmeras IP expostas à Internet tinham telnet disponível com nome de usuário e senha extremamente comuns e fáceis de encontrar. A mesma botnet também foi usada posteriormente para assumir o controle da infraestrutura da Internet da Libéria, bem como da DYN, o que levou a um ataque a vários sites populares, incluindo GitHub, Twitter, Reddit e Netflix. 
Nos últimos dois anos, embora a segurança destes dispositivos tenha melhorado lentamente, ainda não se atingiu um ponto em que estes dispositivos possam ser considerados extremamente seguros de utilizar. Em novembro de 2016, quatro pesquisadores de segurança – Eyal Ronen, Colin O’Flynn, Adi Shamir e Achi-Or Weingarten – criaram um interessante *Proof-of-concept* (PoC) worm que atacou usando drones e assumiu o controle do Philips Hue smart lights de um prédio de escritórios. Mesmo que o ataque tenha sido apenas um PoC, não é exagero pensar que estaríamos vendo ransomware em dispositivos inteligentes semelhante ao WannaCry, pedindo-nos dinheiro para abrir a fechadura da nossa porta ou ligar um marca-passo. Foi determinado que quase todos os dispositivos inteligentes apresentam problemas críticos de segurança e privacidade, incluindo sistemas inteligentes de automação residencial, dispositivos vestíveis, monitores de bebês e até brinquedos sexuais pessoais. Considerando a quantidade de dados íntimos que esses dispositivos coletam, é assustador ver quanta exposição temos a ataques cibernéticos.

---

O aumento de incidentes de segurança em dispositivos IoT também levou a um aumento na demanda por profissionais de segurança IoT, tanto como construtores quanto como disjuntores. Isso permite que as organizações garantam que seus dispositivos estejam protegidos contra vulnerabilidades que invasores mal-intencionados podem usar para comprometer seus sistemas. Além disso, várias empresas começaram a oferecer recompensas por bugs para incentivar os pesquisadores a avaliar a segurança de seus dispositivos IoT, e algumas até enviam dispositivos de hardware gratuitos aos pesquisadores. Nos próximos anos, esta tendência deverá crescer e, com o surgimento das soluções de IoT no mercado, haverá uma maior demanda por profissionais especializados em segurança de IoT na força de trabalho.

## Problemas anteriores de segurança de IoT

A melhor maneira de aprender sobre a segurança desses dispositivos é observar o que aconteceu no passado. Ao aprender sobre os erros de segurança que outros desenvolvedores de produtos cometeram no passado, podemos compreender que tipo de problemas de segurança esperar no produto que estamos avaliando. Embora alguns termos possam parecer desconhecidos aqui, iremos discuti-los em detalhes nos próximos capítulos.

### Termostato Nest

O artigo “Smart Nest Thermostat: A Smart Spy in Your Home”, de Grant Hernandez, Orlando Arias, Daniel Buentello e Yier Jin, menciona algumas das deficiências de segurança do Google Nest que permitiram a instalação de um novo firmware malicioso no dispositivo. Isso foi feito pressionando o botão no Nest por cerca de 10 segundos para acionar a redefinição global. Neste estágio, o dispositivo pode procurar por mídia USB para firmware comunicando-se com o pino sys_boot5. No dispositivo USB, estava presente um firmware malicioso, que o dispositivo usou durante a inicialização.

---

Jason Doyle identificou outra vulnerabilidade nos produtos Nest que envolvia o envio de um valor personalizado nos detalhes do identificador do conjunto de serviços Wi-Fi (SSID) via Bluetooth para o dispositivo de destino, o que travaria o dispositivo e, por fim, o reiniciaria. Isso também permitiria que um ladrão invadisse a casa durante a reinicialização do dispositivo (cerca de 90 segundos) sem ser capturado pela câmera de segurança Nest.

### Casa inteligente Philips

Os dispositivos domésticos da Philips enfrentavam vários problemas de segurança em toda a gama de produtos. Isso inclui o popular worm Philips Hue, construído como PoC pelos pesquisadores de segurança Eyal Ronen, Adi Shamir, Achi-Or Weingarten e Colin O'Flynn. No PoC, eles demonstraram como as chaves de criptografia simétrica embutidas em código usadas pelos dispositivos Philips poderiam ser exploradas para obter controle sobre os dispositivos alvo através do ZigBee. Também incluiu a infecção automática de lâmpadas Philips Hue colocadas próximas umas das outras. 
Em agosto de 2013, Nitesh Dhanjani, pesquisador de segurança, também desenvolveu uma nova técnica para causar apagões permanentes usando uma técnica de ataque de repetição para obter o controle dos dispositivos Philips Hue. Ele descobriu essa vulnerabilidade depois de perceber que os dispositivos inteligentes Philips Hue estavam considerando apenas o MD5 do endereço de controle de acesso à mídia (MAC) como o único parâmetro para validar a autenticidade de uma mensagem. Como o invasor pode aprender facilmente o endereço MAC do host legítimo, ele pode criar um pacote malicioso indicando que veio do host genuíno e com os pacotes de dados com o comando para desligar a lâmpada. Fazer isso continuamente permitiria que o invasor causasse um apagão permanente e o usuário não tivesse outra opção a não ser substituir a lâmpada. 
Philips Hue (e muitos outros dispositivos inteligentes hoje) usa uma tecnologia chamada ZigBee para trocar dados entre os dispositivos, mantendo o consumo de recursos ao mínimo. O mesmo ataque possível ao dispositivo usando pacotes Wi-Fi também seria aplicável ao ZigBee. No caso do ZigBee, tudo o que um invasor precisa fazer é simplesmente capturar o

---

Pacotes ZigBee para uma solicitação legítima e simplesmente reproduzi-los para executar a mesma ação posteriormente e assumir o controle do dispositivo. Também veremos como capturar e reproduzir pacotes ZigBee no Capítulo 10.

### Lâmpada inteligente Lifx

Os dispositivos domésticos inteligentes têm sido um dos alvos de pesquisa mais populares entre a comunidade de segurança. Outro exemplo inicial ocorreu quando Alex Chapman, pesquisador de segurança da empresa Context, descobriu sérias vulnerabilidades de segurança na lâmpada inteligente Lifx, possibilitando que invasores injetassem pacotes maliciosos na rede, obtivessem credenciais Wi-Fi descriptografadas e assumissem o controle. lâmpadas inteligentes sem qualquer autenticação. 
Os dispositivos neste caso estavam se comunicando usando 6LoWPAN, que é outro protocolo de comunicação de rede (assim como o ZigBee) construído sobre 802.15.4. Para detectar os pacotes 6LoWPAN, Chapman usou um Atmel RzRaven com a imagem do firmware Contiki 6LoWPAN, permitindo-lhe observar o tráfego entre os dispositivos. A maior parte da troca de dados confidenciais que ocorre nesta rede foi criptografada, o que fez o produto parecer bastante seguro. 
Uma das coisas mais importantes durante os testes de penetração da IoT é a capacidade de analisar o produto como um todo, em vez de apenas observar um único componente para identificar os problemas de segurança. Isso significa que para descobrir como os pacotes estão sendo criptografados na comunicação por rádio, a resposta provavelmente está no firmware. Uma das técnicas para obter o binário do firmware de um dispositivo é despejá-lo por meio de técnicas de exploração de hardware, como JTAG, que abordamos no Capítulo6. No caso das lâmpadas Lifx, o JTAG deu acesso ao firmware Lifx, que ao ser revertido levou à identificação do tipo de criptografia, que neste caso era Advanced Encyrption Standard (AES), a chave de criptografia, o vetor de inicialização e o modo de bloco usado para criptografia. Como esta informação seria a mesma para todas as lâmpadas inteligentes Lifx, um invasor poderia tomar

---

controle de qualquer lâmpada e invadir o Wi-Fi porque o dispositivo também estava comunicando as credenciais do Wi-Fi pela rede de rádio, que agora poderia ser descriptografada.

### O hack do jipe

O Jeep Hack é provavelmente o hack de IoT mais popular de todos os tempos. Dois pesquisadores de segurança, Dr. Charlie Miller e Chris Valasek, demonstraram em 2015 como eles poderiam assumir e controlar remotamente um Jeep usando vulnerabilidades no sistema Uconnect da Chrysler, resultando no recall de 1,4 milhão de veículos da Chrysler.
O hack completo aproveitou muitas vulnerabilidades diferentes, incluindo extensos esforços na engenharia reversa de vários binários e protocolos individuais. Uma das primeiras vulnerabilidades que possibilitaram o ataque foi o software Uconnect, que permitia que qualquer pessoa se conectasse remotamente a ele por meio de uma conexão celular. A porta 6667 era acessível com autenticação anônima habilitada e estava executando D-Bus sobre IP, que é usado para comunicação entre processos. Após interagir com o D-Bus e obter uma lista de serviços disponíveis, um dos serviços com o nome `NavTrailService` descobriu-se que havia um método de execução que permitia aos pesquisadores executar código arbitrário no dispositivo. Figura1-1 mostra o código de exploração que foi usado para abrir um shell raiz remoto na unidade principal.

![Figura 1-1 Código de exploração](https://github.com/Dragonit3/The-IoT-Hacker-s-Handbook-ptbr/assets/160602980/60c399bb-ce83-4c7d-88c7-a596c2551d5a)

Figura 1-1. Código de exploração. Fonte: Imagem do white paper oficial em http://illmatics.com/Remote%20Car%20Hacking.pdf

---

Uma vez obtida a execução arbitrária do comando, foi possível realizar um movimento lateral e enviar mensagens CAN assumindo o controle dos diversos elementos do veículo, como volante, freios, faróis, etc.

### Belkin Wemo

Belkin Wemo é uma linha de produtos que oferece aos consumidores automação residencial completa. Belkin Wemo é um caso interessante em que os desenvolvedores tomaram precauções para evitar que invasores instalassem firmware malicioso no dispositivo. As atualizações de firmware do Belkin Wemo, no entanto, ocorreram em um canal não criptografado que permitiu que invasores modificassem o pacote binário do firmware durante a atualização. Como medida de proteção, o Belkin Wemo usou um mecanismo de distribuição de firmware criptografado baseado no GNU Privacy Guard (GPG) para que o dispositivo não aceitasse pacotes de firmware maliciosos injetados por um invasor. Essa proteção de segurança foi superada com extrema facilidade porque o dispositivo distribuía a chave de assinatura do firmware junto com o firmware durante o processo de atualização, por meio de um canal não criptografado. Um invasor poderia, portanto, modificar facilmente o pacote, bem como assiná-lo com a chave de assinatura correta, e o dispositivo aceitaria esse firmware com prazer. Esta vulnerabilidade foi descoberta por Mike Davis da IOActive no início de 2014 e recebeu uma pontuação (CVSS) de 10,0 para a criticidade da vulnerabilidade.

Mais tarde, descobriu-se que a Belkin tinha uma série de outros problemas de segurança, incluindo bugs como injeção de SQL e modificação do nome do dispositivo para executar JavaScript arbitrário no smartphone Android do usuário, entre outros. Pesquisa adicional foi realizada no Belkin Wemo pelo grupo FireEye (ver https://www.fireeye.com/blog/threat-research/2016/08/embedded_hardwareha.html), que envolveu a obtenção de acesso ao firmware e console de depuração usando técnicas de hardware Universal Asynchronous Receiver Transmitter (UART) e Serial Peripheral Interface (SPI). Isso também os levou a identificar que

---

através do acesso ao hardware, pode-se facilmente modificar os argumentos do bootloader, tornando inútil a verificação da assinatura do firmware do dispositivo.

### Bomba de insulina

Um pesquisador de segurança chamado Jay Radcliffe, que trabalha para a Rapid7, identificou que alguns dispositivos médicos, especificamente bombas de insulina, podem estar sofrendo de uma vulnerabilidade de ataque baseada em repetição. Radcliffe, ele próprio um diabético tipo 1, começou a pesquisar uma das bombas de insulina mais populares do mercado, o sistema de bomba de insulina OneTouch Ping da Animas, uma subsidiária da Johnson & Johnson. Durante a análise, ele descobriu que a bomba de insulina usava mensagens de texto simples para se comunicar, o que tornava extremamente simples para qualquer pessoa capturar a comunicação, modificar a dosagem de insulina a ser administrada e retransmitir o pacote. Quando ele experimentou o ataque à bomba de insulina OneTouch Ping, funcionou perfeitamente, não havendo como saber a quantidade de insulina que estava sendo administrada durante o ataque.
A vulnerabilidade foi corrigida pelo fornecedor Animas em cinco meses, o que mostra que pelo menos algumas empresas levam a sério os relatórios de segurança e tomam medidas para manter os consumidores seguros.

---

### Fechaduras inteligentes

Um pesquisador de segurança com o nome Jmaxx lançou o desafio de encontrar pontos fracos de segurança no smart lock de agosto, considerado um dos smart locks mais populares e seguros, usado tanto por consumidores em suas casas quanto por anfitriões do Airbnb para permitir que os hóspedes verifiquem conforme sua conveniência. Algumas das vulnerabilidades que ele descobriu incluíam a capacidade dos convidados de se transformarem em administradores, modificando um valor no tráfego de rede de do utilizadorparasuperusuário,firmware não sendo assinado, funcionalidade do aplicativo para ignorar a fixação do Secure Sockets Layer (SSL) (habilitando o modo de depuração) e muito mais.
No mesmo evento, os pesquisadores de segurança Anthony Rose e Ben Ramsey, da empresa de segurança Merculite, fizeram outra apresentação intitulada “Escolhendo fechaduras Bluetooth de baixa energia a um quarto de milha de distância”, na qual

---

eles divulgaram vulnerabilidades em uma série de produtos de fechadura inteligente, incluindo Quicklock Padlock, iBluLock Padlock, Plantraco Phantomlock, Ceomate Bluetooth Smart Doorlock, Elecycle EL797 e EL797G Smart Padlock, Vians Bluetooth Smart Doorlock Okidokey Smart Doorlock, Poly-Control Danalock Doorlock, Mesh Motion Bitlock Cadeado e fechadura inteligente Lagute Sciener.
As vulnerabilidades descobertas por Rose e Ramsey eram de vários tipos, incluindo transmissão da senha em texto não criptografado, suscetibilidade a ataques baseados em repetição, reversão de aplicativos móveis para identificar informações confidenciais, difusão e falsificação de dispositivos. Por exemplo, durante o processo de redefinição da senha, o Quicklock Padlock envia um pacote Bluetooth de baixa energia (BLE) contendo o código de operação, a senha antiga e a nova senha. Como mesmo a autenticação normal ocorre por meio de comunicação de texto não criptografado, um invasor pode usar a senha para configurar uma nova senha para a fechadura da porta, o que tornaria o dispositivo inútil para o proprietário original. A única forma de reiniciá-lo seria retirar a bateria do aparelho após abrir o gabinete. Em outro dispositivo, o Danalock Doorlock, é possível fazer engenharia reversa do aplicativo móvel para identificar o método de criptografia e encontrar a chave de criptografia codificada (“thisisthesecret”) que está sendo usada.

### Hackeando armas e rifles inteligentes

Além dos típicos dispositivos e eletrodomésticos inteligentes, os rifles também estão ficando inteligentes. TrackingPoint, um desses fabricantes de tecnologia de rifle inteligente, oferece um aplicativo móvel para observar a visualização do tiro e ajustá-la. Este aplicativo foi considerado vulnerável a alguns problemas de segurança. Runa Sandvik e Michael Auger identificaram vulnerabilidades no rifle inteligente que lhes permitiram acessar interfaces de programação de aplicativos (APIs) de administração após obter acesso ao dispositivo via UART. Ao explorar a aplicação móvel, um ataque baseado em rede permitiria que um invasor alterasse vários parâmetros, como velocidade do vento, direção, peso do

---

bala e outros parâmetros necessários durante a preparação para disparar a bala. Quando estes parâmetros forem modificados, o atirador não saberá que estas alterações foram feitas.
Outro caso ocorreu quando um pesquisador de segurança chamado Plore conseguiu contornar algumas das restrições de segurança aplicadas pela IP1, uma arma inteligente da Armatix. A arma inteligente exigia que o atirador usasse um relógio especial fornecido pela IP1 para disparar a arma. Para contornar as restrições de segurança, Plore inicialmente realizou uma análise do sinal de rádio e encontrou a frequência exata que a arma usa para se comunicar. Mais tarde, ele percebeu que, usando alguns ímãs, o plugue de metal que trava o plugue de disparo poderia ser manipulado, permitindo ao atirador disparar a bala. Embora o uso de ímãs não seja um ataque de alta tecnologia que você possa considerar necessário para explorar dispositivos IoT, é um ótimo exemplo de como pensar fora da caixa pode ajudá-lo a identificar vulnerabilidades.
Essas vulnerabilidades servem como exemplos para ajudá-lo a compreender vários tipos de vulnerabilidades normalmente encontradas em dispositivos IoT. Posteriormente, abordaremos vários componentes de dispositivos IoT, incluindo técnicas para exploração de hardware, rádio, firmware e software, e você aprenderá mais sobre como usar algumas dessas técnicas nos dispositivos IoT nos quais você está pesquisando ou realizando um pentest.

### Fragmentação na Internet das Coisas

Como a IoT é um campo enorme, com cada empresa querendo obter sua parte no bolo, muitas vezes você se deparará com vários protocolos e estruturas que podem ajudar os desenvolvedores a lançar seus produtos no mercado com mais rapidez.
As estruturas de IoT são várias ofertas prontamente disponíveis que ajudam os desenvolvedores de IoT a acelerar o processo de desenvolvimento de uma solução de dispositivo de IoT, aproveitando a base de código existente e as bibliotecas oferecidas, reduzindo o tempo necessário para colocar o produto no mercado. Embora isso torne as coisas

---

significativamente mais fácil para desenvolvedores e empresas, o outro lado, que muitas vezes é negligenciado, é o quão seguras são essas estruturas. Na verdade, com base em minhas experiências com testes de penetração de dispositivos IoT, os dispositivos que usam várias estruturas eram frequentemente vulneráveis até mesmo a problemas básicos de segurança. As discussões que tive posteriormente com as equipes de produto revelaram que a mentalidade geral é que, se alguém estiver usando uma estrutura popular, muitas vezes ela será considerada segura por design, resultando em descuido na avaliação de sua segurança.
Não importa de que lado você esteja, dos construtores ou dos disjuntores, é importante observar os problemas de segurança do produto, independentemente da estrutura subjacente ou dos conjuntos de protocolos usados. Por exemplo, você frequentemente encontraria desenvolvedores que usam o ZigBee pensando que ele é extremamente seguro, deixando seus produtos vulneráveis a todos os tipos de ataques baseados em rádio.
Neste livro, não nos concentramos necessariamente em qualquer estrutura ou pilha de tecnologia, mas sim em uma abordagem que seja aplicável a qualquer solução de dispositivo IoT, independentemente da arquitetura subjacente. Neste processo, entretanto, também abordamos alguns protocolos populares (por exemplo, ZigBee e BLE) para lhe dar uma ideia de que tipo de vulnerabilidades esperar e como proceder para encontrar esses problemas de segurança.

Algumas das estruturas populares de IoT incluem o seguinte: 
- Eclipse Kura (https://www.eclipse.org/kura/) 
- The Physical Web (https://google.github.io/physical-web/) 
- IBM Bluemix (agora IBM Cloud: https://www.ibm.com/cloud/) 
- Lelylan (http://www.lelylan.com/)
- Thing Speak (https://thingspeak.com/)
- Bug Labs (https://buglabs.net/) 
- The thing system (http://thethingsystem.com/) 
- Open Remote (http://www.openremote.com/)

---

- OpenHAB (https://www.openhab.org/) 
- Eclipse IoT (https://iot.eclipse.org/) 
- Node-Red (https://nodered.org/) 
- Flogo (https://www.flogo.io/) 
- Kaa IoT (https://www.kaaproject.org/) 
- Macchina.io (https://macchina.io/)
- Zetta (http://www.zettajs.org/)
- GE Predix (https://www.ge.com/digital/predix-platform-foundation-digital-industrial-applications) 
- DeviceHive (https://devicehive.com/) 
- Distributed Services Architecture (http://iot-dsa.org/)
- Open Connectivity Foundation (https://openconnectivity.org/)

Essa é apenas uma pequena fração de algumas das estruturas de dispositivos IoT mais populares que você encontrará ao mergulhar no mundo da IoT. Da mesma forma, quando se trata de protocolos de comunicação, existe toda uma gama de protocolos utilizados pelos fabricantes para as suas soluções IoT. Alguns dos protocolos de comunicação mais populares incluem o seguinte:

- Wi-fi 
- BLE 
- Long Term Evolution (LTE) 
- ZigBee 
- ZWave

---

- 6LoWPAN 
- LoRA 
- CoAP 
- SigFox 
- Neul 
- MQTT 
- AMQP 
- Thread
- LoRaWAN

Para avaliar adequadamente a segurança da IoT de um determinado dispositivo ou protocolo de comunicação, você precisará de várias ferramentas de hardware. Por exemplo, o Ubertooth One seria necessário para capturar e analisar pacotes BLE, Atmel RzRaven para ZigBee e assim por diante.
Agora que temos uma boa ideia do que é a IoT e das diversas tecnologias envolvidas, vamos dar uma olhada em alguns dos fatores que levam à insegurança desses dispositivos.

## Razões para vulnerabilidades de segurança IoT

Dado que os dispositivos IoT são extremamente complexos por natureza, é altamente provável que a maioria dos dispositivos que você encontrar tenham problemas de segurança. Se tentarmos entender por que essas vulnerabilidades existem e como você pode evitar esses problemas de segurança durante a construção de um produto, precisaremos nos aprofundar em todo o ciclo de vida de desenvolvimento do produto, desde a fase de concepção até o lançamento do produto. o mercado.
Alguns dos motivos que se destacam como causa de problemas de segurança na construção desses dispositivos são apresentados a seguir.

---

### Falta de conscientização sobre segurança entre os desenvolvedores

Os desenvolvedores que trabalham nesses dispositivos inteligentes geralmente têm menos conhecimento, ou até mesmo desconhecem, as possíveis vulnerabilidades de segurança em dispositivos IoT. Dado que em grandes organizações, os desenvolvedores muitas vezes já estão extremamente ocupados, seria uma ótima idéia realizar reuniões periódicas para discutir como os desenvolvedores podem construir produtos seguros a partir do zero, incluindo táticas acionáveis, como diretrizes rígidas de codificação a serem seguidas e uma lista de verificação de segurança para qualquer amostra de código em que eles trabalhem.

### Falta de uma perspectiva macro

Como veremos no próximo capítulo sobre os vários componentes que constituem um dispositivo IoT, é extremamente fácil para os desenvolvedores ou equipes de segurança esquecerem o fato de que é a interconexão de dispositivos e diversas tecnologias que pode levar a problemas de segurança. Por exemplo, apenas olhar para o aplicativo móvel pode não revelar problemas de segurança, mas se você combinar as descobertas do aplicativo móvel e como funciona a comunicação de rede, poderá descobrir um problema crítico de segurança. É essencial que as equipes de produto invistam mais tempo e esforços analisando toda a arquitetura do dispositivo e realizando modelagem de ameaças.

### Problemas de segurança baseados na cadeia de suprimentos

Uma das causas das vulnerabilidades de segurança em dispositivos IoT é o envolvimento de muitas partes interessadas. Isso significa que muitas vezes você encontraria diferentes componentes de dispositivos sendo fabricados por diferentes fornecedores, tudo sendo montado por outro fornecedor e, finalmente, sendo distribuído por outro. Isto, embora inevitável na maioria das situações, pode levar a problemas de segurança (ou backdoor) que podem ser introduzidos por uma delas, colocando todo o produto em risco.

---

### Uso de estruturas inseguras e bibliotecas de terceiros

No caso de dispositivos IoT ou qualquer outra tecnologia, muitas vezes você encontraria desenvolvedores usando bibliotecas e pacotes existentes e introduzindo amostras de código potencialmente vulneráveis no produto seguro. Embora algumas organizações tenham verificações de qualidade no código escrito pelos desenvolvedores, elas geralmente tendem a ignorar os pacotes que os desenvolvedores estão usando. Isto também é acompanhado pelos requisitos de negócios de uma organização onde a administração exige que os produtos cheguem ao mercado em prazos acelerados (muitas vezes irrealistas), o que coloca a avaliação de segurança do produto em segundo plano. Frequentemente, sua importância não é percebida até que o produto sofra uma violação de segurança.

## Conclusão

Neste capítulo, analisamos o que são os dispositivos IoT, os protocolos e estruturas usados por esses dispositivos inteligentes e os motivos pelos quais esses dispositivos são frequentemente vulneráveis. Também analisamos alguns dos problemas de segurança identificados anteriormente em soluções populares de dispositivos IoT para entender algumas das vulnerabilidades encontradas em dispositivos do mundo real. No próximo capítulo, examinaremos mais profundamente o mapeamento da superfície de ataque desses dispositivos e como podemos identificar e possivelmente evitar riscos de segurança em dispositivos IoT.