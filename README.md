# Imers-o_Alura
# Criação de Agentes de IA para gerar postagens no Instagram

## Aula 5 da Imersão Alura

**Aluno:** Alexandre Guerra  
**Data de Conclusão:** 01/06/2025

---

## Descrição do Projeto

Este projeto tem como objetivo a criação de um sistema de agentes de inteligência artificial que automatizam a geração de postagens para o Instagram. Utilizando tecnologias avançadas e o framework Google Gemini, o sistema é capaz de buscar informações relevantes, planejar conteúdo, redigir posts e revisar a qualidade do texto gerado.

## Agentes de IA

O sistema é composto por quatro agentes, cada um com uma função específica:

1. **Agente Buscador de Notícias**
   - **Função:** Utiliza ferramentas de busca do Google para coletar as últimas notícias relevantes sobre um tópico específico, focando em lançamentos atuais e populares.
  
2. **Agente Planejador de Posts**
   - **Função:** Organiza e elabora um plano de postagem com base nas notícias coletadas, garantindo que o conteúdo seja coeso e relevante para o público-alvo.

3. **Agente Redator do Post**
   - **Função:** Cria um rascunho engajador para o Instagram, utilizando o tema e os dados do plano de post como referência. O redator produz um conteúdo informativo, simples e com hashtags.

4. **Agente Revisor de Qualidade**
   - **Função:** Realiza a revisão do rascunho preparado pelo agente redator, verificando clareza, concisão e adequação ao tom desejado. O revisor sugere melhorias ou aprova o texto para publicação.

## Tecnologias Envolvidas

- **Python:** Linguagem de programação utilizada para desenvolvimento do projeto.
- **Google Gemini SDK:** Ferramenta da Google que possibilita a criação e utilização de modelos de IA.
- **Google Colab:** Ambiente de desenvolvimento que permite a execução de códigos Python de forma interativa.
- **Framework ADK do Google:** Utilizado para criar agentes de IA e suas interações.

## Fluxograma dos Agentes

```plaintext
  +-----------------------+
  | Agente Buscador      |
  | Busca notícias       |
  +----------+------------+
             |
             v
  +-----------------------+
  | Agente Planejador     |
  | Elabora plano de post |
  +----------+------------+
             |
             v
  +-----------------------+
  | Agente Redator        |
  | Cria rascunho        |
  +----------+------------+
             |
             v
  +-----------------------+
  | Agente Revisor        |
  | revisa o rascunho    |
  +-----------------------+

## ÍNDICE DOS BLOCOS:


Bloco 1: Instalação e Configuração da API
Bloco 2: Importação de Módulos e Configuração do Cliente
Bloco 3: Listagem de Modelos Disponíveis
Bloco 4: Teste Inicial do Modelo Gemini
Bloco 5: Configuração de Agentes e Funções Auxiliares
Bloco 6: Definição dos Agentes
Bloco 7: Execução do Sistema de Criação de Posts
Bloco 8: Função Principal para Coordenação do Ciclo de Agentes
Bloco 9: Adicionando Feedback e Melhoria Contínua

Conclusão

Este projeto demonstra como é possível utilizar a inteligência artificial para automatizar processos criativos, melhorando a eficiência e a qualidade das postagens em redes sociais como o Instagram. Com a implementação desses quatro agentes, é possível criar uma abordagem integrada que pode ser facilmente adaptada e expandida.

Contato
Em caso de dúvidas ou sugestões, entre em contato: [guerra7@gmail.com]
