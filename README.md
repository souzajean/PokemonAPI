# PokemonAPI
SAP BTP CPI - PokemonAPI

![Capa](imagens/capa-linkedin.png)

📌 Descrição do iFlow – Integração com API Pokémon

Este iFlow tem como objetivo consumir dados da API pública do Pokémon, transformar e validar as informações retornadas, direcionando o processamento conforme o Pokémon selecionado.

🔄 Fluxo de Processamento

Consumo da API Pokémon
O iFlow realiza uma chamada HTTP à API pública do Pokémon para obter os dados do Pokémon com base no ID informado.

Conversão de Formato (JSON → XML)
A resposta da API, originalmente em formato JSON, é convertida para XML, permitindo melhor manipulação dos dados dentro do SAP CPI.

Definição de Propriedades do Pokémon
Após a conversão, o iFlow extrai informações relevantes (como ID ou nome do Pokémon) e as armazena em propriedades da mensagem para uso posterior no fluxo.

Roteamento por Condição (Router)
O iFlow avalia se o Pokémon retornado corresponde ao Pokémon previamente definido como Pokémon escolhido:

✅ Se for o Pokémon selecionado: o fluxo segue pelo caminho principal de sucesso.

❌ Caso contrário: o processamento é direcionado para o fluxo padrão (default).

Tratamento conforme o Resultado
Cada rota pode executar ações específicas, como retorno da mensagem, log, transformação adicional ou tratamento alternativo.

🎯 Objetivo do iFlow

Garantir que apenas o Pokémon previamente definido seja processado pelo fluxo principal, permitindo validação, controle e direcionamento lógico das mensagens recebidas da API.


📊 Exemplo Prático do Fluxo

### Criando nosso Iflow
![Fluxo](imagens/Screenshot_1.png)

### Adicionando o Artefato do Integration Flow
![Fluxo](imagens/Screenshot_2.png)

### Adicionando o nome do Integration Flow
![Fluxo](imagens/Screenshot_3.png)

### Editando nosso Iflow
![Fluxo](imagens/Screenshot_4.png)

### Adicionar o HTTPS para o Sender para o Start
![Fluxo](imagens/Screenshot_5.png)

### 
![Fluxo](imagens/Screenshot_6.png)

### 
![Fluxo](imagens/Screenshot_7.png)

### 
![Fluxo](imagens/Screenshot_8.png)

### 
![Fluxo](imagens/Screenshot_9.png)

### 
![Fluxo](imagens/Screenshot_10.png)

### 
![Fluxo](imagens/Screenshot_11.png)

### 
![Fluxo](imagens/Screenshot_12.png)


### 
![Fluxo](imagens/Screenshot_13.png)

### 
![Fluxo](imagens/Screenshot_14.png)

### 
![Fluxo](imagens/Screenshot_15.png)

### 
![Fluxo](imagens/Screenshot_16.png)

### 
![Fluxo](imagens/Screenshot_17.png)

### 
![Fluxo](imagens/Screenshot_18.png)

### 
![Fluxo](imagens/Screenshot_19.png)

### 
![Fluxo](imagens/Screenshot_20.png)


### 
![Fluxo](imagens/Screenshot_21.png)


### 
![Fluxo](imagens/Screenshot_22.png)


### 
![Fluxo](imagens/Screenshot_23.png)


### 
![Fluxo](imagens/Screenshot_24.png)


### 
![Fluxo](imagens/Screenshot_25.png)


### 
![Fluxo](imagens/Screenshot_26.png)

### 
![Fluxo](imagens/Screenshot_27.png)

### 
![Fluxo](imagens/Screenshot_28.png)


### 
![Fluxo](imagens/Screenshot_29.png)


### 
![Fluxo](imagens/Screenshot_30.png)


### 
![Fluxo](imagens/Screenshot_31.png)


### 
![Fluxo](imagens/Screenshot_32.png)


### 
![Fluxo](imagens/Screenshot_33.png)


### 
![Fluxo](imagens/Screenshot_34.png)

### 
![Fluxo](imagens/Screenshot_35.png)


### Configuração no Postman
Adicionar a URL do Endpoint
![Fluxo](imagens/Screenshot_36.png)





## 📦 Exemplo prático – iFlow para baixar

📦 [Download do iFlow – Package/PokemonAPI/Package/Integracao_com_API_Pokemon.zip](Package/PokemonAPI/Package/Integracao_com_API_Pokemon.zip)



> O arquivo pode ser importado diretamente no SAP Integration Suite (CPI).

