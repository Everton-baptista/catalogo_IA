1. Conceitos Fundamentais

Inteligência Artificial (IA / AI): Campo da computação que cria máquinas capazes de realizar tarefas que exigiriam inteligência humana, como aprender, perceber e decidir. Ex.: um assistente que entende sua pergunta e responde sozinho.
AGI (Inteligência Artificial Geral): IA hipotética com capacidade igual ou superior à humana em qualquer tarefa intelectual. Ex.: um robô que aprende qualquer profissão como uma pessoa aprenderia.
ASI (Superinteligência Artificial): IA que superaria amplamente a inteligência humana em todas as áreas. Ex.: uma mente que resolve problemas que nenhum cientista conseguiria.
IA Fraca (Narrow AI / ANI): IA feita para uma única tarefa específica. Ex.: assistente de voz que só entende comandos simples.
IA Forte: Ideia de uma IA com consciência e compreensão real, como a humana. Ex.: uma máquina que de fato "entende" e sente o que faz.
IA Simbólica (IA Clássica): Abordagem baseada em regras e símbolos lógicos legíveis por humanos. Ex.: "se tem febre e tosse, então pode ser gripe".
Sistema Especialista: Programa que imita um especialista humano usando uma base de regras. Ex.: software que dá um diagnóstico como um médico daria.
Teste de Turing: Teste em que uma máquina "passa" se um humano não distingue suas respostas das de outra pessoa em uma conversa por texto. Ex.: conversar num chat sem saber se do outro lado é robô ou gente.
Sala Chinesa (Argumento de Searle): Argumento de que manipular símbolos seguindo regras não é o mesmo que entender. Ex.: responder em chinês usando um manual, sem saber chinês.
Algoritmo: Sequência de passos ou regras para resolver um problema. Ex.: uma receita de bolo, passo a passo.
Heurística: Atalho prático ("regra de bolso") que dá uma boa resposta rapidamente. Ex.: escolher a fila menor no mercado para ganhar tempo.
Comportamento Emergente: Habilidade inesperada que aparece quando o modelo fica grande o suficiente. Ex.: criança que, de repente, começa a fazer piadas sozinha.
Representação de Conhecimento: Forma de organizar informações para a máquina conseguir raciocinar sobre elas. Ex.: um mapa mental ligando ideias relacionadas.

2. Machine Learning Clássico

Machine Learning (ML / Aprendizado de Máquina): Máquina que aprende com dados, em vez de seguir regras fixas. Ex.: app que aprende suas músicas favoritas com o tempo.
Aprendizado Supervisionado: Treino com exemplos rotulados (entrada + resposta certa). Ex.: mostrar fotos já marcadas como "gato" ou "cachorro".
Aprendizado Não Supervisionado: Encontra padrões em dados sem rótulos. Ex.: separar clientes parecidos sem dizer antes quem é quem.
Aprendizado Semi-supervisionado: Mistura poucos dados rotulados com muitos sem rótulo. Ex.: poucas fotos marcadas e um monte sem marca nenhuma.
Aprendizado Auto-supervisionado: O próprio dado gera os rótulos. Ex.: tampar uma palavra da frase e tentar adivinhar qual é.
Aprendizado por Reforço (RL): Aprende por tentativa e erro, ganhando recompensas. Ex.: cachorro ganhando petisco quando acerta o truque.
Regressão Linear: Prevê um número traçando uma reta nos dados. Ex.: prever o preço de uma casa pelo tamanho dela.
Regressão Logística: Prevê a probabilidade de algo ser sim ou não. Ex.: estimar a chance de um e-mail ser spam.
Classificação: Coloca cada dado em uma categoria. Ex.: marcar uma foto como "dia" ou "noite".
Clustering (Agrupamento): Junta itens parecidos em grupos automaticamente. Ex.: organizar fotos juntando os rostos parecidos.
Árvore de Decisão: Série de perguntas sim/não que leva a uma resposta. Ex.: jogo de adivinhação: "tem pelos? voa?".
Random Forest (Floresta Aleatória): Muitas árvores de decisão votando juntas. Ex.: pedir o palpite de vários amigos e seguir a maioria.
SVM (Máquina de Vetores de Suporte): Traça a melhor linha que separa dois grupos. Ex.: desenhar a cerca ideal entre gatos e cães.
KNN (K-Vizinhos Mais Próximos): Classifica olhando os exemplos mais próximos. Ex.: você costuma se parecer com seus vizinhos de mesa.
Naive Bayes: Classificador baseado em probabilidade de cada característica. Ex.: prever spam pela frequência de certas palavras.
K-Means: Agrupa os dados em K grupos por proximidade. Ex.: dividir a turma em 3 mesas conforme o gosto.
PCA (Análise de Componentes Principais): Reduz o número de variáveis mantendo o essencial. Ex.: resumir um livro mantendo só a ideia central.
Gradient Boosting: Constrói modelos em sequência, cada um corrigindo o erro do anterior. Ex.: refazer a prova várias vezes, corrigindo os erros a cada vez.
XGBoost: Versão popular, rápida e eficiente do gradient boosting. Ex.: o "motor turbinado" do boosting.
Ensemble (Comitê): Combina vários modelos para acertar mais. Ex.: um júri decidindo em vez de um único juiz.
Bagging: Treina modelos em paralelo com amostras diferentes e faz a média. Ex.: várias pesquisas independentes somadas no fim.
Boosting: Treina modelos em série, cada um focando no que o anterior errou. Ex.: aluno que melhora a cada simulado.
Stacking: Empilha modelos e usa um modelo final para combinar as saídas. Ex.: chefe que decide ouvindo vários consultores.
Feature Engineering (Engenharia de Atributos): Criar e escolher boas variáveis de entrada. Ex.: transformar "data de nascimento" em "idade".
Feature (Atributo / Variável): Cada característica usada como entrada do modelo. Ex.: altura e peso para prever o tamanho da roupa.
AutoML: Ferramentas que automatizam a criação de modelos. Ex.: um robô que monta o modelo praticamente sozinho.
Modelo Paramétrico vs. Não Paramétrico: O primeiro tem número fixo de parâmetros; o segundo cresce com os dados. Ex.: uma fórmula fixa vs. um caderno que vai aumentando.

