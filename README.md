**Projeto de Gerenciamento de disciplinas para universidades**

**Descrição:**
Este projeto implementa um sistema de gerenciamento de horários de disciplinas de cursos de uma universidade. Ele permite a manipulação de cursos, disciplinas, professores e distribuição de disciplinas aos professores em cada ano letivo.

**Autores:**
- Bruna Feyh
- Andre Correa

**Data de Entrega:** 18 de outubro de 2023

**Modalidade:** Trabalho em grupo (máximo de 2 alunos por grupo)

**Idioma:** C

**Funcionalidades:**
1. Cadastro de cursos de graduação, contendo código, nome e área.
2. Cadastro de disciplinas, contendo código, nome, código do curso e série.
3. Cadastro de professores, contendo código e nome.
4. Associação de disciplinas a professores em cada ano letivo.
5. Interface de linha de comando para interação com o sistema.

**Operações de Inclusão em Lote:**
- O sistema permite a inclusão de registros em lote a partir de um arquivo de texto com a seguinte sintaxe:
  ```
  <tipo-item>;<codigo>;<campo1>;<campo2>;...;<campoN>
  ```
  Onde:
  - `<tipo-item>` pode ser C (curso), D (disciplina), P (professor) ou M (distribuição de disciplina).
  - `<campo1>;<campo2>;...;<campoN>` correspondem aos campos com informações referentes ao respectivo item.

**Exemplo de Conteúdo de Arquivo .txt para Inclusão em Lote:**
```
C;1;Ciencia da Computacao;E
C;2;Engenharia Eletrica;E
C;3;Engenharia Mecanica;E
C;4;Letras;H
C;5;Administracao;H
C;6;Enfermagem;B
C;7;Medicina;B
D;1;Algoritmos e Estrutura de Dados;1;2
D;2;Linguagens Formais e Automatos;1;2
D;3;Logica e Matematica Discreta;1;1
D;4;Projeto e Analise de Algoritmos;1;3
D;5;Inteligencia Artificial;1;4
D;6;Resistencia de Materiais;3;3
D;7;Circuitos Eletricos;2;2
D;8;Literatura Contemporanea;4;3
D;9;Gestao de Pessoas;5;4
D;10;Anatomia Humana;7;1
D;11;Farmacologia;7;4
P;1;Joao da Silva
P;2;Jose dos Santos
P;3;Carla Souza
P;4;Joaquim Almeida
P;5;Pedro Batista
P;6;Maria do Prado
P;7;Einstein
P;8;Euler
M;1;2023;8
M;2;2023;2
M;3;2023;2
M;4;2023;7
M;5;2023;7
M;6;2023;1
M;7;2023;5
M;1;2022;6
M;2;2022;3
M;3;2022;2
M;4;2022;3
M;5;2022;8
M;6;2022;1
M;7;2022;4
M;8;2022;3
M;9;2022;1
M;10;2022;7
M;11;2022;3
```

Este arquivo de lote contém registros para inclusão de cursos, disciplinas, professores e distribuição de disciplinas em anos letivos específicos.

**Formato de Execução:**
O programa é executado no prompt de comando do sistema operacional e interage com o usuário por meio de texto.

**Instruções para Compilação e Execução:**
1. Compile todos os arquivos fonte utilizando um compilador C compatível.
2. Execute o programa compilado no prompt de comando.

**Observações:**
- O programa permite operações de inclusão, remoção, consulta e listagem de cursos, disciplinas, professores e distribuição de disciplinas.
- As operações são realizadas de acordo com as opções fornecidas no menu de interação com o usuário.
- Os dados são armazenados em memória durante a execução do programa e podem ser salvos em um arquivo para persistência.

