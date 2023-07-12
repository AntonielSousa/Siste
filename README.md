# Sistema de Adiantamento Salarial

Este é um sistema simples para gerenciar adiantamentos salariais. Permite adicionar, editar, excluir adiantamentos e emitir recibos em PDF.

## Funcionalidades

- Adicionar um novo adiantamento salarial, fornecendo o nome do funcionário, valor, descrição e data.
- Editar um adiantamento salarial existente.
- Excluir um adiantamento salarial da lista.
- Emitir um recibo em PDF para um adiantamento salarial.
- Fazer backup dos adiantamentos salariais.
- Restaurar backup dos adiantamentos salariais.

## Tecnologias Utilizadas

- HTML
- CSS (Bootstrap 5)
- JavaScript (Vanilla JS)
- jsPDF (para a geração de PDFs)

## Como Usar

1. Clone o repositório ou faça o download dos arquivos.

2. Abra o arquivo `index.html` em seu navegador.

3. Use o formulário para adicionar novos adiantamentos salariais. Preencha todos os campos e clique em "Adicionar Adiantamento".

4. Os adiantamentos salariais adicionados serão exibidos na tabela abaixo do formulário. Você pode editar ou excluir um adiantamento usando os botões correspondentes na tabela.

5. Para emitir um recibo em PDF para um adiantamento salarial, clique no botão "Recibo" na tabela. O recibo será gerado e salvo automaticamente.

6. Para fazer backup dos adiantamentos salariais, clique no botão "Fazer Backup". Os dados serão salvos no localStorage.

7. Para restaurar os adiantamentos salariais a partir de um backup anterior, clique no botão "Restaurar Backup". Os dados serão recuperados do localStorage e preencherão a tabela.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções de bugs ou novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