3. Deep Learning e Redes Neurais

Rede Neural: Sistema inspirado no cérebro, com "neurônios" conectados em camadas. Ex.: uma rede de pessoas passando recados adiante.
Perceptron: O neurônio artificial mais simples. Ex.: um interruptor que liga se o sinal for forte o bastante.
MLP (Perceptron Multicamadas): Rede neural com várias camadas de neurônios. Ex.: várias fileiras de interruptores ligados em sequência.
Deep Learning (Aprendizado Profundo): Redes neurais com muitas camadas. Ex.: uma fábrica com muitas etapas refinando o produto.
CNN (Rede Neural Convolucional): Rede ótima para imagens; detecta bordas, texturas e formas. Ex.: um olho que reconhece as partes da figura aos poucos.
RNN (Rede Neural Recorrente): Rede para sequências, com memória do que veio antes. Ex.: ler uma frase lembrando das palavras anteriores.
LSTM (Memória de Longo e Curto Prazo): RNN que lembra informações importantes por mais tempo. Ex.: um caderno que guarda só o que realmente importa.
GRU (Unidade Recorrente com Portas): Versão mais simples e leve da LSTM. Ex.: um caderninho enxuto, só com o essencial.
GAN (Rede Adversária Generativa): Duas redes competindo: uma cria, a outra critica. Ex.: um falsificador e um detetive que melhoram um ao outro.
Autoencoder: Rede que comprime e depois reconstrói os dados. Ex.: zipar e deszipar um arquivo.
VAE (Autoencoder Variacional): Autoencoder que também gera dados novos. Ex.: criar rostos novos parecidos com os reais.
Transformer: Arquitetura que usa atenção e processa tudo em paralelo; é a base dos LLMs modernos. Ex.: ler a frase inteira de uma vez, focando no que importa.
Mecanismo de Atenção: Permite ao modelo focar nas partes mais relevantes da entrada. Ex.: grifar as palavras-chave de um texto.
Self-Attention (Autoatenção): Cada palavra "olha" todas as outras da mesma frase. Ex.: ver como cada palavra se relaciona com as demais.
Backpropagation (Retropropagação): Algoritmo que ajusta os pesos corrigindo os erros de trás para frente. Ex.: corrigir a receita depois de provar o resultado.
Gradiente Descendente: Método que ajusta o modelo "descendo o morro" do erro. Ex.: descer a montanha sempre pelo caminho mais inclinado.
Função de Ativação: Decide se e quanto o neurônio "dispara". Ex.: uma torneira que abre conforme a pressão da água.
ReLU: Ativação que zera valores negativos e mantém os positivos. Ex.: deixar passar só a água quente.
Sigmoid: Ativação que comprime qualquer valor entre 0 e 1. Ex.: um termômetro de "quase não" a "quase sim".
Tanh: Como a sigmoid, mas variando entre -1 e 1. Ex.: uma régua de "muito não" a "muito sim".
Softmax: Transforma números em probabilidades que somam 100%. Ex.: dividir 100% de chance entre as opções possíveis.
GELU: Ativação suave muito usada em transformers modernos. Ex.: uma torneira que abre de forma gradual.
Função de Perda (Loss): Mede o quanto o modelo está errando. Ex.: um placar de erros que se quer reduzir.
Dropout: Desliga neurônios aleatoriamente durante o treino para evitar "decoreba". Introduzido por Srivastava, Hinton e colaboradores (JMLR, 2014), funciona como se a rede treinasse muitas sub-redes diferentes. Ex.: estudar em grupo com alguns colegas faltando, para não depender só de um. JMLR
Batch Normalization: Normaliza os dados entre as camadas para acelerar e estabilizar o treino (Ioffe e Szegedy, ICML 2015). Ex.: padronizar a temperatura em cada etapa da cozinha. Proceedings of Machine Learning Research
Embedding (Vetor de Representação): Representa palavras ou itens como números que captam o significado. Ex.: colocar palavras parecidas pertinho no mapa.
Camada Oculta: Camada intermediária entre a entrada e a saída da rede. Ex.: os bastidores onde o processamento acontece.

