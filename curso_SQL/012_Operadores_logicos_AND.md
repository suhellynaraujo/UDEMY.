/* Operadores lógicos 
OR => PARA QUE A SAÍDA DA QUERY SEJA VERDADEIRA, BASTA QUE APENAS UMA CONDIÇÃO SEJA VERDADEIRA
AND => PARA QUE A SAÍDA SEJA VERDADEIRA TODAS AS CONDIÇÕES PRECISAM SER VERDADEIRAS
*/

/* AND = E */

SELECT NOME, SEXO, ENDERECO FROM CLIENTE
WHERE
SEXO = 'M' AND ENDERECO LIKE '%RJ';

SELECT NOME, SEXO, ENDERECO FROM CLIENTE
WHERE
SEXO = 'F' AND ENDERECO LIKE '%ESTACIO';