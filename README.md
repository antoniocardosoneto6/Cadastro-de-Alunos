# Cadastro de Alunos

Aplicação web desenvolvida em JavaScript para cadastrar alunos, calcular a situação de acordo com a média e realizar buscas pelo nome.

## Funcionalidades

- Cadastro de alunos e notas
- Validação do nome e da nota
- Exibição da média com uma casa decimal
- Classificação como aprovado ou reprovado
- Busca de alunos por nome
- Destaque visual para alunos aprovados e reprovados
- Mensagens para cadastro e campos inválidos
- Mensagem quando nenhum aluno é encontrado

O critério utilizado considera aprovados os alunos cuja média seja maior ou igual a 6.

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Como executar

Não é necessário instalar dependências.

1. Faça o clone do repositório:

```bash
git clone https://github.com/antoniocardosoneto6/Cadastro-de-Alunos.git
```

2. Entre na pasta do projeto:

```bash
cd Cadastro-de-Alunos
```

3. Abra o arquivo `index.html` em um navegador moderno.

Também é possível iniciar um servidor local:

```bash
npx serve .
```

## Como usar

1. Informe o nome do aluno.
2. Informe uma nota entre 0 e 10.
3. Clique em **Cadastrar**.
4. Consulte o aluno na tabela.
5. Utilize o campo **Buscar aluno** para filtrar os resultados pelo nome.

## Estrutura do projeto

```text
Cadastro-de-Alunos/
├── index.html
├── estilo.css
├── script.js
└── README.md
```

- `index.html`: estrutura da página e dos formulários
- `estilo.css`: estilos, cores e estados visuais
- `script.js`: cadastro, validação, busca e atualização da tabela
- `README.md`: documentação do projeto

## Licença

Este projeto ainda não possui uma licença definida.
