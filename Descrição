### APS ÁLGEBRA LINEAR - PROFESSOR MANUEL - UNICARIOCA

### Descrição do Projeto de Criptografia e Descriptografia com Matrizes

#### **Visão Geral**
Este projeto desenvolve um sistema básico para criptografar e descriptografar palavras usando operações matriciais. Ele converte palavras em matrizes numéricas, aplica uma matriz de criptografia e reverte o processo para recuperar a palavra original.

#### **Funcionalidades**
1. **Verificação de Entrada**
   - Função `apenasLetras(palavra)` valida que a palavra contém apenas letras e espaços.

2. **Matrizes Utilizadas**
   - **Matriz de Criptografia**: Matriz fixa 3x3 utilizada para criptografar dados.
     ```python
     matrizCriptografia = np.array([[1, 0, 1], [1, 1, 1], [0, 2, -1]])
     ```
   - **Matriz Inversa**: Calculada a partir da matriz de criptografia para a descriptografia.

3. **Conversão entre Letras e Números**
   - **Conversão**: Letras são convertidas para números utilizando um dicionário.
   - **Desconversão**: Números são convertidos de volta para letras.

4. **Entrada do Usuário**
   - O usuário deve fornecer uma palavra de exatamente 6 caracteres. Se a palavra for menor, é preenchida com espaços para atingir o comprimento necessário.

5. **Processo de Criptografia**
   - A palavra é convertida em uma matriz de números.
   - Esta matriz é multiplicada pela matriz de criptografia, resultando na matriz criptografada.

6. **Processo de Descriptografia**
   - A matriz criptografada é multiplicada pela matriz inversa da matriz de criptografia.
   - Os números resultantes são convertidos de volta em letras, revelando a palavra original.

#### **Melhorias Potenciais**
1. **Complexidade da Matriz**
   - Utilizar matrizes de ordem superior ou valores mais variados para aumentar a segurança contra ataques de força bruta.

2. **Substituição de Caracteres**
   - Adicionar uma etapa de substituição de caracteres, como a cifra de César, antes da criptografia para maior segurança.

#### **Exemplo de Uso**
- O usuário insere a palavra "SECURE".
- A palavra é convertida em uma matriz numérica e criptografada.
- A matriz criptografada pode ser revertida para a palavra original através da matriz inversa, demonstrando o processo de descriptografia.

Este projeto ilustra uma abordagem introdutória à criptografia utilizando matrizes, servindo como base para a exploração de conceitos mais avançados em criptografia e segurança da informação.
