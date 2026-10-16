# Radar de Vendas: do Dado à Decisão

Projeto de análise de vendas desenvolvido no Excel. O objetivo é transformar registros de vendas em indicadores que ajudem a compreender o faturamento, o comportamento dos pedidos e o desempenho de produtos, cidades e canais de venda.

## Sobre os dados

A base contém 360 vendas fictícias realizadas entre janeiro e dezembro de 2025 por uma rede simulada de cafés e presentes. Cada linha representa uma venda e inclui informações como produto, categoria, cidade, canal, quantidade, preço e percentual de desconto.

## Análises realizadas

- Faturamento bruto, descontos concedidos e faturamento líquido
- Ticket médio por venda, calculado com base no faturamento líquido
- Desempenho por produto, categoria, cidade e canal
- Variação do faturamento ao longo dos meses
- Comparação entre percentual de desconto e ticket médio bruto e líquido

## Indicadores gerais

| Indicador | Resultado |
|---|---:|
| Vendas | 360 |
| Unidades vendidas | 693 |
| Faturamento bruto | R$ 27.605,70 |
| Descontos concedidos | R$ 1.780,39 |
| Faturamento líquido | R$ 25.825,31 |
| Ticket médio líquido | R$ 71,74 |
| Desconto efetivo sobre o faturamento bruto | 6,45% |

## Destaque: desconto e ticket médio

Na amostra, a relação entre o percentual de desconto e o ticket médio líquido é fraca e negativa. A correlação observada é de aproximadamente -0,09. Isso indica uma associação pequena e não permite afirmar que o desconto, por si só, causou a redução do ticket.

O ticket médio líquido é usado para representar a receita por venda após os descontos. O faturamento bruto serve como referência para comparar os valores antes dos descontos. A análise também considera o número de vendas em cada faixa, pois grupos pequenos podem produzir médias menos estáveis.

## Estrutura do arquivo

- **Projeto:** contexto, objetivos e roteiro do exercício.
- **Base de vendas:** registros das vendas e campos calculados.
- **Minha análise:** indicadores, respostas às perguntas e recomendações.
- **Abas auxiliares:** resumos e materiais de apoio à análise.

## Limitações

Os dados são fictícios e cobrem apenas um ano. A planilha não contém informações de custos ou margens; portanto, a análise avalia faturamento, mas não rentabilidade. As associações observadas não demonstram causalidade.
