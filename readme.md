# Estudo Ecológico Sobre as Internações hospitalares por Problemas Psiquiátricos no SUS (DEMO)

*Trata-se de um projeto exploratório que busca melhor entender o fenômeno das internações hospitalares no SUS por condições psiquiatricas. Assim, o projeto busca cruzar determinantes epidemiologicos, geográficos, demográficos, econômicos e sociais para construir conhecimento científico e melhor compreender essa dinâmica*

## Datasets Utilizados no Projeto
| Base de Dados | Caminho do Arquivo | Descrição | Fonte |
|---|---|---|---|
| Internações por Distúrbios Psiquiátricos | data\sus\mental_diseases_jan2024-dec2024\sih_cnv_nibr102443191_53_138_174.csv | Dados sobre hospitalizações psiquiátricas por municipalidade de jan 2024 à jan 2025 | [DATA SUS](http://tabnet.datasus.gov.br/cgi/tabcgi.exe?sih/cnv/nibr.def) |
| Malha Municipal Digital e Áreas Territoriais 2023 | C:\Users\Andre\Desktop\projeto mapa\data\geo\BR_Municipios_2023 | Dados geográficos para a projeção, cruzamento dos dados e criação de mapas | [IBGE](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html) |

## Formato da Pesquisa no Data SUS
![Screen](data/sus/mental_diseases_jan2024-dec2024/data_sus_search_params1.png)
![Screen](data\sus/mental_diseases_jan2024-dec2024/data_sus_search_params2.png)



## Mapas Gerados

### Rede Municipal Brasileira
![Screen](/images/all_municipalities.png "Rede Municipal Brasileira")

**/arranging_geo_data.ipynb**
### Municipalidades Com e Sem Reportes
![Screen](/images/municipalities_with_and_without_reports.png "Municipalities with and without reports")

**/municipalities_with_and_without_reports.ipynb**
### Choromap de Número Absoluto de Internações por Municipalidade
![Screen](/images/hospitalizations_choromap.png "Choromap das Internações Psiquiatricas")

**/municipalities_with_and_without_reports.ipynb**