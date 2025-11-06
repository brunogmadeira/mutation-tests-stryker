# Mutation Testing com Stryker Mutator

Este projeto utiliza a biblioteca **Stryker Mutator** para aplicar a técnica de *Mutation Testing* em testes unitários feitos com **Jest**.

O Mutation Testing altera propositalmente o código-fonte e executa os testes para verificar se eles são capazes de detectar os erros inseridos. Isso ajuda a medir a qualidade dos testes e identificar pontos não cobertos.

## Como rodar

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Execute os testes unitários normalmente:
   ```bash
   npm test
   ```

3. Rode o Mutation Testing:
   ```bash
   npx stryker run
   ```

4. Após rodar, o relatório HTML completo estará no seu terminal e em:
   ```
   reports/mutation/html/index.html
   ```

