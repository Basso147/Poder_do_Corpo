# 3. Principais Recursos e Funcionalidades #

` `O sistema Descrito terá as seguintes funcionalidades, direcionadas somente a Funcionários:

A funcionalidade da matrícula permite a inserção do nome completo, telefone para contato, email, data de nascimento, lesão (caso o aluno tenha), prontuário médico (caso o aluno tenha) e pagamento, no qual, solicitará a inserção da bandeira do cartão, observações, brindes, valor de pagamento e últimos quatro dígitos do cartão.

A funcionalidade treino permite a criação e edição dos treinos de cada aluno.

A funcionalidade caixa permite a abertura, retirada do valor igual ou inferior ao que foi inserido na abertura, suprimento (sem valor estipulado), despesa e fechamento do caixa.


A funcionalidade do aluno permite a visualização de seus treinos, planos e pagamentos, além de permitir a venda de produtos.

A funcionalidade de agendamento de aulas permite a criação, agendamento, edição e matrícula de alunos das aulas.

A funcionalidade relatório permite e extração de dados a partir da data atual referente a abertura e fechamento de caixa, criação de matrículas e frequência de alunos na academia.

## 3.1 Requisitos Funcionais ##

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

## 3.2 Requisitos Não Funcionais ##

- ## Desempenho: ##
  - ` `O sistema irá oferecer tempos de resposta rápidos para garantir uma experiência de usuário fluida.	
  - ` `Deve ser capaz de lidar com múltiplos usuários simultaneamente sem degradação significativa de desempenho.
- ## Segurança: ##
  - ` `Deve ser implementado um sistema robusto de autenticação e autorização para proteger os dados dos membros.
  - ` `Todas as transações financeiras devem ser criptografadas e protegidas contra acesso não autorizado.
- ## Usabilidade: ##
  - A interface do usuário deve ser intuitiva e fácil de usar, mesmo para membros sem experiência técnica.
  - Deve ser fornecida documentação abrangente e suporte técnico para ajudar os usuários a navegar pelo sistema.
- ## Escalabilidade: ##
  - O sistema deve ser capaz de lidar com o crescimento futuro da base de membros e das operações da academia sem grandes atualizações de infraestrutura.
- ## Compatibilidade: ##
  - Deve ser compatível com uma variedade de dispositivos e navegadores web para garantir acessibilidade em diferentes plataformas.