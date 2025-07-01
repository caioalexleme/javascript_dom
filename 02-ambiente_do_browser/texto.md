## Ambiente do Browser

- O JavaScript foi criado originalmente para web.
- Já vimos como inserir numa página web
- O ambiente onde o JS é executado disponibiliza funcionalidades extra.

## BROWSER

    (para além de interpretar HTML e CSS...)

    window
    |
    |_ DOM (Documente Object Model) - Acesso aos elementos de HTML que existem na página
        O DOM representa o conteúdo da página na forma de objetos que podemos modificar
        O 'document' é o principal ponto de entrada para modificar o conteúdo do HTML.

    |_ BOM (Browser Object Model) - Contém objetos adicionais para manipular o browser, excepto o documento HTML.
        Exemplo: mavigator permite obter informações do sistema.
        location permite let a URL atual e redirecionar para outra página

    |_ JavaScript Core - os mecanismos internos do JavaScript (sintaxe, arrays, objetos, classes, etc.)