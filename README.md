# Como usar
Crie um arquivo de modelo de contrato no formato .docx e adicione os códigos de referência que deseja substituir pelos dados pessoais. Por exemplo, se você deseja substituir o nome de uma pessoa no contrato, pode adicionar o código de referência XXXX no lugar do nome.
Crie um arquivo de informações no formato .xlsx ou .xls com uma linha para cada pessoa e as colunas correspondentes aos dados pessoais que deseja adicionar ao contrato. Por exemplo, se você deseja adicionar o nome e o endereço de uma pessoa, deve ter as colunas "Nome" e "Endereço".
Execute o script Python e os contratos serão gerados automaticamente. Os contratos serão salvos na mesma pasta em que o script está sendo executado, com o nome "Contrato - Nome da Pessoa.docx".

## Observações
Certifique-se de que o arquivo de modelo de contrato e o arquivo de informações estão no formato correto e contêm as informações necessárias.
O script substituirá apenas os códigos de referência presentes no arquivo de modelo. Se um código de referência não existir no arquivo, ele não será adicionado.
O script não verifica se os códigos de referência no arquivo de modelo correspondem aos campos no arquivo de informações. Certifique-se de que os códigos de referência no arquivo de modelo correspondem aos campos corretos no arquivo de informações.
