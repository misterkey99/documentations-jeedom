# Changelog Lora Payload

# Changelog LoraPayload

>**IMPORTANTE**
>
>Recorde-se que se não há informação sobre a atualização é porque se trata apenas de atualização de documentação, tradução ou texto

# 21/02/2024
- Alterando o nível de log para determinadas informações geradas pelo plugin

- Alterando o tipo de módulo *Milesight EM500 PT100*

- Adicionando ID do pedido ao plugin Lorapayload

- Adicionando configuração *Dragino D20-LB* (propriedades : Bateria, temperatura vermelha, alarme, nível PA8, MOD)


# 19/01/2024
- Adicionando configuração *RAK c15003* (propriedades : Temperatura, Umidade, Pressão, Temperatura2)

- Alterando a configuração *Clima Vicki* (propriedades : GetKeepAlive, KeepAlive, GetDevicePrimaryOperationalMode, DevicePrimaryOperationalMode, GetOperationalMode, OperationalMode, controle proporcional, controle direcional igual, controle integral proporcional, GetControlAlgorithm, ControlAlgorithm, parâmetros de detecção de janela aberta (1.precisão 0), parâmetros de detecção de janela aberta (0.1 precisão))

- Adicionando a coluna *Estado* para exibir o valor dos pedidos de informação

- Adicionando configuração *Citylone SmartLighting-Box 2* (propriedades : stateS1, stateS2, stateS3, stateS4, statusS1, statusS2, statusS3, statusS4, input1, input2, Off Output 1 fixo, On Output 1 fixo, Auto Output 1 fixo, Off Output 2 fixo, On Output 2 fixo, Auto Output 2 fixo, Desligada Saída 3 fixa, Ligada Saída 3 fixa, Saída Automática 3, Desligada Saída 4 fixa, Ligada Saída 4 fixa, Saída Automática 4 fixa, Desligado Tudo fixo, Ligado Tudo fixo, Auto Tudo fixo, DureeOnS1, DureeOnS2, DureeOnS3, DureeOnS4, DureeOffS1 , DureeOffS2, DureeOffS3, DureeOffS4, RSSI, Timestamp GMT, Timestamp Local, Atualização via LNS, Longitude, Latitude, Base de Índice, Índice HCHC, Índice HCHP, ID do Medidor TIC, Opção de Tarifa, Corrente Instantânea Monofásica, Corrente Instantânea Fase1, Fase2 Corrente instantânea, Corrente instantânea Fase3, Corrente instantânea máxima Fase única, Corrente instantânea máxima Fase1, Corrente instantânea máxima Fase2, Corrente instantânea máxima Fase3, Potência ativa máxima, Potência de alarme limite, Potência instantânea aparente, Falha de energia, Estado de mudança de tempo)

- Adicionando configuração *RAK2171* (propriedades : ID da mensagem, ID do aplicativo, ID do dispositivo, bateria, carimbo de data / hora, status de correção do GPS, tipo de carga útil, longitude, latitude, precisão, número inicial do GPS, SOS, nível de alarme)

- Adicionando configuração *Milhas WS50x* (propriedades : Versão, Tensão, Potência de Ativação, Fator Ativo, Consumo de Energia, Corrente, Chave 1, Chave 2, Chave 3)

- Adicionando configuração *Milhas WS51x* (propriedades : Versão, Tensão, Potência de Ativação, Fator Ativo, Consumo de Energia, Corrente, Estado)

- Alterando a configuração *ELA MIO LORA V2* (propriedades : LIGADO 1-2, DESLIGADO 1-2, LIGADO 1-3, DESLIGADO 1-3...)

# 27/03/2023

- Adicionado botão "ChildLockDisable" - Para desativar automaticamente o Child Lock quando o dispositivo estiver offline
- Adicionado um botão "ChildLockUnchange" - Para fazer com que o Child Lock permaneça inalterado quando o dispositivo estiver offline

# 10/03/2023

- Remoção de downlinks duplos quando "Have Confirmation" está marcado
- Adição de um botão "Versão" para ter a versão de Hardware e Software
- Defina o formato de carga útil como "Base64" por padrão
- Adicionada a opção de exibir o equipamento Lora na lista

# 17/01/2023

- Adicionado a capacidade de enviar instruções para os módulos Lorawan

# 10/06/2021

- Documentação do plugin
