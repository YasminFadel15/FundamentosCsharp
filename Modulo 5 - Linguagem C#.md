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
    * Object: tipo genérico que recebe qualquer valor ou objeto, não possui intellisense (ajuda do editor).
  - Enumeradores.
  - Estruturas.
  - Tipos nulos.
    * Void: sem retorno.
    * Null: diferente de zero ou string vazio, é nulo. Se atribuir 'null' a um objeto, colocar '?' na frente do tipo.

# System
  - Tudo começa do tipo base System.
  - Todos os tipos estão dentro do system.

# Alias
  - Apelido que todo tipo no .NET tem.
  - Recomendado usar o alias ao invés do tipo.

# Conversão implícita
  - Podem ser executadas apenas com passagem de dados de tipos compatíveis.
  - Chamada também de cast.

# Conversão explícita
  - Obrigatoriamente informar o tipo entre parênteses antes da atribuição.
  - Usada quando os tipos não são compatíveis.

# Parse
  - Método presente em todo tipo primitivo.
  - Extensão usada para converter um caractere ou string para um tipo qualquer.
  - Exemplo: int inteiro = int.Parse("100");

# Convert
  - Classe usada para converter vários tipos de valor para outros tipos.
  - Informar o tipo na chamada da conversão.
  - Exemplo: int inteiro = Convert.ToInt32("100");

# Métodos/funções
  - Possui um retorno, um nome e parâmetros em sua assinatura.
  - Começam sempre com maiúscula.
  - Pode ter parâmetros opcionais que vem por último e devem ser inicializados.

# Tipos de referência e valor
  - Os tipos de valor armazenam os dados (struct).
  - Os tipos de referência armazenam o endereço dos dados (class), então ao atribuir ele para outra variável, não cria uma cópia, e sim aponta para o mesmo valor.

# Structs
  - Armazenam tipos de dados.
  - Nome sempre em maiúsculo, tanto da struct quanto das propriedades.
  - Criado a partir da palavra 'new'.
  - As propriedades devem ser definidas (public, private, protected).
  - Exemplo: var product = new Product();
    product.Id = 1;
    product.Title = "Casa";
  - Método construtor é um método com o mesmo nome da struct que não retorna nada. Eles facilitam a criação da estrutura.

# Enumeradores
  - Usado para uma melhor visualização do código.
  - Substituem o uso de inteiros.
  - Usado em dados fixos, começa com 'E'.
  - Exemplo: enum EEstadoCivil { ... }
  - Pode ser usado como tipo.