4. LLMs e IA Generativa

LLM (Grande Modelo de Linguagem): Modelo treinado em enormes quantidades de texto para entender e gerar linguagem. Ex.: o assistente que escreve e responde como uma pessoa.
IA Generativa: IA que cria conteúdo novo (texto, imagem, áudio, vídeo). Ex.: app que faz um desenho a partir de uma frase.
GPT (Transformer Pré-treinado Generativo): Família de LLMs que gera texto. Ex.: o motor por trás do ChatGPT.
BERT: Modelo que entende texto olhando o contexto nos dois sentidos. Ex.: ler a frase inteira antes de interpretar cada palavra.
Modelo de Fundação (Foundation Model): Modelo grande e geral que serve de base para muitas tarefas. Ex.: uma massa-base que vira vários tipos de pão.
Token: Pedaço de texto (uma palavra ou parte dela) que o modelo processa. Ex.: cortar a frase em peças de Lego.
Tokenização: Processo de quebrar o texto em tokens. Ex.: picar o texto em pedacinhos.
Fine-tuning (Ajuste Fino): Re-treinar um modelo pronto para uma tarefa específica. Ex.: dar uma aula extra de um assunto a quem já sabe muito.
Instruction Tuning: Ajuste para o modelo seguir bem as instruções. Ex.: ensinar a obedecer pedidos diretos.
RLHF (Aprendizado por Reforço com Feedback Humano): Humanos avaliam e comparam respostas; isso treina um "modelo de recompensa" que orienta o ajuste do LLM (Rafailov et al., 2023). Ex.: dar joinha ou joia para ensinar o que é uma boa resposta.
RLAIF (Reforço com Feedback de IA): Outra IA fornece o feedback no lugar dos humanos, para ganhar escala. Ex.: um robô-professor corrigindo o robô-aluno.
DPO (Otimização Direta de Preferência): Alinha o modelo diretamente pelas preferências, sem precisar de um modelo de recompensa separado nem de RL — mais simples e estável que o RLHF (Rafailov et al., NeurIPS 2023). Ex.: aprender o gosto da pessoa direto das escolhas que ela faz.
Constitutional AI: Método da Anthropic que treina o modelo guiado por uma lista de princípios escritos (uma "constituição"). Ex.: um robô que segue um código de conduta próprio. Anthropic
RAG (Geração Aumentada por Recuperação): Busca informação externa e a usa como contexto para responder. Ex.: consultar a apostila antes de responder à prova.
Prompt: A instrução ou pergunta dada ao modelo. Ex.: o pedido que você digita na conversa.
Prompt Engineering (Engenharia de Prompt): A arte de escrever bons prompts. Ex.: aprender a perguntar do jeito certo para obter respostas melhores.
In-context Learning: Aprender pela própria conversa, com exemplos dentro do prompt. Ex.: mostrar 2 exemplos e pedir o terceiro.
Zero-shot: Resolver a tarefa sem nenhum exemplo. Ex.: responder de primeira, sem dica.
Few-shot: Resolver com poucos exemplos no prompt. Ex.: dar 3 exemplos antes de pedir o resultado.
Chain-of-Thought (Cadeia de Pensamento): Pedir que o modelo raciocine passo a passo. Ex.: mostrar a conta toda antes de dar o resultado.
Janela de Contexto: Quantidade de texto que o modelo consegue "enxergar" de uma vez. Ex.: o tamanho da mesa onde cabem os papéis.
Temperatura: Controla o quanto a resposta é criativa ou previsível (0 = determinística; valores altos = mais variada). Ex.: um botão que vai de "sério" a "criativo".
Top-k: Limita a escolha às k palavras mais prováveis. Ex.: escolher só entre as 5 melhores opções.
Top-p (Nucleus Sampling): Escolhe entre as palavras que, somadas, atingem certa probabilidade. Ex.: considerar só as opções que somam 90% de chance.
Alucinação: Quando a IA inventa algo falso que parece verdadeiro. Ex.: citar um livro que não existe com toda a confiança.
Modelo de Difusão: Gera imagens partindo de ruído e "limpando-o" aos poucos. Ex.: revelar uma foto embaçada até ela ficar nítida.
Text-to-Image: Cria uma imagem a partir de um texto. Ex.: digitar "gato astronauta" e receber o desenho.
Text-to-Speech (TTS): Converte texto em voz. Ex.: um app que lê o texto em voz alta para você.
Multimodal: Modelo que lida com vários tipos de dado ao mesmo tempo (texto, imagem, áudio). Ex.: ver uma foto e descrevê-la em palavras.
MoE (Mistura de Especialistas): Arquitetura que ativa apenas parte da rede (alguns "especialistas") para cada entrada, mantendo muitos parâmetros totais mas poucos ativos por vez. Ex.: chamar só o médico certo para cada caso, em vez do hospital inteiro. MindStudio
Quantização: Reduz a precisão dos números do modelo (ex.: de 32 para 4 ou 8 bits) para ele ficar mais leve e rápido. Ex.: arredondar os preços para facilitar a conta de cabeça.
Destilação (Knowledge Distillation): Um modelo pequeno "aluno" aprende imitando um grande "professor" (Hinton, Vinyals e Dean, 2015). Ex.: o resumo do professor que cabe direitinho no caderno. Intellabs
LoRA (Adaptação de Baixo Posto): Ajusta o modelo treinando pequenas matrizes extras, sem mexer no resto. Ex.: colar adesivos no carro em vez de repintá-lo inteiro.
QLoRA: LoRA combinado com quantização em 4 bits para economizar memória. Ex.: o LoRA na versão econômica.
PEFT (Ajuste Fino Eficiente em Parâmetros): Família de técnicas que treinam pouquíssimos parâmetros (inclui LoRA, prefix/prompt tuning). Ex.: trocar só as peças realmente necessárias.
Modelo de Raciocínio: LLM que "pensa" mais antes de responder, gastando mais cálculo na hora. Ex.: o aluno que faz um rascunho antes de entregar a prova.
Test-time Compute: Gastar mais processamento no momento da resposta para acertar mais. Ex.: pensar mais tempo numa questão difícil.
Chatbot: Programa que conversa em linguagem natural. Ex.: o atendente virtual de um site.
Parâmetros: Os "pesos" ajustáveis que guardam o que o modelo aprendeu. Ex.: bilhões de botõezinhos regulados durante o treino.

