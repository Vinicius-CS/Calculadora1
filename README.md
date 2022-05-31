[![Github Actions Status for

Vinicius-CS/Calculadora1](https://github.com/Vinicius-CS/Calculadora1/tree/master/.github/workflows/Integra%C3%A7%C3%A3o%20continua%2
0de%20Java%20com%20Maven/badge.svg)](https://github.com/Vinicius-CS/Calculadora1/actions)

[![Quality Gate
Status](https://sonarcloud.io/api/project_badges/measure?project=Calculadora1&metric=alert_status)](https://sonarcloud.io/sum
mary/new_code?id=Calculadora1)

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=Calculadora1&metric=coverage)](https://sonarcloud.io/
component_measures?id=Calculadora1&metric=coverage)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>
