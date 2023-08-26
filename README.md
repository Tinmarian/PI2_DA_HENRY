# Proyecto de Data Analytics aplicado al Criptomercado.

En este proyecto dedicado al rol de Data Analyst, vamos a encontrar soluciones para una empresa enfocada en el sector financiero, la cual encuentra el mercado cripto interesante debido al potencial de inversión que podrían ofrecer a sus clientes. El objetivo es desarrollar un análisis profundo sobre el mercado y dar a conocer nuestros hallazgos y recomendaciones sobre el mercado.

El requerimiento mínimo es un análisis de 10 criptomonedas.

Se espera encontrar estrategias u oportunidades de inversión, puede ser también integrado algo sobre gestión de riesgo, optimización de portfolio, sugerencias sobre monitoreo del mercado, entre otras posibles soluciones que se puedan desarrollar.

Los mínimos entregables son:

    * EDA
    * Dashboard
    * KPI's: Sugerir 3
    * Repositorio de GitHub

Desafíos:

    * Integrar una BD en la solución
    * Ejecutar código de python en el visualizador
    * Cruzar datos con otras fuentes, para obtener información nueva o para comparar

Descartamos las stablecoins en este análisis, pero se puede añadir un análisis de puras stablecoins, sería lo ideas.

Se trabajó de manera amplia en el EDA, obteniendo conclusiones certeras sobre las mejores formas de operar, aunque no muchas. Se trabajo con gráficos de líneas, histogramas, gráficos de correlaciones, gráficos de autocorrelación, mapas de calor y gráficos de barras.

El repositorio consta de 3 ramas diferentes: data, EDA y KPIs. En los tres podemos encontrar los archivos .csv, en la rama master se encuentra todo el contenido del proyecto. Las carpetas "Binance" y "CoinGecko"contienen toda la data utilizada

Se trató de integrar más datos pero por el tiempo no se concluyó. Además, muchos datos de binance no se utilizaron, solo se utilizaron datos diarios.

Con base en todo esto, nos permitimos concluir que las mejores criptomonedas para hacer trading son BTC y ETH debido a su alta volatilidad y su mayor oportunidad de ganancia, sin embargo, los datos también demuestran que son criptomonedas con un riesgo más alto que muchas otras.

Por otra parte, también se concluye que la mejor criptomoneda para realizar transferencias entre intercambios o wallets es XRP.

Después de eso, descubrimos que, después de BTC, ETH y BNB, la criptomoneda más correlacionada con estas tres es TRX y después DOT.

Aunado a esto, vale la pena repetir las primeras conclusiones, bajo las cuales definimos que es necesario trabajar sobre los datos de precios del intercambio, pero sobre los datos de volumen y market cap de coingecko. Sin embargo, más adelante nos encontramos con que es justamente el volumen uno de los parámetros que no se correlaciona con ningún otro parámetro.

El reporte sobre el Análisis se puede encontrar en https://docs.google.com/document/d/1UnjnYO15r0W_Pk-WoVyFygt15qWtYoEHEXQQxBNrJ3g/edit?usp=sharing.