5. Agentes de IA

Agente de IA: Sistema que percebe o ambiente, decide e age sozinho para atingir um objetivo. Ex.: um assistente que marca sua consulta sem você precisar fazer cada passo.
Agentic AI: Abordagem em que a IA age com autonomia, em várias etapas encadeadas. Ex.: um robô que planeja e executa a viagem inteira.
Sistema Multiagente: Vários agentes cooperando entre si. Ex.: uma equipe de robôs dividindo as tarefas.
ReAct (Raciocinar + Agir): Padrão em que o agente alterna passos de pensar e de usar ferramentas. Ex.: pensar, pesquisar, pensar de novo, agir.
Tool Use / Function Calling (Uso de Ferramentas): O modelo chama ferramentas externas (APIs) para executar ações. Ex.: pedir à calculadora para fazer a conta em vez de chutar.
Orquestração de Agentes: Coordenar vários agentes e etapas. Ex.: o maestro regendo toda a orquestra.
Memória de Agente: Onde o agente guarda contexto e experiências (curto e longo prazo). Ex.: o caderno de anotações do assistente.
Planejamento: O agente quebra o objetivo grande em passos menores. Ex.: fazer a lista de tarefas antes de começar.
Padrão Supervisor: Um agente líder distribui tarefas a subagentes especialistas. Ex.: o chefe delegando para a equipe.
MCP (Protocolo de Contexto de Modelo): Padrão aberto que conecta modelos de IA a dados e ferramentas externas, descrito como uma "tomada USB-C para IA". Foi lançado e disponibilizado em código aberto pela Anthropic em 25 de novembro de 2024 (criado por David Soria Parra e Justin Spahr-Summers); no anúncio oficial, a Anthropic descreveu-o como "a new standard for connecting AI assistants to the systems where data lives". Sua adoção cresceu rápido: em 9 de dezembro de 2025 a Anthropic informava mais de 10.000 servidores públicos ativos e mais de 97 milhões de downloads mensais de SDK. Ex.: uma tomada universal que liga qualquer IA a qualquer fonte de dados. Anthropic
A2A (Agent2Agent): Protocolo aberto que permite a agentes de fornecedores diferentes conversarem e coordenarem tarefas entre si. Foi anunciado pelo Google em 9 de abril de 2025, no Google Cloud Next, com mais de 50 parceiros (incluindo Atlassian, Box, Cohere, LangChain, MongoDB, PayPal, Salesforce, SAP, ServiceNow e Workday), e doado à Linux Foundation em junho de 2025. Ex.: dois assistentes de marcas diferentes combinando uma tarefa por conta própria.
Vibe Coding: Programar descrevendo a tarefa em linguagem natural e deixando a IA gerar o código, muitas vezes sem revisar linha por linha. O termo foi cunhado por Andrej Karpathy em 2 de fevereiro de 2025, em postagem no X: "There's a new kind of coding I call 'vibe coding', where you fully give in to the vibes, embrace exponentials, and forget that the code even exists." Ex.: dizer "faça um app de lista de compras" e aceitar o que o assistente entregar. X

