# Configuração de Pesquisa Cognitiva no Azure

## Introdução  
A **Pesquisa Cognitiva do Azure** é uma ferramenta poderosa para **mineração de conhecimento**, permitindo extrair informações relevantes de documentos, imagens e bancos de dados de forma inteligente. Este repositório contém um guia passo a passo para configurar uma pesquisa cognitiva e insights sobre suas aplicações e benefícios.

---

## Passo a passo para configurar uma Pesquisa Cognitiva no Azure

### 1. Criar um recurso de Pesquisa Cognitiva  
1. Acesse o **[Portal do Azure](https://portal.azure.com/)**.  
2. Vá até **Criar um recurso** e pesquise por **"Pesquisa Cognitiva do Azure"**.  
3. Escolha um **grupo de recursos**, dê um nome ao serviço e selecione a região.  
4. Escolha o nível de preço conforme a necessidade (existem opções **gratuitas e pagas**).  
5. Clique em **Criar** e aguarde a implantação.

### 2. Conectar uma Fonte de Dados  
1. No serviço de Pesquisa Cognitiva, vá até **Fontes de Dados**.  
2. Selecione uma fonte, como:  
   - **Azure Blob Storage** (para documentos e imagens).  
   - **Banco de Dados SQL do Azure** (para armazenar informações estruturadas).  
   - **Cosmos DB** (para bases NoSQL).  
3. Insira as credenciais e configure o acesso.  

### 3. Criar um Índice de Pesquisa  
1. Vá até **Índices** e clique em **Adicionar índice**.  
2. Defina os **campos** que deseja indexar (exemplo: título, data, autor, conteúdo).  
3. Marque os campos necessários para **busca, filtragem e ordenação**.  
4. Salve as configurações.

### 4. Criar um Conjunto de Habilidades de IA (Opcional)  
Se desejar aplicar **IA para enriquecer os dados**, siga estes passos:  
1. Vá até **Conjuntos de Habilidades** e adicione habilidades como:  
   - **OCR (Reconhecimento de Texto)** para extrair texto de imagens.  
   - **Análise de Sentimento** para classificar emoções nos textos.  
   - **Tradução Automática** para converter idiomas.  
2. Conecte as habilidades ao índice criado.

### 5. Criar um Indexador  
1. Vá até **Indexadores** e clique em **Adicionar indexador**.  
2. Escolha a **fonte de dados** e o **índice de pesquisa** criado.  
3. Configure a frequência da indexação.  
4. Execute o indexador para preencher o índice com os dados.

### 6. Realizar uma Busca  
1. Vá até **Explorador de Pesquisa**.  
2. Digite um termo e veja os resultados.  
3. Ajuste os filtros e ordenações conforme necessário.

---

## Possíveis Aplicações e Ferramentas Beneficiadas  
A **Pesquisa Cognitiva do Azure** pode ser aplicada em diversas áreas:  
- **Automação de Documentos** – Extração de informações de contratos, faturas e recibos.  
- **E-commerce** – Melhoria na busca de produtos e recomendações personalizadas.  
- **Empresas** – Análise de grandes volumes de documentos internos.  
- **Educação e Pesquisa** – Mineração de conhecimento em artigos e bases científicas.  
- **Jurídico** – Busca inteligente em processos e arquivos jurídicos.

---

## Insights e Aprendizados  
- A Pesquisa Cognitiva **não apenas busca texto**, mas **enriquece os dados** com IA.  
- Ferramentas como **Análise de Sentimento e OCR** são úteis para criar aplicações mais inteligentes.  
- A combinação de **fontes de dados estruturadas e não estruturadas** amplia as possibilidades de análise.  
- Mesmo usuários sem conhecimento técnico podem explorar as funcionalidades pelo **Portal do Azure**.  
---

## Recursos Adicionais  
- [Documentação Oficial do Azure Cognitive Search](https://learn.microsoft.com/en-us/azure/search/)  
- [Guia de Treinamento Microsoft Learn](https://learn.microsoft.com/en-us/training/paths/document-intelligence-knowledge-mining/)  
- [AI Search Hands-On](https://aka.ms/ai900-ai-search)  
