DESAFIO-QA-BEEDOO-2026
Descrição do Projeto

Este repositório foi criado para documentar a exploração e os testes realizados na aplicação proposta no desafio técnico QA Beedoo 2026.

O objetivo foi analisar o funcionamento do sistema, identificar seus principais fluxos e registrar cenários de testes que validam o comportamento da aplicação.

A aplicação aparenta ser um sistema simples de gerenciamento de cursos, permitindo cadastrar cursos e validar diferentes tipos de entradas de dados no formulário.

Objetivo da Aplicação

O sistema tem como objetivo permitir o cadastro e gerenciamento de cursos dentro de uma plataforma educacional.

Entre as funcionalidades observadas estão:

Cadastro de novos cursos

Validação de campos obrigatórios

Verificação de dados inválidos

Exclusão de cursos cadastrados

Essas funcionalidades garantem que apenas dados válidos sejam registrados no sistema.

Principais Fluxos da Aplicação

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

Cadastro de Curso

Fluxo básico para adicionar um novo curso ao sistema.

Passos:

Acessar o sistema

Inserir o nome do curso

Clicar em salvar

Resultado esperado:

O curso deve ser cadastrado com sucesso no sistema.

Validação de Campo Obrigatório

O sistema valida se o campo de nome do curso foi preenchido.

Passos:

Acessar o sistema

Tentar cadastrar um curso sem nome

Clicar em salvar

Resultado esperado:

O sistema deve apresentar mensagem de erro informando que o campo é obrigatório.

Validação de Dados Inválidos

O sistema verifica se o nome do curso contém caracteres válidos.

Passos:

Acessar o sistema

Inserir caracteres inválidos

Clicar em salvar

Resultado esperado:

O sistema deve impedir o cadastro e informar que o campo é inválido.

Exclusão de Curso

Permite remover um curso previamente cadastrado.

Passos:

Acessar o sistema

Cadastrar um curso

Salvar

Clicar no botão excluir

Resultado esperado:

O curso deve ser removido da lista.

Estratégia de Testes

A estratégia utilizada foi baseada em:

Testes funcionais

Validação de entradas

Testes positivos e negativos

Exploração manual da aplicação

Isso permite verificar se o sistema responde corretamente a diferentes cenários de uso.

A exploração da aplicação permitiu identificar os principais fluxos de cadastro e validação de cursos.

Conclusão
Os testes documentados ajudam a garantir que o sistema funcione corretamente e que entradas inválidas sejam tratadas adequadamente.
