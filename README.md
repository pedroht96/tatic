Funcionamento do programa:

1)Após a execução do programa o usuario deve digitar: armazenador (caminho que se encontra o arquivo .txt para ser lido) com um espaçamento;

2)Quando o programa terminar de ler o arquivo a linha sera quebrada, e assim podera prosseguir com a execução do programa;

3)Para acionar a função "buscador" digite buscador (primeira data) (segunda data) (identificador do usuario(opcional)) e as datas dentro do itervalo digitado serão exibidas no console.

Explicações técnicas do código:

1)Para a indexação foi indexado primeiro cada data contida no arquivo e convertido para o tipo de data normal (DateTime) - arquivo Registro.cs

2)Foi feito um dicionaro de dicionario onde o mais externo contém um numero que representa o indice que será escolhido em codigo e um mais interno que é uma representação do evento, um evento está associado a mais de um usuario, portanto será um indice secundario.No armazenamento dos dados no disco, as variavéis foram escolhidas de acordo com cada registro, para o ano e milissegundos foi usado o tipo "UInt16" e os demais foi representa por tipo "byte" - arquivo Registros.cs

3)Explicar o buscador:
