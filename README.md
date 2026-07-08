# Trabalho Final de Análise de Sobrevivência

Repositório para trabalho final da matéria Análise de Sobrevivência, como parte do programa de Pós-Graduação em Estatística pela Universidade de Brasília. Alunos Guilherme Braga e Vinicius Paiva. Entrega limite para 13 de julho de 2026.

Link para o repositório: https://github.com/gui1080/trabalho_final_analise_de_sobrevivencia

## Arquivos

No notebook *visualizacao_bs.Rmd* tem visualizações simples da Birnbaum-Saunders, junto da instanciação de sua reparametrização.

## Fonte do Dataset

Feigl, P. and Zelen, M. (1965) Estimation of exponential survival probabilities with concomitant information. Biometrics, 21(4), 826-838. 

Conforme usado no Artigo: LEÃO, Jeremias; LEIVA, Víctor; SAULO, Helton; TOMAZELLA, Vera. A survival model with Birnbaum–Saunders frailty for uncensored and censored cancer data. Brazilian Journal of Probability and Statistics, v. 32, n. 4, p. 707–729, 2018. DOI: 10.1214/17-BJPS360.

Esse dataset é referente a pacientes com leucemia, incluindo variáveis explicativas e pacientes censurados. Obtido via comando data(cancer, package="survival") no R.