6. PLN (Processamento de Linguagem Natural)

PLN (NLP): Campo que faz a máquina entender e gerar linguagem humana. Ex.: o corretor que entende o sentido das suas frases.
Análise de Sentimento: Detecta a emoção ou opinião de um texto. Ex.: ver se uma avaliação de produto é positiva ou negativa.
NER (Reconhecimento de Entidades Nomeadas): Identifica nomes de pessoas, lugares e empresas no texto. Ex.: grifar "São Paulo" e "Maria" automaticamente.
POS Tagging (Marcação Gramatical): Marca a classe de cada palavra (verbo, substantivo, adjetivo). Ex.: etiquetar cada palavra da frase com sua função.
Tradução Automática: Traduz texto de um idioma para outro. Ex.: app que traduz o cardápio na hora.
Sumarização: Resume textos longos em versões curtas. Ex.: transformar 10 páginas em um parágrafo.
Word2Vec: Técnica que transforma palavras em vetores que captam significado. Ex.: "rei" − "homem" + "mulher" ≈ "rainha".
N-grama: Sequência de N palavras ou letras seguidas. Ex.: "bom dia" é um bigrama (2-grama).
Stemming (Radicalização): Corta o final das palavras para chegar a um radical, sem se preocupar com gramática. Ex.: "correndo" vira "corr".
Lematização: Reduz a palavra à sua forma de dicionário, considerando o contexto. Ex.: "melhores" vira "bom".
Tokenização (em PLN): Quebrar o texto em unidades menores. Ex.: separar a frase em palavras.
Bag of Words (Saco de Palavras): Representa o texto contando palavras, ignorando a ordem. Ex.: uma lista de compras sem sequência definida.
TF-IDF: Mede a importância de uma palavra em um documento. Ex.: destacar as palavras raras e relevantes do texto.
Stop Words: Palavras muito comuns geralmente removidas ("de", "a", "o"). Ex.: tirar o "enchimento" antes de analisar o texto.

7. Visão Computacional

