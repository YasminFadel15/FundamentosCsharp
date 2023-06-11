# Namespace
  - Divisões lógicas.
  - O ideal é ter apenas uma namespace e uma classe por arquivo.
  - Pode ser reutilizado e pode estar presente em diversos arquivos (tendo classes diferentes).

# Using
  - Faz as importações das bibliotecas que o programa vai utilizar, inclusive das namespaces.

# Variáveis
  - Pode usar um tipo ou a palavra reservada 'var' para a criação.
  - Se não informar o valor será aplicado um padrão.

# Constantes
  - Não podem ser alteradas.
  - Mais otimizadas que as variáveis.
  - Definição pela palavra reservada 'const'.
  - Se não inicializar, começa com zero.

# Comentarios
  - Uma linha: ctrl + k + c para comentar e ctrl + k + o para descomentar.
  - Mais linhas: barra + asterisco.
  - Notação XML: três barras (metadata).

# Tipos primitivos
  - Conhecidos como built-in types.
  - Tipos simples.
    * Byte: 8-bit (o sbyte permite valores negativos).
    * Inteiro: short/ushort (16-bit), int/uint (32-bit), long/ulong (64-bit) --> (o 'u' siginfica que não permite número negativos).
    * Real: float (32-bit, colocar 'f'), double (64-bit), decimal (128-bit, colocar 'm').
    * Boolean: 8-bit, true ou false.
    * Char: 16-bit, aspas simples.
    * String: a ocupação de memória depende do tamanho da string, aspas duplas.
    * Var: substitui o nome de um tipo.
  - Enumeradores.
  - Estruturas.
  - Tipos nulos.

# System
  - Tudo começa do tipo base System.
  - Todos os tipos estão dentro do system.

