# 📌 Seu Primeiro Copiloto de IA  
### Criando uma Solução Inteligente com IA Generativa

## 📖 Visão Geral

Este projeto foi desenvolvido como parte do trabalho da disciplina **Fundamentos de Inteligência Artificial com foco em IA Generativa**.  
O objetivo é prototipar uma solução prática que utilize **modelos de linguagem de grande escala (LLMs)** e **prompt engineering** para auxiliar colaboradores na criação de textos corporativos de forma mais rápida, padronizada e alinhada à identidade organizacional.

A solução proposta consiste em um **Copiloto de IA Generativa**, integrado ao Telegram, capaz de gerar e adaptar comunicações internas do setor de Recursos Humanos, como e-mails, avisos institucionais, mensagens corporativas e resumos de reunião.

---

## 🎯 Problema Identificado

Departamentos de Recursos Humanos e Comunicação Interna lidam diariamente com um grande volume de textos repetitivos, como:

- E-mails institucionais  
- Avisos internos  
- Mensagens para WhatsApp corporativo  
- Resumos e atas de reunião  

Apesar de semelhantes, essas comunicações exigem cuidado com o tom, clareza, padronização e alinhamento com a cultura da empresa, o que gera **sobrecarga operacional**, consumo excessivo de tempo e risco de inconsistências.

---

## 💡 Solução Proposta

O **Copiloto de IA** atua como um assistente inteligente de comunicação corporativa, recebendo inputs simples do usuário e gerando textos:

- Coerentes  
- Bem estruturados  
- Adaptados ao público e ao canal  
- Alinhados à identidade organizacional  

Todo conteúdo gerado passa por **validação humana**, garantindo uso responsável da IA.

---

## 🧠 Tecnologias e Ferramentas Utilizadas

- **Telegram**  
  Interface de interação com o usuário (chatbot).

- **n8n**  
  Orquestração dos fluxos de automação e integração entre serviços.

- **Supabase**  
  Banco de dados para cadastro de colaboradores, preferências e controle de consentimento.

- **Gemini 2.5 Flash**  
  Utilizado para:
  - Transcrição literal de áudios  
  - Leitura e transcrição de documentos  
  - Análise e descrição objetiva de imagens  

- **GPT-4.1 Mini**  
  Utilizado para:
  - Geração de textos corporativos  
  - Adaptação de tom, linguagem e estrutura  
  - Aplicação de prompt engineering avançado  

---

## 🧩 Arquitetura da Solução

O fluxo da aplicação segue as seguintes etapas:

1. **Entrada do Usuário (Telegram)**  
   O colaborador envia texto, áudio, imagem ou documento.

2. **Normalização dos Dados**  
   O conteúdo é identificado e classificado conforme o tipo de mídia.

3. **Processamento Multimodal (Gemini)**  
   - Áudio → transcrição literal  
   - Documento → extração completa do texto  
   - Imagem → descrição objetiva  

4. **Identificação do Colaborador (Supabase)**  
   O sistema identifica o usuário pelo ID do Telegram e carrega suas preferências.

5. **Geração de Conteúdo (GPT-4.1 Mini)**  
   Um agente de IA generativa utiliza prompts estruturados com:
   - identidade organizacional  
   - tom de voz institucional  
   - regras hierárquicas  
   - diretrizes de LGPD  

6. **Segmentação da Resposta**  
   Mensagens longas são divididas em blocos naturais para conversas em chat.

7. **Entrega da Resposta (Telegram)**  
   O texto final é enviado ao usuário de forma clara e humanizada.

---

## 🧠 Uso de IA Generativa e Prompt Engineering

O comportamento do copiloto é definido por **prompts cuidadosamente elaborados**, que consideram:

- Cargo e departamento do colaborador  
- Nível de formalidade desejado  
- Canal de comunicação (e-mail, WhatsApp, aviso institucional)  
- Cultura e valores da organização fictícia (InnovaTech Solutions)

A IA não atua apenas como geradora de texto, mas como um **assistente cognitivo especializado em comunicação corporativa**.

---

## 🔐 Ética, LGPD e Segurança

O projeto foi desenvolvido com foco em boas práticas de uso responsável da IA:

- Armazenamento apenas de dados essenciais  
- Consentimento explícito para uso de IA  
- Não retenção de conteúdos sensíveis  
- Alertas automáticos sobre possíveis riscos de privacidade  
- Alinhamento com os princípios da **Lei Geral de Proteção de Dados (LGPD)**  

A IA atua como **apoio à decisão humana**, não substituindo o julgamento do usuário.

---

## 🧪 Demonstração do Protótipo

Durante a demonstração prática, é possível observar:

- Envio de mensagens pelo Telegram  
- Processamento multimodal (texto, áudio, imagem e documentos)  
- Geração automática de mensagens corporativas  
- Adaptação de tom e linguagem conforme solicitação do usuário  

---

## 📌 Considerações Finais

Este projeto demonstra, na prática, como a **Inteligência Artificial Generativa** pode ser aplicada para resolver problemas reais no ambiente corporativo, promovendo:

- Aumento de produtividade  
- Padronização da comunicação  
- Redução da sobrecarga operacional do RH  

A solução atende aos objetivos propostos pela disciplina, integrando teoria e prática por meio de um protótipo funcional, ético e bem documentado.

---

## 👤 Autor

**David William Tamiette**  
Trabalho acadêmico – Fundamentos de IA com Foco em IA Generativa  
Unifecaf
