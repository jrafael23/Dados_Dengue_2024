# Dados_Dengue_2024 atualizado em 31/01/2024
### Pesquisa feita a partir de dados do DATASUS relacionada a Notificações de casos de Dengue no ano de 2024. Processo de ETL realizado no Pentaho PDI gerando arquivos de saída em TXT e dashboard criado no Power BI.

### Conjunto de dados baixado diretamente do site do DATASUS ( ftp://ftp.datasus.gov.br/dissemin/publicos/SINAN/DADOS/PRELIM/DENGBR24.dbc), assim como os dados para conversão dos códigos dos municípios/UF ( os arquivos tb_municip.dbf e  tb_uf.dbf encontram-se disponível nesse repositório) e convertidos para formato .DBF pelo aplicativo TabWin (ftp://ftp.datasus.gov.br/tabwin/tabwin/TAB415.zip).

## Pentaho PDI
### Passo a passo do processo de ETL descrito no diagrama na área de transformação do Pentaho ( o arquivo dengue_2024.ktr encontra-se disponível nesse repositório).

![image](https://github.com/jrafael23/Dados_Dengue_2024/assets/130203423/c6a0f9b1-537e-498f-ae26-7455b451a228)


## Power BI
### Arquivo do Power BI (dengue_2024.pbix) e template (Template_dengue_ok.png) disponíveis nesse repositótio.

![image](https://github.com/jrafael23/Dados_Dengue_2024/assets/130203423/f62f4f27-bffe-45e9-b527-6066684b9fa0)


