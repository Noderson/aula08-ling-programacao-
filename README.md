# Aula 08 - Linguagem de Programação

Esta pasta contém todos os exercícios da Aula 08 da disciplina de Linguagem de Programação:
## Estrutura da pasta

- exercicio1/
  - calculadora_modular.c
- exercicio2/
  - analise_array.c
- exercicio3/
  - manipulador_strings.c
- exercicio4/
  - gestao_notas.c


## Compilação dos programas

Para compilar os programas, você precisa ter um compilador C instalado (ex: GCC).

### Passo a passo:

1. Abra o terminal (Linux/Mac) ou prompt de comando (Windows).
2. Navegue até a pasta do exercício desejado:

   cd caminho/da/pasta/exercicioX

3. Compile o arquivo `.c`:

   gcc nome_do_arquivo.c -o nome_executavel

   - Exemplos:
     gcc calculadora_modular.c -o calculadora
     gcc analise_array.c -o analise_array
     gcc manipulador_strings.c -o manipulador_strings
     gcc gestao_notas.c -o gestao_notas
     gcc exercicio8.c -o exercicio8

4. Execute o programa:

   - Linux/Mac:
     ./nome_executavel
   - Windows:
     nome_executavel.exe

### Observações:

- Substitua `nome_do_arquivo.c` pelo arquivo real do exercício.
- Substitua `nome_executavel` pelo nome que deseja dar ao programa compilado.
- Alguns programas podem ter múltiplos arquivos `.c` ou `.h`. Compile todos juntos se necessário:

   gcc arquivo1.c arquivo2.c -o programa



