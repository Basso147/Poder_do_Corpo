![](Aspose.Words.99cc83a3-5736-4915-8f2f-e02261c25489.001.png)

**Nome do Projeto: Poder Do Corpo Academia Fitness**

**Versão: 1.0**

**Data: 22/04/2024**

**Componente Curricular: Desenvolvimento de Sistemas 1**

**Nome Integrantes: Ana Caroline Debastiani e João Arthur Dutra Basso.**

**1. Introdução**

**1.1 Objetivo** 

O objetivo deste documento é fornecer uma visão geral do projeto de um sistema destinado a uma academia. Descrevendo a finalidade do projeto, as principais partes envolvidas, os requisitos principais, os diagramas de caso de uso, diagrama de classes e Canva do projeto.

**1.2 Escopo**

Este projeto busca a organização dentro de uma academia através de um sistema, mesmo com algumas atividades ainda manual como forma de pagamentos e pagamentos e busca de dados pelo CPF, como exemplos. O sistema se destina aos donos da própria academia para a organização, e também aos clientes da rede. 

**1.3 Definições, Acrônimos e Abreviações**

Nome fictício: Poder do Corpo
Razão Social: Poder do Corpo Academia Fitness LTDA



**1.4 Público-alvo**

O público-alvo será adultos e idoso, dos 30 aos 55 anos, pessoas cansadas e desanimadas com suas rotinas, trabalho e corpo.

**2. Descrição do Projeto**

O projeto irá apresentar funcionalidade na qual irá auxiliar na segurança, controle e demandas internas de uma academia, auxiliando em vendas, acessos, matrículas, treinos, relatórios, entre outras demandas.

**2.1 Visão Geral do Projeto**

A academia busca proporcionar saúde e a satisfação de nossos alunos através da prática de esporte físico. A academia irá proporcionar eventos mensais e semanais  incentivando as pessoas a prática de exercícios. 







**2.1.1 Canvas do Projeto**

![](Aspose.Words.99cc83a3-5736-4915-8f2f-e02261c25489.002.png)

**2.2 Stakeholders**

\- [João Arthur Dutra Basso] - [Gerente do Projeto e Membro da equipe de desenvolvimento]

\- [Ana Caroline Debastiani] - [Gerente do Projeto e Membro da equipe de desenvolvimento]

\- [Amora Pedrita Peres] - [Funcionária Recepcionista]

\- [Maicon Josef] - [Funcionário Recepcionista]

\- [João Pedro Visconde] - [Funcionário Recepcionista]

\- [Cecilia Aparecida Reis] - [Funcionária Professora]

\- [Rodrigo Rodolfo Ramos] - [Funcionário Professor]

\- [Elias Pedro Silva] - [Funcionário Professor]

**2.3 Objetivos**

O objetivo do projeto é auxiliar através de um sistema, donos de academias a otimizarem e controlarem de uma forma mais ampla o seu controle sobre o seu negócio.

**3. Principais Recursos e Funcionalidades**

` `O sistema Descrito terá as seguintes funcionalidades, direcionadas somente a Funcionários:

A funcionalidade da matrícula permite a inserção do nome completo, telefone para contato, email, data de nascimento, lesão (caso o aluno tenha), prontuário médico (caso o aluno tenha) e pagamento, no qual, solicitará a inserção da bandeira do cartão, observações, brindes, valor de pagamento e últimos quatro dígitos do cartão.

A funcionalidade treino permite a criação e edição dos treinos de cada aluno.

A funcionalidade caixa permite a abertura, retirada do valor igual ou inferior ao que foi inserido na abertura, suprimento (sem valor estipulado), despesa e fechamento do caixa.


A funcionalidade do aluno permite a visualização de seus treinos, planos e pagamentos, além de permitir a venda de produtos.

A funcionalidade de agendamento de aulas permite a criação, agendamento, edição e matrícula de alunos das aulas.

A funcionalidade relatório permite e extração de dados a partir da data atual referente a abertura e fechamento de caixa, criação de matrículas e frequência de alunos na academia.

**3.1 Requisitos Funcionais**

RF01 - O sistema deve permitir o acesso aos sistema a qualquer horário pelo funcionário;

RF02 - O sistema deve permitir a ao funcionário a inserção de documentos de imagem na matrícula do aluno;

RF03 - O sistema deve permitir efetuar matrículas após incluir nome completo, data de nascimento e telefone;

RF04 - O sistema deve permitir a visualização, abertura, fechamento, suprimento e retirada de caixa;

RF05 - O sistema deve permitir fazer a inscrição de alunos em diferentes modalidades de horários diferentes;

RF06 - O sistema deve permitir a visualização de matrículas e edição de matrículas;

RF07 - O sistema deve permitir a visualização e impressão de frequência;

RF08 - O sistema deve permitir a criação de aulas em diferentes modalidades e edição das tais;

RF09 - O sistema deve permitir a criação e alteração de treinos;

RF10 - O sistema deve permitir a alteração de professor designado a cada aluno;

RF11 - O sistema deve permitir a impressão de relatórios de frequência, matrícula e caixa;

RF12 - O sistema deve permitir a opção de pagamento através de cartão ou pix;

RF13 - O sistema deve permitir a o aluno realizar avaliação física.

**3.2 Requisitos Não Funcionais**

