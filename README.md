# Azure OpenAI Playground - Resumo (Dio)  
Destinado às atividades do Bootcamp "Microsoft AI for Tech - OpenAI Services".  

## Azure OpenAI Playground  
Esse serviço da Microsoft está disponível dentro do "Azure AI Foundry". Nele, é possível usar e ajustar diversos modelos da OpenAI, como o GPT e DALL-E, sem necessidade de código. O objetivo é oferecer uma interface de experimentação onde o usuário possa explorar as capacidades dos modelos escolhidos e ajustar seus parâmetros como desejar.  
Para usar essa interface, basta ter acesso a uma conta com o serviço "Azure OpenAI".  

### Recursos  
Além da interface intuitiva, o serviço oferece:  
- **Diversos modelos disponíveis para deploy**: Desde GPT-4, GPT-3.5-Turbo e DALL-E até modelos de linguagem usados para embedding de dados (muito utilizados no contexto de RAG), tudo acessível pelo "Catálogo de Modelos".  
- **Ajustes facilitados e outras ferramentas**: No playground, é fácil lidar com os principais parâmetros dos modelos de linguagem (temperature, top-p, max-response, etc.) e até mesmo adicionar dados externos para fazer um RAG simplificado.  

### Parâmetros principais
Os principais parâmetros que afetam o comportamento de um modelo LLM são facilmente ajustáveis pelo playground. Esses parâmetros incluem:  

- **System message**: Enviada no início de uma interação, serve para definir o comportamento e o tom do modelo em uma conversa, estabelecer um contexto inicial, restringir ou expandir o escopo e simular uma personalidade ou papel.  
- **Frequency penalty**: Define a repetição de tokens (palavras). Quanto maior o valor, menor será a repetição.  
- **Presence penalty**: Incentiva o modelo a trazer novas palavras ou conceitos ainda não usados na conversa. Um valor maior significa que o modelo tentará introduzir novos conceitos na resposta.  
- **Temperature**: Controla o "nível de criatividade" para selecionar a próxima palavra. Basicamente, define o quão criativa será a resposta, variando de 0 a 1, indo de respostas previsíveis até improváveis e, em alguns casos, sem sentido.  
- **Top-P**: Em vez de escolher as palavras com base na maior probabilidade (como faz o parâmetro *temperature*), o *top-p* faz com que o modelo faça uma pré-seleção das palavras cuja probabilidade somada atinja o valor definido (entre 0 e 1) para então escolher uma delas aleatoriamente. Um *top-p* maior faz com que mais palavras sejam pré-selecionadas.  

## Conclusão  
O Azure OpenAI Playground é uma ferramenta robusta que permite explorar o funcionamento dos modelos de IA. Ao ajustar os parâmetros adequadamente, é possível gerar desde respostas precisas e formais até textos inovadores e surpreendentes. A interação no playground simplifica o entendimento das capacidades da IA e suas possíveis aplicações em diversos cenários.  



