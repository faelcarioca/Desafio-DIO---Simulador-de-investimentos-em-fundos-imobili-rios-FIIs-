# Desafio DIO: Simulador de investimentos em fundos imobiliários (FIIs)
Simulador de investimentos em fundos imobiliários (FIIs) feito em planilha de cálculos compatível com Excel e softwares do gênero. Projeto desafio do bootcamp DIO - Reclame AQUI: Dados e IA na Prática. Diferente do projeto original (do mentor Felipe Aguiar), este foi desenvolvido no Google Sheets minimizando incompatibilidades.

## OBS: EDITADO NO GOOGLE SHEETS E SALVO NO FORMATO EXCEL 2007. NO GOOGLE SHEETS O FORMATO .XLSX IMPOSSIBILITA O TRAVAMENTO DAS CÉLULAS PARA EDIÇÃO. AINDA É POSSÍVEL FAZER O TRAVAMENTO NO FORMATO .ODS, MAS QUE, POR SER OUTRO PADRÃO, PODE ALTERA DETALHES DA FORMATAÇÃO E PERDE A FUNÇÃO DE TRAVAMENTO NO USO COM OUTROS SOFTWARES DO MESMO GÊNERO.

- A ferramenta retorna ao usuário uma resposta rápida ao patrimônio acumulado em 5 anos (L13) e aos dividendos (L14) a partir do input de dados solicitados, além de pré calcular o patrimônio acumulado de outros períodos (2, 5, 10, 20 e 30 de L17 a L21)
    
- VF é a função de cálculo para valor futuro. Ela considera a taxa de juros, o período de recorrência de pagamentos e o valor pago. A periodicidade da taxa precisa parear com a periodicidade do investimento sendo convertido os anos em meses. O retorno por padrão é negativo e também precisa ser convertido ("-" antes da referência) para retornar positivo.
PROCV procura um valor na primeira coluna de um intervalo de tabela e retornando o valor da mesma linha na coluna especificada da mesma tabela (valor exato no caso o desafio). No desafio ele procura um valor combinado de perfil+tipo de FII no intervalo de colunas A:D da planilha SUPORTE, retornando o valor de porcentagem do investimento sugerido do perfil.

- Salário=SALARIO; Rendimento da Carteira=REDIM; Sugestão de Investimento=INVEST; Quanto investir mensalmente=APORTE; Período em anos=PERI_ANO; Taxa de rendimento mensal=TAX_MES; Patrimônio acumulado=PATRIMN

- Planilha SUPORTE, coluna D

- Cores, logo, valores, intervalos nomeados, formatação, disposição do gráfico, nome de algumas referências e outras coisas menores.