- ` `**Desempenho**:
  - ` `O sistema irá oferecer tempos de resposta rápidos para garantir uma experiência de usuário fluida.	
  - ` `Deve ser capaz de lidar com múltiplos usuários simultaneamente sem degradação significativa de desempenho.
- **Segurança**:
  - ` `Deve ser implementado um sistema robusto de autenticação e autorização para proteger os dados dos membros.
  - ` `Todas as transações financeiras devem ser criptografadas e protegidas contra acesso não autorizado.
- **Usabilidade**:
  - A interface do usuário deve ser intuitiva e fácil de usar, mesmo para membros sem experiência técnica.
  - Deve ser fornecida documentação abrangente e suporte técnico para ajudar os usuários a navegar pelo sistema.
- **Escalabilidade**:
  - O sistema deve ser capaz de lidar com o crescimento futuro da base de membros e das operações da academia sem grandes atualizações de infraestrutura.
- **Compatibilidade:**
  - Deve ser compatível com uma variedade de dispositivos e navegadores web para garantir acessibilidade em diferentes plataformas.


**4. Diagrama de Caso de Uso**

![](Aspose.Words.99cc83a3-5736-4915-8f2f-e02261c25489.003.png)




**4.1 Descrição de Caso de Uso**
### <a name="_4e7corccx54x"></a>**1)Caso de Uso:** Gerar Relatório de Frequência
**Objetivo:** Gerar um Relatório de Frequência dos funcionários 

**Atores:** Funcionário

**Pré-condição:** O sistema deve estar disponível on-line e o funcionário deve estar logado no sistema com usuário e senha válidos.

**Fluxo de Eventos:**

Funcionário: Acessar a página de relatórios.

Funcionário: Acessar a página de relatórios de Frequência

Sistema: Retorna a tela com o Relatório de Frequência

**Pós-condição:** O relatório de frequência deve ter sido gerado e apresentado ao funcionário.

**Caso de Uso:** Manter Aluno

**Objetivo:** Realizar o gerenciamento dos dados dos alunos, incluindo cadastro, edição, exclusão e consulta.

**Atores:**Administrador

**Pré-condição:** O sistema deve estar disponível on-line e o administrador deve estar logado no sistema com usuário e senha válidos.

**Fluxo de Eventos:**

Administrador: Acessa o link para gerenciar alunos.  

Administrador: Acessa o link para cadastrar, editar, excluir ou consultar um aluno.

**Se for cadastrar:**

Sistema: Retorna a tela com o formulário de cadastro de aluno.  

Administrador: Informa os dados do aluno (nome, data de nascimento, turma, etc.).  

Administrador: Clique em "Salvar Aluno".  

Sistema: Valida os dados informados e grava o novo aluno no sistema.






**Se for editar:**

Sistema: Retorna a lista de alunos cadastrados.  

Administrador: Seleciona o aluno que deseja editar.  

Sistema: Retorna a tela com o formulário preenchido com os dados do aluno.  

Administrador: Altera os dados necessários.  

Administrador: Clique em "Salvar Alterações".  

Sistema: valida os dados e atualiza o cadastro do aluno.

**Se for excluir:**

Sistema: Retorna a lista de alunos cadastrados.  

Administrador: Seleciona o aluno que deseja excluir.  

Administrador: Confirma a exclusão.  

Sistema: Exclui o cadastro do aluno.

**Se for consultar:**

Sistema: Retorna a lista de alunos cadastrados.  

Administrador: Seleciona o aluno para visualizar detalhes.  

Sistema: Apresenta os detalhes do aluno selecionado.

**Pós-condição:** O aluno deve ter sido cadastrado, editado, excluído ou consultado conforme a ação realizada pelo administrador.






















**5. Diagrama de Classes**

![](Aspose.Words.99cc83a3-5736-4915-8f2f-e02261c25489.004.png)












**6. Cronograma e Entrega**

![](Aspose.Words.99cc83a3-5736-4915-8f2f-e02261c25489.005.png)

**7. Riscos e Mitigação**

Os principais riscos são em casos de invasão, plágio de código ou falta de contato com a internet, na qual não irá funcionar o sistema. Estamos em fase de implementação de um sistema a mais de segurança na qual irá fiscalizar cada atividade no sistema.








**8. Custos e Orçamento**

Estimativa de custos iniciais:

- Aluguel: R$5.500,00/mês
- salários: Professores: 15,00 R$/h Atendentes:R$1.412,00/mês
- Água/Luz:R$ 1.000,00/mês
- equipamentos: R$500,00/mês
- estoque insumos: R$250,00/mês
- Uniformes: R$500,00/mês





**9. Considerações Finais**

Este documento de visão fornece uma visão geral do projeto Poder do Corpo Academia Fitness. Ele descreve a finalidade, os principais stakeholders, os requisitos principais, os 

Diagramas de caso de uso, diagrama de classes e protótipos de possíveis telas para o sistema. Este documento servirá como base para o desenvolvimento do projeto, auxiliando na compreensão e alinhamento das partes interessadas.



**Confira o Sistema no link abaixo:**

<https://www.figma.com/design/Ll9EeZ5UH9iyTmzOnRwNi5/Sistema-Academia?node-id=1-16&t=HzVa6L39IoXHfV7l-1> 