Visão Computacional: Campo que faz máquinas "enxergarem" e interpretarem imagens e vídeos. Ex.: o celular que reconhece o seu rosto.
Detecção de Objetos: Localiza e marca objetos com caixas na imagem. Ex.: desenhar quadrados em volta dos carros numa foto.
Segmentação Semântica: Rotula cada pixel da imagem por categoria. Ex.: pintar de azul tudo o que for céu.
Segmentação de Instância: Separa cada objeto individualmente, mesmo da mesma categoria. Ex.: distinguir cada pessoa numa multidão.
Reconhecimento Facial: Identifica de quem é determinado rosto. Ex.: desbloquear o celular olhando para ele.
OCR (Reconhecimento Óptico de Caracteres): Lê texto que está dentro de imagens. Ex.: digitalizar e "ler" uma nota fiscal de papel.
Classificação de Imagem: Diz a que categoria a imagem inteira pertence. Ex.: dizer se a foto é de praia ou de montanha.
YOLO ("You Only Look Once"): Família de modelos rápidos de detecção de objetos em tempo real. Ex.: identificar tudo num vídeo ao vivo, instantaneamente.
Bounding Box (Caixa Delimitadora): O retângulo que cerca um objeto detectado. Ex.: a moldura desenhada ao redor do gato.

8. MLOps e Engenharia de ML

MLOps: Conjunto de práticas para colocar e manter modelos de ML em produção (o "DevOps para ML"). Ex.: a linha de montagem que cuida do modelo do início ao fim.
Pipeline de ML: Sequência automatizada de etapas, dos dados ao modelo treinado. Ex.: a esteira de uma fábrica de modelos.
Deploy / Implantação: Colocar o modelo em uso real. Ex.: abrir a loja para o público.
Model Serving: Disponibilizar o modelo para receber pedidos (geralmente via API). Ex.: o garçom que entrega as previsões aos clientes.
Monitoramento de Modelo: Acompanhar o desempenho do modelo já em produção. Ex.: checar a "saúde" do modelo todos os dias.
Model Drift / Data Drift (Deriva de Modelo / de Dados): Queda de desempenho porque os dados do mundo real mudaram. Ex.: um mapa antigo que não bate mais com a cidade nova.
Feature Store: Repositório central de atributos, reutilizáveis no treino e na produção. Ex.: uma despensa organizada de ingredientes prontos.
Versionamento de Modelo: Guardar e identificar cada versão do modelo. Ex.: salvar "v1", "v2", "v3" do trabalho.
CI/CD para ML: Integração e entrega contínuas adaptadas a ML, somando "CT" (treino contínuo). Ex.: atualizar o app automaticamente, com testes de segurança.
A/B Testing: Comparar duas versões com usuários reais para ver qual é melhor. Ex.: testar dois cardápios e ver qual vende mais.
Model Registry: Catálogo central das versões de modelo aprovadas. Ex.: a estante oficial com os modelos prontos para uso.
Experiment Tracking: Registrar cada experimento e seus resultados. Ex.: o diário de bordo de todos os testes.
Containerização: Empacotar o modelo com tudo de que ele precisa para rodar em qualquer lugar. Ex.: uma marmita pronta que funciona em qualquer cozinha.
Inferência: Usar o modelo já treinado para gerar previsões. Ex.: o modelo "respondendo" de fato na prática.

9. Dados

Big Data: Volumes enormes de dados que exigem ferramentas especiais. Ex.: um oceano de informações.
Dataset (Conjunto de Dados): Coleção organizada de dados para um projeto. Ex.: uma planilha gigante cheia de exemplos.
Dados de Treino / Validação / Teste: Partes dos dados usadas para ensinar, ajustar e avaliar o modelo. Ex.: estudar, fazer simulado e, por fim, a prova final.
Rotulagem / Anotação: Marcar os dados com as respostas corretas. Ex.: escrever "gato" embaixo de cada foto.
Data Augmentation: Criar variações dos dados para enriquecer o treino. Ex.: girar, recortar e clarear fotos para ter mais exemplos.
Normalização: Ajustar os dados a uma mesma escala. Ex.: converter tudo para a mesma unidade de medida.
Data Mining (Mineração de Dados): Descobrir padrões úteis em grandes volumes de dados. Ex.: garimpar ouro no meio dos números.
ETL (Extrair, Transformar, Carregar): Processo de coletar, limpar e armazenar dados para uso. Ex.: pegar, lavar e guardar os ingredientes antes de cozinhar.
Dados Estruturados: Dados organizados em tabelas, com campos definidos. Ex.: uma planilha com colunas e linhas.
Dados Não Estruturados: Dados sem formato fixo, como texto livre, áudio e fotos. Ex.: uma caixa cheia de fotos e bilhetes soltos.
Dados Sintéticos: Dados artificiais criados para treinar quando faltam dados reais. Ex.: usar um manequim no lugar de uma pessoa de verdade.

