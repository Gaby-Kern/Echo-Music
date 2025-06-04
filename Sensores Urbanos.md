* ##  Sensores Urbanos

# O que medimos: 
A concentração de ocorrências de aglomeração em cada local monitorado pelas câmeras, com objetivo de identificar quais pontos possuem maior frequência de aglomerações, sinalizando locais que demandam atenção ou intervenção para garantir a segurança e fluidez do público.  

# Parâmetros:  
Indicador de aglomeração  
timestamp  
Indicador de pessoa caida  
Indicador de aglomeração  
Indicador de veiculo parado  
Incidentes  
Count(id\_frame)  

# Gráficos:  
**1\. Gráfico de barras — Densidade de aglomerações por localização**  
Configuração:  
Eixo X: indicador de aglomeração  
Eixo Y: timestamp  
Insight:  
As câmeras 1 e 3 registraram as maiores concentrações de aglomerações ao longo do período analisado. Embora esses pontos apresentem destaque, a diferença na densidade em relação às demais câmeras é relativamente discreta, sugerindo uma distribuição relativamente homogênea de fluxos de pessoas nas áreas monitoradas.  
---
**2\. Gráfico de série temporal — Evolução das aglomerações ao longo do dia do evento**  
Configuração:  
Eixo X: timestamp  
Eixo Y: indicador de pessoa caída | indicador de aglomeração | indicador de veículo parado  
Insight:  
As aglomerações representaram a maioria absoluta dos incidentes detectados durante o período monitorado. No entanto, observou-se uma tendência de redução gradual desses eventos ao longo do tempo, indicando possível dispersão do público ou eficácia de intervenções no controle do fluxo de pessoas.  
---
**3\. Gráfico de Pizza — Proporção de incidentes registrados**  
Configuração:  
Eixo X: incidentes  
Eixo Y: Count(id\_frame)  
Insight:  
Aglomerações constituíram a maior parte dos incidentes registrados, com 63% do total. Os eventos de veículos parados representaram 9% das ocorrências, enquanto casos de pessoas caídas foram responsáveis por apenas 2%, indicando baixa incidência desses últimos eventos no contexto monitorado.  
---

# Conclusão:  
Os dados indicam que o principal desafio na gestão das áreas monitoradas é o controle de aglomerações, especialmente em pontos específicos como as câmeras 1 e 3\. Recomenda-se reforçar medidas de segurança e controle de fluxo nesses locais, como presença de agentes de monitoramento e sinalização preventiva.  
A tendência de queda nas aglomerações ao longo do tempo pode indicar a eficácia de ações já implementadas, mas recomenda-se manter a vigilância, principalmente em horários ou eventos de maior movimento.  
Dado o baixo volume de registros de veículos parados e pessoas caídas, esses incidentes podem ser tratados com protocolos de resposta padrão, sem necessidade imediata de alocação adicional de recursos.  
Por fim, sugere-se o uso contínuo de ferramentas de análise automatizada para identificar rapidamente alterações nos padrões de movimentação e antecipar riscos, garantindo segurança e fluidez no ambiente monitorado.  
