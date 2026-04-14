# Ferramenta de Análise Nutricional Infantil para Contextos Indígenas

Aplicação desenvolvida para apoiar a análise antropométrica de crianças, com foco em vigilância alimentar e nutricional em contextos indígenas e territórios de atenção primária à saúde.

A ferramenta recebe uma planilha `.xlsx` com dados de puericultura e retorna gráficos, curvas antropométricas e análises descritivas para apoiar o acompanhamento do crescimento infantil.

## Objetivo

Este projeto foi criado para facilitar a visualização e a interpretação de dados antropométricos infantis, permitindo que equipes de saúde, pesquisadores e outros grupos organizem melhor o monitoramento nutricional de crianças a partir de registros já existentes em planilhas.

A proposta da ferramenta é apoiar ações de vigilância em saúde e acompanhamento nutricional, sem substituir avaliação clínica individual, discussão multiprofissional ou conhecimento territorial.

## O que a ferramenta faz

A aplicação permite carregar um arquivo Excel (`.xlsx`) e visualizar:

- análises descritivas dos dados
- curvas antropométricas com escores z
- gráficos por sexo
- curvas de:
  - peso por idade
  - estatura por idade
  - IMC por idade
  - perímetro encefálico por idade
  - peso por estatura

Na versão pública atualmente disponível, a interface apresenta as abas **Descritivas**, **Curvas** e **Controle**, além das curvas antropométricas separadas para meninos e meninas. :contentReference[oaicite:2]{index=2}

## Acesso à aplicação

Versão online:
**https://juliajallad-pucrio.shinyapps.io/app_puericultura/**

## Como usar

### 1. Preparar a planilha
O arquivo `.xlsx` nesse repositório é um template compativel com o esperado pela ferramente, utilize-o preenchendo com os dados nescessários.

### 2. Carregar o arquivo
Abra a aplicação e envie o arquivo no campo de upload.

### 3. Navegar pelas abas
Após o carregamento, a ferramenta organiza a análise em diferentes áreas:

- **Descritivas**: visão geral da base
- **Curvas**: gráficos antropométricos com escores z
- **Controle**: apoio à inspeção dos registros e consistência dos dados

## Como interpretar a análise

### Curvas antropométricas
As curvas antropométricas permitem comparar as medidas observadas com padrões de referência por idade e sexo.

Elas são úteis para acompanhar tendências como:

- déficit de estatura
- déficit de peso
- alterações no IMC
- discrepâncias entre peso e estatura
- distribuição do perímetro encefálico

### Escores z
Os escores z ajudam a posicionar cada medida em relação à população de referência.

De forma geral, valores muito abaixo ou muito acima do esperado podem indicar necessidade de maior atenção, investigação ou acompanhamento mais próximo. No entanto, a interpretação nunca deve ser automática ou isolada.

## Cuidados importantes

### 1. A ferramenta não substitui avaliação clínica
Os gráficos e curvas apoiam o monitoramento, mas não devem ser usados isoladamente para conclusões.

### 2. O contexto importa
Em territórios indígenas, a análise nutricional deve considerar fatores históricos, culturais, ambientais e organizacionais do cuidado. O debate sobre saúde indígena no DSEI Xingu destaca justamente a importância de uma atenção diferenciada, territorializada e construída com participação local.

### 3. Uso ético dos dados
Recomenda-se fortemente:
- remover identificadores pessoais antes de compartilhar bases

## Limitações

- A qualidade da saída depende diretamente da qualidade do arquivo de entrada.
- Campos incompletos ou inconsistentes podem comprometer as curvas e gráficos.
- A ferramenta foi pensada como apoio à vigilância nutricional e à organização da informação, não como sistema diagnóstico autônomo.
- A interpretação dos resultados deve ser feita por equipes capacitadas ou em diálogo com profissionais de saúde.
