# bancodeDados

Link dos exercícios referente ao modelo lógico: https://drive.google.com/file/d/1Fhr1pV75HBphI8CqCq7hQ2w8_RDuYL5r/view?usp=drive_link

O que é um Banco de Dados
É um sistema estruturado para armazenar, organizar e recuperar grandes volumes de informações de forma rápida e segura. Ele funciona como o cérebro de sites e aplicativos, guardando dados como usuários, senhas, produtos e mensagens, sendo gerenciado por softwares especializados conhecidos como SGBD (Sistemas de Gerenciamento de Banco de Dados). 

Modelos Logico
É uma representação estruturada que traduz o modelo conceitual (regras de negócio) para uma linguagem que o Sistema Gerenciador de Banco de Dados (SGBD) entende, mapeando entidades e relacionamentos em tabelas, colunas, chaves primárias, estrangeiras e tipos de dados

Tabela
É uma estrutura que armazena dados de forma organizada em linhas (registros) e colunas (atributos). Semelhante a uma planilha eletrônica, ela serve para agrupar informações de um mesmo tema (como "Clientes" ou "Produtos"), sendo a unidade básica de armazenamento em bancos relacionais.

Campo da Tabela 
É a unidade básica onde uma informação específica é armazenada. Em termos práticos, ele corresponde a cada coluna da tabela (como "Nome", "Data" ou "Valor"), onde são inseridos os dados que formam os registros (as linhas).

Tipo dos Dados
Define a natureza o formato e o tamanho da informação que cada coluna de uma tabela pode armazenar como números textos datas ou valores lógicos servindo para organizar as informações garantir que nenhum dado incorreto seja inserido e preparar a estrutura para a criação do banco de dados real.
No modelo conceitual, o nome, CPF, telefone e outras características são chamados de atributos.
Já no modelo lógico, esses atributos viram

Tabela Tamanho
Refere-se à capacidade ou comprimento máximo definido para um atributo (coluna). Ele indica a quantidade máxima de caracteres (em textos) ou de dígitos (em números) que aquele campo pode armazenar.

Chave Primaria(PK)
É um identificador único para cada linha ou registro em uma tabela de banco de dados. Ela funciona como uma "identidade" inconfundível, garantindo que não existam dados duplicados e que nenhuma informação fique sem identificação

Chave Estrangeira(FK)
É um campo utilizado para criar ligação entre tabelas no banco de dados. Ela pega a chave primária de uma tabela e utiliza em outra para conectar as informações. Por exemplo, em uma tabela de empréstimos, podemos usar o CPF do leitor e o ISBN do livro para saber qual leitor pegou determinado livro emprestado.

Relacionamento
As três linhas significam que aquela tabela aceita vários registros (como uma lista de compras com vários itens). Do outro lado, a bolinha e o traço significam que a ligação é opcional (pode começar com zero), mas se existir, aceita no máximo um (como um produto que pode ou não ter um cupom de desconto específico).


Explicando as opções do MySQL Workbench
Essas opções aparecem durante a criação dos campos no banco de dados.
PK – Primary Key (Chave Primária)
Identifica cada registro de forma única dentro da tabela.
Quando marcar?
Quando o campo será o identificador principal da tabela.
NN – Not Null
O campo não pode ficar vazio.
Quando marcar?
Quando a informação for obrigatória.
UQ – Unique
Não permite valores repetidos.
Quando marcar?
Quando a informação deve ser única no sistema.
B – Binary
Utilizado para armazenar dados binários.
Quando marcar?
Em situações específicas envolvendo arquivos ou dados binários.
UN – Unsigned
Não permite números negativos.
Quando marcar?
Quando o valor nunca poderá ser negativo.
ZF – Zero Fill
Completa números automaticamente com zeros à esquerda.
Quando marcar?
Quando desejar padronizar números visualmente.
AI – Auto Increment
O valor é gerado automaticamente pelo banco de dados.
Quando marcar?
Normalmente em campos identificadores.
G – Generated
Campo gerado automaticamente pelo banco.
Quando marcar?
Quando o valor será calculado automaticamente.
Default/Expression
Define um valor padrão para o campo.
Quando marcar?
Quando desejar que o banco preencha automaticamente um valor inicial.
Exemplos comuns de uso
status
data
quantidade
ativo/inativo
