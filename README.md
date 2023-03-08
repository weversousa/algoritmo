# Algoritmo

https://mermaid.js.org/syntax/flowchart.html

```mermaid
graph TD
A([Início]) --> B[Digite a nota do aluno]
B --> C{A nota é maior que 7?}
C --> |Sim| D[Aluno aprovado]
C --> |Não| E[Aluno reprovado]
D --> F[(Fim)]
E --> F[(Fim)]
```
