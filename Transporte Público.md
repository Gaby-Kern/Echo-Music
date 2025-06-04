* ## Transporte Publico

# O que medimos:  
Realizamos uma análise comparativa entre diferentes rotas de transporte público (metrô e ônibus), considerando:  
Eficiência das rotas, por meio da média de tempo de viagem.  
Capacidade de transporte, através da estimativa de passageiros por linha e sentido.  
Confiabilidade operacional, observando a frequência de status problemáticos (linhas interrompidas ou atrasadas).  
Nosso objetivo foi identificar quais rotas oferecem as melhores alternativas em termos de rapidez, conforto e segurança operacional para os usuários do sistema.  

# Parâmetros analisados:  
linha\_transporte  
sentido  
soma de passageiros\_estimados  
média de tempo de viagem  
status\_linha  
id\_viagem  
status problematico  

#Gráficos:  
**1\. Gráfico de barras: Tempo médio de viagem por linha**  
Configuração:
Eixo X: linha\_transporte  
Eixo Y: média de tempo\_viagem\_min  
Insight:
Metrô é mais rápido que ônibus nas rotas analisadas.  
---
**2\. Gráfico de barras: Lotação estimada por linha e sentido**  
Configuração:
Eixo X: linha\_transporte  
Eixo Y: média ou total de passageiros\_estimados  
Dimensão detalhada: sentido  
Insight:
Metrô transporta mais passageiros que ônibus, em ambos os sentidos.  
---
**3\. Gráfico de barras: Status das linhas**  
Configuração:
Eixo X: linha\_transporte  
Eixo Y: id\_viagem  
Dimensão detalhada: status\_linha  
Insight:
Ônibus apresentam mais interrupções e atrasos que o metrô.  
**4\. Gráfico de pizza**  
Configuração:
Eixo X: linha\_transporte  
Eixo Y: status problematico  
Insight:
Todas as linhas possuem aproximadamente 20% de ocorrências problemáticas.  
---

# Conclusão:  
Com base na Análise de Rotas Alternativas, conseguimos identificar padrões importantes para a tomada de decisão sobre mobilidade urbana.  
As linhas de metrô demonstraram maior eficiência em termos de tempo médio de viagem, sendo mais rápidas que as linhas de ônibus.  
Apesar da eficiência, o metrô também apresentou uma lotação estimada superior tanto no sentido de ida quanto na volta, indicando uma maior demanda nesse tipo de transporte.  
Em relação aos status das linhas, os dados mostram que o metrô apresenta menos problemas operacionais (como interrupções ou atrasos) do que as linhas de ônibus, reforçando sua confiabilidade como alternativa.  
Contudo, ao analisarmos a proporção de status problemáticos (gráfico de pizza), percebemos que as linhas possuem uma distribuição uniforme de cerca de 20% de ocorrências problemáticas, independentemente do tipo de transporte.

