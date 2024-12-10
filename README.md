<p align="center">
  <img src="./images.png" alt="UNISANTOS" width="300" />
</p>

# Criptografia Blowfish para Estudos Teóricos e Práticos

## Descrição
O projeto é uma continuação do documento de Pesquisa Curricularizada de Graduação da Universidade Católica de Santos, envolvendo as matérias de Projeto de Algoritmos, Fundamentos da Computação II e Matemática Discreta. O projeto tem como objetivo pesquisar e entender o que é as Criptografias mais comuns (simétrica, assimétrica e hash) e seus contextos históricos. Nessa pesquisa focamos na criptografia Blowfish.

Link da documentação do projeto: [ALGORITMOS CRIPTOGRÁFICOS](https://docs.google.com/document/d/1eKZlc-bICpO1CRryWhqmSZMKzea8nvtQ/edit?usp=sharing&ouid=106154299811612627140&rtpof=true&sd=true)

## Funcionamento do código
Para rodar o código é necessários ter dois arquivos, um de output e um de input, os dois do tipo 'txt'. Eles devem estar dentro da mesma pasta do arquivo da Criptografia. Se houver algum erro no caminho do arquivo, "Crie os arquivos!", verifique a linha 262 e 263.

- O código foi a implementação da criptografia Blowfish na linguagem C, por se tratar de uma criptografia Simétrica, tanto a encriptação quanto a decriptação deve ser feita com a mesma chave;
- A chave tem um limite de 448 bits, 56 caracteres no máximo;
- Após inserir a chave indique se será Criptografar [1], Descriptografar [2];
- No input deve ter o texto que será criptografado , ou descriptografado, no output irá sair o resultado.