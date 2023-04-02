# CHALLENGE FULL STACK LEKTO

### Faça um fork do repositório

## Contexto

A empresa Cad+ pretende comercializar um ERP para Hospitais. O ERP é comercializado por módulos sendo o módulo de cadastro de usuários comum em todas as versões do produto.

O módulo de cadastro está no processo de desenvolvimento e você faz parte da equipe que o está desenvolvendo.

O Cadastro de usuários deve seguir os seguintes critérios:

1. Um campo para CPF válido atentanndo a mask do input Ex: 999.999.999-99.
2. Um campo para NOME com no mínimo 4 caracteres.
3. Um campo para EMAIL.
4. Um campo para CELULAR atentanndo a mask do input Ex: (99) 99999-9999.
5. Um campo para SENHA deve conter no mínimo 8 carácteres sendo no mínimo 1 letras maiúsculas, 1 letra minúsculas, 1 caractere especiai e 1 números.
6. Cadastro de endereço com campo para CEP válido atentanndo a mask do input Ex: 99999-999, RUA, NÚMERO, BAIRRO, ESTADO, CIDADE e COMPLEMENTO.

Obs. Ao finalizar a digitação do CEP deve fazer uma busca na [API](https://viacep.com.br/). caso o CEP seja válido montar os dados nos inputs deixando boqueados a edição exceto o de numero e complemento.

## Requisitos Front

1. Possuir uma tela de LOGIN.
2. Possuir um dashboard onde listo todos os users
3. Possuir uma tela de cadastro e edição.
4. Possuir uma ação de excluir o usuário.
5. Pussuir uma tela de contato direcionando para um link de Whatsapp.

## Requiisitos Back

Construir uma API nos padrões REST onde:

1. Cadastrar novos usuários.
2. Editar usuários.
3. Deletar usuários.
4. Listar todos os usuários.
5. Buscar usuário por ID.

Ao realizar a ação de login o usuário deve ser encaminhado para o dashboard

## Requisitos Obrigatórios

1. [TypeScript](https://www.typescriptlang.org/)
2. [Context API](https://react.dev/learn/passing-data-deeply-with-context)
3. [Axios](https://axios-http.com/ptbr/docs/intro)
4. [React Query](https://tanstack.com/query/v3/)
5. [Formik](https://formik.org/)

## Requisitos Opcionais

1. Testes unitários com [JEST](https://jestjs.io/pt-BR/) ou [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

## Avaliação

Neste teste sera avaliado:

1. Organização de projeto
2. Componentização
3. Clean Code
4. Semântica do HTML e estruturação
5. Tipagem
