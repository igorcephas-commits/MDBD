# Banco de Dados Carrossel

## Sobre o projeto

Esta pasta contém os arquivos relacionados ao banco de dados do sistema Carrossel.

O banco foi desenvolvido em MySQL e foi utilizado para organizar as principais informações do sistema acadêmico, como alunos, responsáveis, professores, cursos, turmas, disciplinas, matrículas e boletins.

## Funcionalidades

- Armazenar os dados dos alunos.
- Armazenar dados pessoais e contatos.
- Controlar matrículas e turmas.
- Organizar cursos e disciplinas.
- Registrar professores e coordenadores.
- Armazenar informações de boletins e avaliações.
- Relacionar as diferentes informações por meio de chaves estrangeiras.

## Tecnologias utilizadas

- MySQL
- SQL
- brModelo
- phpMyAdmin

## Estrutura do projeto

Os arquivos desta pasta representam a modelagem e a estrutura do banco de dados.

Entre as principais tabelas estão:

- `ALUNOS`
- `DADOS_PESSOAIS`
- `RESPONSAVEIS`
- `TELEFONES`
- `MATRICULA`
- `TURMAS`
- `CURSOS`
- `DISCIPLINAS`
- `PROFESSORES`
- `BOLETINS`
- `AVALIACOES`
- `COORDENADORES`
- `CIDADES`
- `BAIRROS`
- `ESTADOS`

As tabelas são relacionadas por meio de chaves primárias e estrangeiras. Por exemplo, a tabela `ALUNOS` possui relacionamentos com dados pessoais e endereço. :contentReference[oaicite:0]{index=0}

## Como executar

Para utilizar o banco, é necessário ter o MySQL instalado, podendo ser utilizado o XAMPP e o phpMyAdmin.

O arquivo `.sql` pode ser importado pelo phpMyAdmin para criar o banco e suas tabelas.

Depois da criação do banco, a API PHP pode utilizar essas tabelas para cadastrar, consultar, editar e desativar os dados dos alunos.

## Autor : Igor Augusto do Nascimento Rodrigues 3ºDS
