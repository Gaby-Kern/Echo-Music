# **Fontes de dados levantadas e o método de coleta**

## **Fontes de Dados Prioritárias para o Projeto**

### **1\. Redes Sociais** (Twitter/X, Instagram, Facebook, TikTok)

**Descrição:**  
Plataformas onde usuários publicam conteúdos em tempo real sobre eventos, incluindo textos, imagens, vídeos e localização.  
**Tipo de dados:**  
Não estruturados: textos, imagens, vídeos.  
Semi-estruturados: posts com metadados (data, hora, localização geográfica, hashtags).  
**Métodos de acesso e coleta:**

* API Oficial:  
  Twitter/X API: permite acesso a tweets públicos em tempo real, com filtros por    palavras-chave, hashtags ou geolocalização.  
  Meta Graph API: para publicações públicas no Instagram e Facebook.  
  TikTok: não possui API pública oficial para coleta em massa; pode ser necessário       usar scraping com cautela.  
* Web Scraping:  
  Para dados públicos visíveis na web, com atenção às políticas de uso das plataformas.  
* Ferramentas especializadas:  
  GNIP (para Twitter), CrowdTangle (para Facebook/Instagram).  
  ---

### **2\. Câmeras Públicas de Monitoramento** (CCTV Online)

**Descrição:**  
Algumas cidades oferecem acesso público a câmeras de monitoramento de tráfego e espaços públicos.  
**Tipo de dados:**  
Não estruturados: vídeo em tempo real ou imagens.  
**Métodos de acesso e coleta:**

* Streams públicos: Sites de prefeituras ou órgãos de trânsito que disponibilizam câmeras online.  
* Web scraping: Extração de imagens ou fluxos, com cuidado legal.  
* Integração direta: Via acordos com prefeituras ou órgãos de segurança que disponibilizem feeds abertos.

---

### **3\. Dados de Transporte Público** (GTFS e APIs de mobilidade)

**Descrição:**  
Informações sobre fluxo de transporte público (metrô, ônibus), úteis para entender concentração e deslocamento de pessoas.  
**Tipo de dados:**  
Estruturados: horários, rotas, número de passageiros.  
**Métodos de acesso e coleta:**

* GTFS (General Transit Feed Specification): Formato padrão usado mundialmente para disponibilização de dados de transporte.  
* APIs locais: exemplos: SPTrans (São Paulo), Moovit API, Google Transit API.  
* Scraping: Para casos em que os dados são publicados em sites sem API.

---

### **4\. Dados Meteorológicos** (INMET, NOAA, OpenWeather)

**Descrição:**  
Condições climáticas podem impactar a segurança em eventos (tempestades, calor extremo).  
**Tipo de dados:**  
Estruturados: temperatura, umidade, pressão, previsão do tempo, histórico.  
**Métodos de acesso e coleta:**

* APIs públicas:  
  OpenWeather API (grátis para consultas básicas).  
  NOAA (National Oceanic and Atmospheric Administration) — dados climáticos históricos e em tempo real.  
  INMET (Instituto Nacional de Meteorologia — Brasil) — dados meteorológicos públicos

---

### **5\. Dados Históricos de Crimes e Ocorrências Policiais**

**Descrição:**  
Bases de dados públicas sobre crimes, incidentes e ocorrências relacionadas a eventos anteriores.  
**Tipo de dados:**  
Estruturados: tabelas com localização, tipo de ocorrência, data e hora.  
**Métodos de acesso e coleta:**

* Portais de dados abertos: ex.: SSP-SP (Secretaria de Segurança Pública de São Paulo), FBI Crime Data Explorer (EUA).  
* Downloads diretos: CSV, Excel ou JSON.

---

### **6\. Sensores Urbanos e Dados de Ruído** (Plataformas Open Data)

## **Descrição:** Sensores instalados em cidades inteligentes coletam dados sobre níveis de ruído, poluição e densidade de pessoas. **Tipo de dados:** Estruturados: níveis de decibéis, fluxo de pessoas. **Métodos de acesso e coleta:**

* ## Plataformas Open Data: exemplos: NYC Open Data, Dados Abertos SP.

* ## APIs de sensores urbanos: Smart Cities com sistemas de dados abertos podem oferecer esse recurso.

---

## **Fontes secundárias (não prioritárias, mas complementares):** 

**Dados de localização e mapas (OpenStreetMap):** importantes para a visualização geoespacial e roteamento, mas não essenciais para a detecção direta de tumultos.

# Os dados foram criados com ferramentas e bibliotecas generativas. 

## Introdução da problemática:

Grandes eventos públicos — como festivais culturais, manifestações políticas, shows e eventos esportivos — reúnem milhares de pessoas em um mesmo espaço, elevando significativamente os riscos de tumultos, violência, vandalismo e até atentados. Monitorar, em tempo real, o comportamento das multidões e antecipar situações críticas é um dos principais desafios das forças de segurança e organizadores desses eventos.

Tradicionalmente, a resposta aos incidentes é reativa: as autoridades agem somente após a ocorrência do problema, o que pode resultar em maiores danos, tanto à integridade física dos participantes quanto ao patrimônio público e privado. Assim, torna-se fundamental o desenvolvimento de métodos que permitam a antecipação e a mitigação desses riscos, com base na análise de dados.

## Justificativa do uso de dados sintéticos:

Devido à natureza sensível dos dados envolvidos neste tipo de análise — incluindo informações pessoais, geolocalização e conteúdos potencialmente identificáveis de redes sociais —, este projeto opta pela utilização de **dados sintéticos**.

Os dados sintéticos são informações geradas artificialmente que imitam características estatísticas e padrões encontrados em dados reais, mas sem representar indivíduos ou eventos reais. Esta abordagem oferece diversas vantagens:

1. Evita riscos legais e éticos, respeitando legislações como a LGPD (Lei Geral de Proteção de Dados).

2. Permite o desenvolvimento e validação de modelos analíticos em um ambiente seguro e controlado.

3. Favorece a transparência e a replicabilidade, uma vez que os dados podem ser compartilhados livremente para fins educacionais ou de pesquisa.

Assim, o uso de dados sintéticos neste projeto não compromete a validade da proposta, pois o foco está na demonstração da metodologia e no potencial da análise de dados como ferramenta para prevenção de crises em eventos de grande porte.