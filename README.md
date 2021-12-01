# Agro_IoT
Projeto de IoT para irrigação automática de plantas


Este artigo descreve o projeto de automação do processo de irrigação de solo usando um sensor de Solo Higrômetro de humidade (Fig. 3), que através de um módulo wifi NodeMCU ESP8266 faz a leitura das condições de tal solo para enviar, assim que seco, o comando para que o mesmo seja irrigado. O programa apresentará um LED vermelho para quando o solo estiver seco, assim acionando a irrigação, e em condições normais e ideais do solo, apresentará o LED verde. Essas condições tambem são apresentadas em uma especie de Dashboard.



Aqui estão toda a documentação, codigos e o arquivo .ino, que foi desenvolvido no Software Arduino UNO. Para esta automação foi utilizado o módulo Wi-Fi NodeMCU ESP8266, que se conecta com o software MQTT Node-RED, onde estão as configurações do Broker. LEDs vermelho e verde foram colocados para ser um segundo output do status do solo. Sempre que o solo estiver seco, o led vermelho irá acender e a bomba d'água irá ser acionada. Para maiores informações: [link]