10. Avaliação e Métricas

Acurácia: Proporção de acertos sobre o total. Ex.: a nota de quantas questões você acertou na prova.
Precisão: Dos casos que o modelo disse "sim", quantos eram realmente certos. Ex.: dos alarmes que dispararam, quantos eram fogo de verdade.
Recall (Revocação / Sensibilidade): Dos casos que eram "sim" de verdade, quantos o modelo encontrou. Ex.: de todos os incêndios, quantos o alarme conseguiu detectar.
F1-Score: Média harmônica entre precisão e recall, equilibrando os dois. Ex.: uma nota única que junta acerto e cobertura.
Matriz de Confusão: Tabela que mostra acertos e erros por categoria. Ex.: um boletim detalhado de quais tipos de erro aconteceram.
ROC / AUC: Curva e área que medem o quão bem o modelo separa as classes (0,5 = chute; 1,0 = perfeito). Ex.: uma nota geral de quão bem ele distingue bom de ruim.
Overfitting (Sobreajuste): Modelo que decora o treino e erra em dados novos. Ex.: decorar a prova e travar numa pergunta diferente.
Underfitting (Subajuste): Modelo simples demais, que vai mal até no treino. Ex.: estudar de menos e ir mal em tudo.
Viés-Variância (Trade-off): Equilíbrio entre erro por simplificar demais e erro por complicar demais. Ex.: nem chutar igual sempre, nem inventar exageros.
Validação Cruzada: Testar o modelo em várias divisões diferentes dos dados. Ex.: revezar quem faz o simulado para a nota ser mais justa.
Benchmark: Teste-padrão usado para comparar modelos. Ex.: uma prova oficial que todos os candidatos fazem.
Perplexidade: Mede o quanto um modelo de linguagem fica "surpreso" ao prever o texto; quanto menor, melhor. Ex.: o quanto a IA se atrapalha para adivinhar a próxima palavra.
BLEU: Métrica que compara uma tradução gerada com uma tradução de referência humana. Ex.: a nota de quanto a tradução bate com o gabarito.

11. Ética, Segurança e Governança

