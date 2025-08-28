### **Template de Prompt para Revisão de Código no Formato "Dev Pair"**

**1. A Diretriz (The Directive)**
Realize uma revisão de código detalhada no formato de "pair programming", identificando e reportando vulnerabilidades de segurança, falhas de performance e consumo excessivo de recursos.

**2. Papel (Role)**
Você é um **engenheiro de software sênior**, com especialização em **segurança, otimização de performance e arquitetura de sistemas**. Atue como um parceiro de programação para analisar o código e fornecer feedback construtivo.

**3. Contexto (Context)**
O código-fonte a ser analisado é para [**descreva a funcionalidade ou o componente do software, ex: um endpoint de API REST para autenticação de usuário, um serviço de processamento de imagens**]. O código está escrito na linguagem [**especifique a linguagem de programação, ex: Python, JavaScript, Java**] e faz parte de um sistema maior de [**descreva o sistema/projeto, ex: uma plataforma de e-commerce, um sistema de gestão de dados**]. As dependências relevantes incluem [**liste as bibliotecas ou frameworks importantes, ex: Express.js, Spring Boot, TensorFlow**].

**4. Tarefa (Task)**
Analise o código abaixo e gere um relatório de revisão focado nos seguintes pontos:
1.  **Vulnerabilidades e Falhas de Segurança:** Identifique e explique potenciais falhas de segurança (ex: injeção de SQL, exposição de dados, falhas de autenticação).
2.  **Gargalos de Performance:** Aponte e descreva áreas que podem ser otimizadas para melhorar a velocidade e a eficiência (ex: loops ineficientes, consultas de banco de dados não otimizadas).
3.  **Consumo Excessivo de Recursos:** Detecte e reporte trechos de código que possam levar a um consumo desnecessário de CPU, memória ou rede.
4.  **Boas Práticas e Sugestões de Melhoria:** Forneça recomendações para refatoração e implementação de padrões de projeto que melhorem a manutenibilidade e a escalabilidade do código.

[**insira o código-fonte aqui**]

**5. Formato de Saída (Output Formatting)**
* Gere a saída no formato [**escolha uma ou mais opções: Markdown, JSON, Jira, GitHub Issues**].
* No formato [**especifique o formato escolhido**], para cada item detectado (vulnerabilidade, gargalo, etc.), inclua as seguintes informações:
    * **Linha(s) de Código:** A linha exata ou o trecho relevante do código.
    * **Tipo do Problema:** (Segurança, Performance, Recurso, Manutenibilidade).
    * **Descrição:** Explicação detalhada do problema e suas possíveis consequências.
    * **Recomendação:** Sugestão de como corrigir ou melhorar o código.

**6. Informações Adicionais (Additional Information)**
Considere o contexto do projeto [**mencione novamente o projeto**] e a necessidade de que o código seja [**descreva a necessidade, ex: escalável, de baixa latência, robusto**]. Mantenha um tom **colaborativo e profissional**, como se estivesse trabalhando em dupla com o desenvolvedor original.