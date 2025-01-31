# Changelog jeeZigbee

>**IMPORTANTE**
>
>Se não houver informação sobre a atualização, significa que se trata apenas da atualização da documentação, tradução ou texto.

- Atualização de firmware aprimorada no Luna
- Melhor gerenciamento portuário em Luna
- Simplificando a lista de portas
- Possibilidade de enviar mensagem sobre um subtópico do comando set : arm_mode/modo::armando_ficar
- Correção de bug

# 26/12/2023

- Desligamento aprimorado do daemon zigbee2mqtt
- Correção de bug

# 21/12/2023

- Remoção da noção de instância
- Possibilidade de lançar uma inclusão diretamente em um módulo roteador
- Adicionado suporte para conbee 3
- Adicionado suporte para raspbee 2

# 12/08/2023

- Adicionada opção "Não permitir mensagens se o equipamento não for visto há mais de (s)" (Reservado para usuários avançados)

# 12/05/2023

- Suporte para atualização de firmware zigbee no Luna (beta)
- Suporte para ID lógico longo em comandos
- Possibilidade de criar um comando de atualização (você deve adicionar um comando e digitar action/default e no campo id lógico colocar atualização)
- Possibilidade de adicionar um cron que solicite a atualização dos valores (atenção, nada garante que o módulo realmente os atualizará, deve suportá-lo)
- Corrigido um bug com a versão mais recente do zigbee2mqtt


# 11/06/2023

- Corrigido um bug no gerenciamento de grupo
- Otimização de código
- Corrigidos bugs durante a instalação do plugin (erro 500)

# 22/09/2023

- Possibilidade de escolher a versão do zigbee2mqtt

>**IMPORTANTE**
>
>Para aqueles que estão tendo problemas com um módulo inacessível após atualizações anteriores, você deve restaurar um backup do Jeedom anterior à atualização e refazer a atualização. Peço sinceras desculpas por esse bug que ocorre com alguns de vocês, ele vem de um recurso inesperado do Zigbee2MQTT que não tenho em meus outros laboratórios.

# 20/09/2023

- Corrigido um bug na versão zigbee2mqtt

# 19/09/2023

- Corrigido um bug ao atualizar dependências (Zigbee2MQTT) se você restaurasse o jeedom

# 08/09/2023

- Corrigido um bug que impedia a criação correta de pedidos

# 09/04/2023

- Capacidade de configurar a porta de escuta do zigbee2mqtt
- Corrigido um problema com comandos de tipo de cor
- Correção na geração de comandos que não funcionavam em determinados casos
- Nomenclatura de comando aprimorada
- Possibilidade de caixas Atlas com controladores do tipo Elelabs atualizarem o firmware do jeedom

# 03/07/2023

- Corrigido um problema ao enviar um comando de posicionamento (tipo de obturador)

# 27/06/2023

- Corrigido um problema com a detecção de certos módulos (incluindo profalux)

# 30/05/2023

- Versão inicial