Viés Algorítmico: Preconceito presente nos dados que o modelo acaba reproduzindo. Ex.: um sistema que favorece injustamente um grupo de pessoas.
Fairness (Justiça / Equidade): Garantir tratamento equânime entre diferentes grupos. Ex.: usar a mesma régua para todo mundo.
Alinhamento (Alignment): Fazer a IA agir conforme valores e intenções humanas. Ex.: ensinar o robô a ser prestativo, honesto e seguro.
Explicabilidade (XAI): Capacidade de explicar por que a IA tomou determinada decisão. Ex.: o médico-robô mostrando o motivo do diagnóstico.
Interpretabilidade: O quanto conseguimos entender o funcionamento interno do modelo. Ex.: enxergar dentro da "caixa-preta".
IA Responsável: Desenvolver e usar IA de forma ética, segura e transparente. Ex.: um conjunto de regras de boa conduta para projetos de IA.
Privacidade: Proteger os dados pessoais usados ou gerados pela IA. Ex.: não deixar vazar seus dados de saúde.
Red Teaming: Testar a IA tentando, de propósito, fazê-la se comportar mal, antes do lançamento. Ex.: um hacker do bem procurando brechas no sistema.
Guardrails (Salvaguardas): Filtros e regras que bloqueiam respostas perigosas ou proibidas. Ex.: a mureta de proteção na beira da estrada.
Jailbreak: Truque que burla as proteções do modelo para obter respostas proibidas. Ex.: convencer o robô a quebrar as próprias regras.
Prompt Injection: Ataque que insere instruções maliciosas na entrada para desviar o comportamento do modelo; é a vulnerabilidade nº 1 (LLM01) do OWASP Top 10 para aplicações de LLM (2025). Ex.: um bilhete escondido mandando o assistente desobedecer ao chefe.
Deepfake: Mídia falsa hiper-realista (vídeo, foto, áudio) criada por IA. Ex.: um vídeo de alguém "dizendo" o que nunca disse.
Watermarking (Marca d'Água): Marca invisível que identifica conteúdo gerado por IA. Ex.: um carimbo secreto embutido na imagem.

12. Hardware e Infraestrutura

GPU (Unidade de Processamento Gráfico): Chip que faz muitos cálculos em paralelo; virou a base do deep learning. Ex.: mil calculadoras trabalhando ao mesmo tempo.
TPU (Unidade de Processamento Tensorial): Chip criado pelo Google especificamente para ML. Ex.: uma calculadora especializada só em IA.
CPU (Unidade Central de Processamento): O processador de uso geral do computador. Ex.: o cérebro que faz um pouco de tudo.
NPU (Unidade de Processamento Neural): Chip eficiente de IA presente em celulares e dispositivos. Ex.: um motorzinho de IA dentro do celular.
Computação em Nuvem: Usar servidores remotos sob demanda, pela internet. Ex.: alugar potência em vez de comprar um supercomputador.
Edge AI (IA na Borda): Rodar a IA no próprio dispositivo, sem depender da nuvem. Ex.: uma câmera que reconhece coisas sozinha, mesmo offline.
Computação Distribuída: Dividir o trabalho entre várias máquinas. Ex.: muita gente montando o mesmo quebra-cabeça junta.
Paralelismo: Fazer várias tarefas ao mesmo tempo. Ex.: vários caixas de supermercado atendendo simultaneamente.
FLOPs: Medida de quantas operações de cálculo (com vírgula) são feitas por segundo. Ex.: o velocímetro da capacidade de cálculo.

13. Hiperparâmetros e Treinamento

Hiperparâmetro: Configuração definida pelo humano antes do treino começar. Ex.: ajustar a temperatura do forno antes de assar.
Época (Epoch): Uma passada completa por todos os dados de treino. Ex.: ler o livro inteiro uma vez.
Batch (Lote): Grupo de exemplos processados juntos de cada vez. Ex.: lavar a louça em pilhas, não prato por prato.
Learning Rate (Taxa de Aprendizado): Tamanho do passo de ajuste a cada atualização. Ex.: dar passos grandes ou pequenos ao descer a escada.
Regularização (L1 / L2): Penaliza a complexidade do modelo para evitar overfitting. Ex.: uma regra que evita exageros na resposta.
Early Stopping (Parada Antecipada): Parar o treino quando o modelo deixa de melhorar. Ex.: parar de estudar quando você já decorou tudo.
Transfer Learning (Aprendizado por Transferência): Reaproveitar um modelo já treinado como ponto de partida em outra tarefa. Ex.: quem toca violão aprende cavaquinho bem mais rápido.
Federated Learning (Aprendizado Federado): Treinar um modelo compartilhado em vários aparelhos sem juntar os dados num só lugar (técnica do Google, McMahan et al.). Ex.: cada celular aprende localmente e só envia o resumo, mantendo seus dados em casa.

Termos Emergentes (2024-2026)

SLM (Pequeno Modelo de Linguagem): Modelo de linguagem compacto (de milhões a poucos bilhões de parâmetros), eficiente e muitas vezes específico. Ex.: um assistente enxuto que roda direto no celular. Hugging Face
Mamba / SSM (Modelos de Espaço de Estados): Arquitetura alternativa ao transformer, eficiente em sequências longas e com custo linear (em vez do custo quadrático da atenção). Foi introduzida por Albert Gu e Tri Dao em 1º de dezembro de 2023 (artigo "Mamba: Linear-Time Sequence Modeling with Selective State Spaces"), com throughput cerca de 5× maior que o de Transformers comparáveis. Ex.: um leitor que acompanha textos muito longos sem se perder nem cansar.
Context Engineering (Engenharia de Contexto): Prática de projetar todo o contexto que um agente precisa (instruções, conhecimento recuperado, memória, ferramentas, estado), indo além de só escrever o prompt. Ex.: montar a mesa de trabalho completa antes de pedir a tarefa. GitHub
World Models (Modelos de Mundo): IA que aprende uma representação interna de como o ambiente funciona (física, causa e efeito) para prever consequências e planejar. Ex.: imaginar mentalmente o que vai acontecer antes de agir. Thomasthelliez
Vector Database (Banco de Dados Vetorial): Banco especializado que guarda embeddings e faz busca por similaridade; base de muitos sistemas de RAG. Ex.: uma prateleira mágica que encontra os itens "mais parecidos".
Coding Agent (Agente de Programação): Agente que escreve, executa e corrige código com autonomia. Ex.: um programador-robô que faz a tarefa quase sozinho.
