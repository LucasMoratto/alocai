# 🚀 Desafio de IA: Produto e Engenharia de Prompt

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Desafio](https://img.shields.io/badge/Módulo-1-blue)
![Ferramenta](https://img.shields.io/badge/Ferramenta-Google_NotebookLM-orange)

## 📌 Visão Geral do Projeto
Este repositório contém a entrega da avaliação do primeiro módulo, focada na interseção entre **Gestão de Produtos** e **Engenharia de Prompts**. O objetivo do desafio é idealizar um produto digital, documentar seu escopo e criar um prompt avançado para configurar um Assistente de Inteligência Artificial Especialista usando o Google NotebookLM.

## 📂 Estrutura do Repositório
Conforme as diretrizes da avaliação, este repositório contém estritamente dois arquivos em formato PDF (ambos respeitando o limite de 6.000 caracteres):

*   📄 **`AlocAI.pdf`**: Documentação oficial do produto desenvolvido.
*   📄 **`Prompt AlocAI.pdf`**: O prompt de sistema contendo a configuração de personalidade e diretrizes do agente de IA.

---

## 🏗️ O Produto: AlocAI
O **AlocAI** é uma aplicação web corporativa (SaaS) projetada para automatizar e otimizar a alocação de colaboradores em obras e montagens industriais. 

**Principais Funcionalidades documentadas:**
*   Gestão de contingente e validação de requisitos técnicos (ex: NR-10, Operador de PTA).
*   Matriz Comportamental (Afinidades e Desafinidades entre recursos).
*   Painel Kanban interativo (*Drag & Drop*) com validação em tempo real.
*   Motor de IA para alocação inteligente respeitando regras de negócio bloqueantes.
*   Dashboard de visibilidade para equipes de apoio logístico (hotelaria, transporte e refeições).

---

## 🤖 O Agente de IA: Especialista de Suporte Técnico
O prompt foi desenhado para fazer o NotebookLM incorporar a persona de um **Suporte Técnico Sênior**. A IA atua com rigor técnico, formalidade e foco estrito na documentação fornecida.

### 🛠️ Técnicas de Engenharia de Prompt Utilizadas
Para garantir alta precisão e mitigar alucinações, foram aplicadas as seguintes técnicas no documento do prompt:

1.  **Chain of Thought (Cadeia de Raciocínio):**
    O agente é instruído a processar a solicitação em etapas lógicas invisíveis (*Análise > Busca > Validação > Execução*) antes de gerar a resposta final. Isso garante que a documentação seja sempre consultada antes de formular o texto.
2.  **Few-Shot Prompting (Prompt com Exemplos):**
    Foram incluídos exemplos práticos de como o agente deve responder a duas situações distintas:
    *   *In-Scope:* Explicando o bloqueio de um colaborador sem certificação de PTA na obra, focando em ensinar o usuário.
    *   *Out-of-Scope:* Recusando-se a realizar cálculos de folha de pagamento e acionando o protocolo de transparência (redirecionamento para o Suporte N2).

### 🎯 Diretrizes Fundamentais do Agente
*   **Integridade:** Proibição absoluta de sugerir *workarounds* não documentados ou inventar funcionalidades.
*   **Transparência:** Reconhecimento claro de seus limites, com redirecionamento padrão para `exemplo@exemplo.com` em casos de falhas de integração ou dúvidas sistêmicas externas.

---

*Desenvolvido para avaliação de habilidades em Ferramentas de IA, Alta Performance e Criação de Produtos.*
