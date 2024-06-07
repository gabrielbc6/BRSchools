# Análise dos Microdados do Censo Escolar do Brasil
## Visão Geral do Projeto
Este projeto utiliza os microdados do Censo Escolar do Brasil, disponíveis no Portal Brasileiro de Dados Abertos, para realizar duas análises principais. O Censo Escolar é a principal pesquisa estatística sobre a educação básica no Brasil, abrangendo todas as instituições de ensino públicas e privadas do país. As análises realizadas no projeto estão focadas em dois aspectos distintos: características das escolas e perfil sociodemográfico dos alunos.

## Análise 1: Características das Escolas
### Objetivo
O objetivo desta análise é compreender as características das escolas de educação básica no Brasil, considerando aspectos como a localização (rural ou urbana), o estado, e o tipo de escola (pública ou privada).

### Metodologia
Extração e Limpeza de Dados:

Foram extraídos dados brutos sobre as escolas a partir dos microdados disponibilizados.
Os dados passaram por um processo de limpeza para remover entradas duplicadas, lidar com valores ausentes e padronizar formatos.
Transformação de Dados:

A localização das escolas foi categorizada como rural ou urbana.
Os estados foram identificados por suas siglas e organizados para permitir uma análise comparativa entre diferentes regiões.
Análise Exploratória:

Distribuição por Localização: Avaliou-se a distribuição das escolas entre áreas rurais e urbanas.
Distribuição por Estado: Foi analisada a quantidade de escolas por estado, proporcionando uma visão regional da distribuição de instituições de ensino.
Tipos de Escola: Foram examinados os tipos de escola (pública ou privada) e sua distribuição conforme a localização e os estados.

## Análise 2: Perfil Sociodemográfico dos Alunos
### Objetivo
Esta análise visa examinar as características sociodemográficas dos alunos matriculados nas escolas de educação básica, incluindo aspectos como a moradia, o transporte até a escola e a etnia dos estudantes.

### Metodologia
Extração e Limpeza de Dados:

Dados sobre os alunos foram extraídos dos microdados disponíveis.
Similar à análise anterior, os dados foram limpos para garantir a precisão e a integridade das informações utilizadas.
Transformação de Dados:

Informações sobre moradia foram categorizadas (e.g., moradia própria, alugada, etc.).
Dados sobre transporte foram transformados para indicar o tipo de transporte utilizado (e.g., transporte público, escolar, a pé, etc.).
As etnias dos alunos foram classificadas conforme as categorias oficiais utilizadas no censo.
Análise Exploratória:

Moradia: Investigou-se a distribuição dos tipos de moradia entre os alunos, fornecendo uma visão sobre a situação habitacional dos estudantes.
Transporte: Analisou-se como os alunos se deslocam para a escola, com ênfase nas diferenças entre áreas rurais e urbanas.
Etnia: Foram estudadas as proporções das diferentes etnias entre os alunos, explorando possíveis variações regionais e por tipo de escola.
