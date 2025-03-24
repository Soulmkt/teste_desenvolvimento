Existe um arquivo PDF dentro da pasta com essas instruções.

Teste PHP, HTML Soulmkt 

Considerações

Este teste tem como objetivo avaliar a organização da aplicação, qualidade do código, qualidade dos testes, interpretação do que foi pedido, implementação e execução como um todo.

História do Usuário 

O usuário deseja enviar uma planilha de produtos no formato CSV para o servidor. O servidor irá ordenar os produtos em ordem alfabética pelo nome do produto e montar uma tabela HTML na tela contendo toda essa lista.

No momento de enviar a planilha, o usuário deseja informar se as colunas estão separadas por vírgula (',') ou ponto e vírgula (';'). Iremos fornecer os modelos de planilha que o usuário poderá enviar. 

A planilha que o usuário subir terá as colunas nome, codigo e preco, não necessariamente nesta ordem. Colunas adicionais devem ser ignoradas! 

Caso o preço do produto esteja negativo, o usuário deseja que a linha dessa tabela HTML seja pintada de vermelho. 

O usuário quer que nas linhas dessa tabela HTML haja um botão que copie os dados daquela linha (nome, código e preço), no formato JSON, para a área de transferência. Esse botão deve aparecer apenas para os produtos que CONTENHA PELO MENOS 1 (UM) número par no código do produto (coluna codigo). Por exemplo, se o código do produto for AD751DFG1 o botão não deverá aparecer já que existem números no código mas nenhum é par, porém se o código do produto for  AD756DFG1 o botão irá aparecer já que no código existe o número 6 que é par.

Critérios de Aceitamento 

Utilizar o envio do formulário HTML através de uma requisição AJAX (NÃO UTILIZAR O SUBMIT DO FORMULÁRIO).

Os dados precisam ser processados pelo servidor PHP.

Utilizar PHP 7 +.

A aplicação PRECISA utilizar orientação a objetos.

Os dados ordenados devem retornar para a tela em formato json e o HTML ser montado na tela via Javascript, Jquery ou outra tecnologia.

A informação se a linha da tabela HTML deve ser pintada de vermelho ou se o botão irá existir na tabela deve vir do servidor PHP.

Conter um passo a passo sobre como utilizar a aplicação num arquivo README.md na raiz do projeto.

Envio

Disponibilize o seu projeto no github para avaliação.
Compartilhe o link do seu projeto com os e-mails gilmar@soulmkt.com.br e marcos.paulo@soulmkt.com.br

Dica

Seja o mais detalhado possível ao elaborar cada commit para que possamos entender a sua linha de raciocínio.

Realize casos de teste com arquivos em formatos inválidos ou com colunas incompletas. (ex o cliente tentou subir um xml, ou enviou um CSV sem a coluna preco)

BOA SORTE
