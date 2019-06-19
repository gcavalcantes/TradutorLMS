# TradutorLMS

## Descrição geral
Este projeto tem o intúito de elaborar um tradutor para a linguagem LMS, seguindo certas especificações.

## Especificações gerais
O tradutor realiza uma análise léxica, síntatica, semântica e fazer a geração de código para a máquina hipotética. Isso significa que este software deve também possuir uma implementação de máquina hipotética e possibilitar a interpretação do código intermediário gerado.

## Características e detalhes
- Interface gráfica;
- Botão para carregamento de arquivo contendo o programa-fonte;
- Área de texto contendo o programa-fonte sendo analisado;
- Possibilidade de digitar o programa-fonte diretamente na interface (área de texto);
- Botões para fazer análise léxica, sintática e semântic, bem como, interpretação (execução);
- Após a análise léxica deverá ser apresentada uma tabela contendo os tokens identificadas. Essa tabela deve conter: código de token, lexema (string do token propriamente dita), classe(descrição da categoria a que pertence o token);
- Caso seja encontrado algum erro léxico, sintático ou semântico na compilação, deve ser apresentada na tela uma mensagem de erro adequada, bem como a linha correspondente no programa-fonte em que o erro foi encontrado;
- Se o programa-fonte informado pelo usuário estiver correto (léxico, sintático e semanticamente) deve ser gerado o respectivo código para a máquina hipotética (código intermediário);
- O software deve pertimir visualizar o código gerado para a máquina hipotética, contendo: endereço de instrução, memônico da instrução, operando 1 e operando 2;
- A máquina hipotética deve estar acoplada ao software de maneira que, a partir do menu ou de alguma barra de ferramentas, seja possível ao usuário executar o código gerado;
- O analisador semântico deve ser implementado em uma classe chamada "AnalisadorSemantico". Classes auxiliares poderão ser implementadas, no entanto, o tratamento das ações semânticas deverá ser efetuada nessa classe.

## Considerações para o projeto
Este projeto é desenvolvido tendo em mente o 