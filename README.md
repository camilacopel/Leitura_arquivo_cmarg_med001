# Leitura_arquivo_cmarg_med001
Leitura de um dos arquivo de saído Newave.

 
 ## DADOS:
     
 - CUSTO MARGINAL DE DEMANDA - MEDIA PATAMARES
 - SUBMERCADO:SUDESTE
 - PLD AGOSTO - 2022 - 
 - Niveis para 30/07 NW 
 - Versao 28.0.3
 - Arquivo de sáida, sem patamar e com dados estatísticos


-------------------------------------------------------------------------------
 
 ## RETORNA:
 
 - Uma tabela bidimensional do caso cmarg med
 - Com 16 colunas e 10001 linhas
 - Exclui os dados estatísticos
 - Exporta para CSV
 - Paradigma Estruturado
 
 
 
 ## Tabela:
 
 submercado | anos dos casos | series | todos os meses | media
 Dados
 
 
 
 -------------
 

 ## Refatorar: 
     
 - Anos
 - Aplicar pivot_table
 - Tratar os dados dos anos
    years = np.array([['ANO:', '2022'], ['ANO:', '2023']...
    anos = np.array([2022, 2023, 2024, 2025, 2026])

 - Cabeçalho
 - Submercado
 - Importar excel
 - Importar csv
    
===============================================================================
"""
