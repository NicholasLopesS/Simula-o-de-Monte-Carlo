# Simulacao de Monte Carlo
Trabalho realizado na UEM como atividade final

Sou aluno de Estatística na UEM e realizei um trabalho final da disciplina Estatística Computacional II da graduação de Estatística da UEM, 
o projeto tinha como objetivo simular 9 cenários possíveis com diferentes valores de parâmetros permutados e encontrar o que tinha o menor Viés 
e EQM do EMV de uma das variações da Weibull, sendo escolhida a Weibull Inversa. 
E por fim, usar os melhores parâmetros como chute inicial para tentar ajustar o modelo em uma variável do banco de dados referente ao perfil de 
leucócitos de um rol de espécies de pássaros nativos da Europa Central.
Após a realização de 100 mil simulações, foi descoberto que os melhores cenários foram, com Alpha e Theta, respectivamente: o 1 (1 e 1), o 4 (1 e 2), 
e o 7 (1 e 3). No entanto, o escolhido foi o 1 para a tentativa de ajustá-lo. 
Foi possível então concluir que a Weibull Inversa não se ajusta perfeitamente, porém, quando comparada com a Exponencial e com a própria Weibull, 
e usando os mesmos parâmetros, pode-se concluir que a Inversa tem o melhor desempenho dentre as três.
