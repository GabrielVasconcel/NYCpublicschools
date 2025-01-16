# NYCpublicschools
Projeto em Python que demonstra conhecimentos de consultas, criações de tabelas e junções para responder perguntas sobre os dados. Realizado a partir de um projeto atividade do Datacamp, no qual foram fornecidos os dados e propostos os parâmetros para realização do projeto.

Perguntas a serem respondidas:

Quais escolas de NYC têm o melhor resultado em matemática?

    O melhor resultado em matemática são 80% da pontuação máxima de 800 para matemática. Os resultados foram salvos em um DataFrame pandas best_math_schools, possuindo as colunas "school_name" e "average_math", ordenadas por "average_math" de forma decrescente. 

Quais as 10 melhores escolas baseada em pontuação SAT combinada? 

    O resultado for salvo em um DataFrame pandas top_10_schools com as colunas "school_name" e uma nova coluna calculada "total_SAT", com resultados ordenados por "total_SAT" em ordem decrescente.

Qual bairro tem o maior desvio padrão na pontuação SAT combinada?

    O resultado foi salvo em um DataFrame largest_std_dev de uma linha. O DataFrame possui as colunas: "borough" - O nome do bairro com maior desvio padrão.

    "num_schools" - O número de escolas no bairro

    "average_SAT" - A média de "total_SAT"

    "std_SAT" - O desvio padrão de "total_SAT"

    Todos valores numéricos foram arredondados para 2 casas decimais