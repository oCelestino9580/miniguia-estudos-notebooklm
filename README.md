# 📘 Miniguia de Estudos: IA Generativa na Educação com NotebookLM

## 🎯 Contexto e Objetivos

Este projeto foi desenvolvido como parte do desafio da **DIO (Digital Innovation One)** para explorar o uso do **Google NotebookLM** como ferramenta de aprendizagem ativa. O tema escolhido foi **"Inteligência Artificial Generativa na Educação"**, um assunto em alta que conecta tecnologia, inovação e práticas pedagógicas modernas.

**Objetivos de estudo:**
- Compreender os fundamentos da IA generativa e suas aplicações educacionais
- Desenvolver habilidades de curadoria de fontes e pensamento crítico
- Dominar técnicas de engenharia de prompts para extrair o melhor da IA
- Criar um material de estudo estruturado e reutilizável para revisões futuras

## 📚 Curadoria de Fontes

Foram selecionadas **5 fontes abertas** (artigos, relatórios e guias em PDF/texto) que serviram de base para o caderno temático no NotebookLM:

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | **UNESCO - Guidance for Generative AI in Education and Research** | PDF | [https://www.unesco.org/en/digital-education/artificial-intelligence/generative-ai](https://www.unesco.org/en/digital-education/artificial-intelligence/generative-ai) |
| 2 | **Stanford HAI - AI Index Report 2025 (Capítulo Educação)** | PDF | [https://aiindex.stanford.edu/report/](https://aiindex.stanford.edu/report/) |
| 3 | **OECD - Artificial Intelligence in Education: Promises and Implications** | PDF | [https://www.oecd.org/education/artificial-intelligence-in-education.htm](https://www.oecd.org/education/artificial-intelligence-in-education.htm) |
| 4 | **Google Blog - 8 Expert Tips for Getting Started with NotebookLM** | Artigo | [https://blog.google/innovation-and-ai/products/notebooklm-beginner-tips/](https://blog.google/innovation-and-ai/products/notebooklm-beginner-tips/) |
| 5 | **NotebookLM Prompt Engineering Guide** | Guia | [https://notebooklm.hk/en/blog/notebooklm-prompt-engineering-guide/](https://notebooklm.hk/en/blog/notebooklm-prompt-engineering-guide/) |

## ⚙️ Engenharia de Prompts e "Cicatrizes"

### Perguntas Estratégicas Testadas

Durante o projeto, elaborei e refinei diversos prompts para extrair o máximo do NotebookLM. Abaixo, registro as principais iterações:

#### **Prompt 1: Resumo Inicial (Versão Fraca)**
**Resultado:** Resposta genérica, sem citações das fontes, misturava informações externas.  
**Problema:** Prompt muito aberto, sem restrição de fonte ou formato.

---

#### **Prompt 2: Resumo com Citações (Versão Melhorada)**
**Resultado:** Lista objetiva com citações numeradas.  
**Melhoria:** Adicionei restrição de fonte, formato e número de itens.

---

#### **Prompt 3: Comparação entre Fontes (Versão Avançada)**
**Resultado:** Tabela clara com contradições e consensos.  
**Dificuldade:** O NotebookLM inicialmente ignorou a coluna de citação — refinei pedindo "inclua o número da citação após cada célula".

---

#### **Prompt 4: Glossário (Versão Final)**
**Resultado:** Glossário preciso e referenciado.  
**Troubleshooting:** Na primeira tentativa, a IA inventou definições. Adicionei a regra "se não estiver nas fontes, diga explicitamente".

---

### 🧠 Lições Aprendidas (Cicatrizes)

1. **Sempre restrinja a fonte:** NotebookLM funciona melhor quando você diz "com base apenas nas fontes deste notebook".
2. **Peça formato explícito:** Tabelas, listas e bullets são mais fáceis de verificar que textos longos.
3. **Exija citações:** Sem pedir citações, a IA pode alucinar. Sempre inclua "com citação" no prompt.
4. **Itere rápido:** A primeira resposta raramente é a melhor. Refine com "detalhe mais", "corte X", "adicione Y".
5. **Aceite lacunas:** Se a IA disser "não coberto nas fontes", é sinal de que você precisa adicionar mais material.

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados

#### **O que é IA Generativa?**
IA generativa é um tipo de inteligência artificial capaz de criar conteúdo novo (texto, imagem, áudio, código) a partir de padrões aprendidos em grandes volumes de dados. Na educação, ela pode gerar exercícios, explicar conceitos, corrigir redações e personalizar trilhas de aprendizagem [1][2].

#### **Principais Benefícios na Educação**
- **Personalização:** Adapta o ritmo e o estilo de ensino para cada aluno [1][3].
- **Acesso democratizado:** Ferramentas gratuitas ou de baixo custo ampliam o acesso a tutoria de qualidade [2][4].
- **Automação de tarefas repetitivas:** Correção de provas, geração de quizzes e feedbacks rápidos liberam tempo do professor para mentoria [3][5].
- **Criatividade e engajamento:** Alunos podem criar projetos multimídia com apoio da IA [1][2].

#### **Riscos e Desafios**
- **Plágio e dependência:** Estudantes podem usar IA para fazer tarefas sem aprender [1][3].
- **Viés algorítmico:** Modelos treinados em dados enviesados podem reforçar estereótipos [2][3].
- **Privacidade de dados:** Uso de plataformas de IA exige cuidado com informações sensíveis de alunos [1][4].
- **Despreparo docente:** Professores precisam de formação para integrar IA de forma crítica e pedagógica [3][5].

---

### 2. Glossário de Conceitos

| Termo | Definição | Fonte |
|-------|-----------|-------|
| **IA Generativa** | Tipo de IA que cria conteúdo novo (texto, imagem, etc.) a partir de padrões aprendidos. | [1][2] |
| **Prompt** | Instrução ou pergunta dada à IA para gerar uma resposta. | [4][5] |
| **Alucinação** | Quando a IA inventa informações não presentes nas fontes. | [5][9] |
| **RAG (Retrieval-Augmented Generation)** | Técnica que combina busca em fontes com geração de texto para reduzir alucinações. | [9] |
| **Curadoria de Fontes** | Processo de selecionar, validar e organizar materiais de estudo confiáveis. | [6][8] |
| **Engenharia de Prompts** | Arte de escrever instruções claras e estruturadas para extrair o melhor da IA. | [5][9] |
| **Personalização** | Adaptação do ensino ao ritmo, estilo e necessidades de cada aluno. | [1][3] |
| **Viés Algorítmico** | Distorção nos resultados da IA causada por dados de treinamento enviesados. | [2][3] |
| **Audio Overview** | Recurso do NotebookLM que transforma fontes em um podcast com IA. | [6][11] |
| **Notebook** | Container temático no NotebookLM que agrupa fontes e gera respostas baseadas nelas. | [1][4] |

---

### 3. Prompts Reutilizáveis

Salve estes prompts para usar em futuros cadernos temáticos:

#### **📌 Resumo Rápido**

#### **📌 Comparação entre Fontes**

#### **📌 Glossário Temático**

#### **📌 Linha do Tempo**

#### **📌 Checagem de Contradições**

#### **📌 Extração de Citações**

---

## 🚀 Como Usar Este Projeto

1. **Crie um caderno no NotebookLM:** Acesse [notebooklm.google.com](https://notebooklm.google.com) e faça login com sua conta Google.
2. **Adicione as fontes:** Faça upload dos PDFs ou cole os links das fontes listadas acima.
3. **Use os prompts:** Copie e cole os prompts reutilizáveis no chat do NotebookLM.
4. **Salve as respostas:** Fixe as melhores respostas no painel "Estúdio" para montar seu próprio miniguia.
5. **Gere um Audio Overview:** Use o recurso de podcast para revisar o conteúdo enquanto faz outras atividades.

---

## 📬 Contato

**Autor:** [Seu Nome Aqui]  
**LinkedIn:** [linkedin.com/in/seu-perfil](https://linkedin.com/in/seu-perfil)  
**GitHub:** [github.com/seu-usuario](https://github.com/seu-usuario)

---

## 📌 Referências

[1] UNESCO. *Guidance for Generative AI in Education and Research*. 2023.  
[2] Stanford HAI. *AI Index Report 2025*.  
[3] OECD. *Artificial Intelligence in Education: Promises and Implications*. 2024.  
[4] Google Blog. *8 Expert Tips for Getting Started with NotebookLM*. 2024.  
[5] NotebookLM Guide. *Prompt Engineering Guide + 30 Templates*. 2026.  
[6] Apidog. *Como usar NotebookLM em 2026: Guia Prático*. 2026.  
[7] Codecademy. *How to Use NotebookLM: Create Study Notes & Presentations*. 2025.  
[8] GitHub. *Caderno Temático com NotebookLM + IA*. 2026.  
[9] NotebookLM HK. *NotebookLM Prompt Engineering Guide*. 2026.  
[10] Tech Insider. *How to Use NotebookLM: 12 Steps, 75 Min [2026]*.  
[11] Hora de Codar. *Prompt para NotebookLM: como estruturar seus pedidos*. 2026.
