# Golpes digitais contra pessoas idosas: painel do mapeamento

Painel interativo dos 299 estudos incluídos no mapeamento sistemático *Golpes Digitais contra Pessoas Idosas: um Mapeamento Sistemático da Literatura (2020–2026)*.

**Acesse:** https://pedrohrnq03.github.io/mapeamento-golpes-idosos/

## O que o painel mostra

- Filtros por ano, país, modalidade de golpe e tipo de intervenção
- Indicadores da seleção: total de estudos, quantos especificam a modalidade, quantos propõem intervenção e quantos tratam de denúncia
- Gráficos por ano, país, modalidade, fator de suscetibilidade, intervenção, desenho do estudo e impacto medido
- Lista dos estudos selecionados, com link para o artigo original pelo DOI

## Como os dados foram obtidos

As buscas foram feitas em seis bases (Scopus, Web of Science, IEEE Xplore, ACM Digital Library, ScienceDirect e SciELO) e retornaram 4.433 registros. Depois da remoção de duplicados e de duas etapas de triagem no [Parsifal](https://parsif.al), com apoio do [parsifal-auto](https://github.com/joaopcalumby/parsifal-auto), restaram 299 estudos publicados entre 2020 e 2026.

Cada estudo foi classificado em 12 campos por regras de palavras-chave aplicadas ao título e ao resumo. Numa conferência de 20 estudos, a concordância foi de 72%, então os números indicam tendências e não medidas exatas.

## Tecnologia

Uma única página HTML, com os dados embutidos e gráficos feitos em [D3.js](https://d3js.org). Não depende de servidor nem de build.

## Autores

André Farias Santos e Pedro Henrique Santos da Silva. Trabalho da disciplina Ciência dos Dados e Inteligência Empresarial (SISB110), sob orientação do Prof. Jário José dos Santos Júnior, Universidade Federal de Alagoas (UFAL), Campus Penedo, 2026.
