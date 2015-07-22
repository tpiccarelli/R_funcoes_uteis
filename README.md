# R_funcoes_uteis

eval(): evaluate an R expression in a specific env
  quote(): returns written argument
USE: eval(quote)

assign(): assign a value to a name in an environment
maybe do the same thing as eval(quote)


deparse(substitute(x)): retorna um objeto (vetor de caracteres de extensão unitária) com nome idêntico ao do objeto x original


oanda.currencies: Download Currency and Metals Data from Oanda.com

proc.time(): registra instante (útil para medir processos de início/fim)
Ex.:  no início algoritmo, cria objeto t0 <- proc.time()
      no fim do algoritmo, cria objeto t1 <- proc.time()
  
