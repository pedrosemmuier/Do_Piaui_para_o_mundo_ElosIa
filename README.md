# ElosIA — Inteligência Artificial e Acessibilidade na Comunicação da Nossa Escola

> **Inclusão sociodigital e IA integrando a nossa comunidade escolar, aproximando famílias com baixa escolaridade ou deficiência auditiva.**

O **ElosIA** é um assistente virtual focado em acessibilidade local, desenvolvido sob medida para a realidade e os desafios da nossa escola. Operando de forma direta no WhatsApp, o sistema utiliza a API da **OpenAI** para processar as mensagens das famílias, simplificar a linguagem pedagógica e responder de forma multimodal: através de texto curto, áudio claro e suporte em Libras.

---

## O Nosso Cenário e o Problema
Convivendo diariamente na nossa escola, identificamos que os canais tradicionais de comunicação (avisos em murais, bilhetes impressos ou editais) geravam exclusão. Na nossa realidade, enfrentamos três grandes barreiras:
1. **Dificuldades de leitura e baixa escolaridade:** Muitos responsáveis não compreendem circulares com termos pedagógicos complexos.
2. **Deficiência auditiva:** Responsáveis surdos ficam isolados das decisões e eventos da escola.
3. **Sobrecarga local:** A secretaria da nossa escola acumula funções, gerando filas e atrasos para responder dúvidas repetitivas.

*Dado de Validação Interna:* Em pesquisa realizada com a nossa comunidade escolar, **91,4%** das famílias declararam preferência absoluta pelo uso do WhatsApp para tratar de assuntos acadêmicos.

---

## Como Funciona o MVP (O Nosso Fluxo)
O ElosIA adapta a tecnologia à realidade socioeconômica dos nossos alunos e responsáveis, exigindo apenas um celular comum com internet limitada.

- [x] **Processamento com OpenAI:** A IA da OpenAI interpreta as dúvidas enviadas por texto ou transcrição de áudio das famílias e busca a resposta exata na base de dados interna da nossa escola.
- [x] **Linguagem Simplificada:** A OpenAI garante que a resposta gerada seja curta, direta e livre de termos técnicos ou burocráticos.
- [x] **Áudio Automático Simultâneo:** O sistema envia a resposta em texto e um áudio correspondente (essencial para pais analfabetos ou com baixa visão da nossa comunidade).
- [x] **Acessibilidade em Libras:** Envio de um link dedicado para a nossa página web leve integrada ao widget do **VLibras**, traduzindo o aviso escolar para a Língua Brasileira de Sinais.
- [x] **Agendamento e Menus:** Fluxos diretos para marcação de reuniões com a coordenação pedagógica da nossa escola.

---

## Stack Tecnológica
* **Inteligência Artificial (LLM):** OpenAI API (GPT-4o mini)
* **Orquestração e Integração:** n8n / Typebot
* **Canal:** API do WhatsApp (Evolution API / Baileys)
* **Acessibilidade:** Widget VLibras (Governo Federal)
* **Hospedagem:** Hostinger

---

## Nossa Equipe
* Seu Nome - Mentor do Projeto & Estratégia de MVP
* Pedro Ivo Assis Bomfim - MVP & Automação (n8n + WhatsApp)
* Karine Neres De Freitas - Integração da API da OpenAI & Engenharia de Prompt
* Ícaro Rafael Strieder Pulgas - Desenvolvimento da Página Local com VLibras
* Pedro Felipe Feitosa Floresta - Identidade Visual, Design dos Slides & Demo
* Mikaela Jacobina Neres - Documentação do Repositório & Repositório GitHub
