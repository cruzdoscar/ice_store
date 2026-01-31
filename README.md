# Análisis de ventas de videojuegos: Insights del proyecto Ice Store

El **Proyecto Ice Store** es un análisis exhaustivo de las ventas de videojuegos desde 1980 hasta 2016. Este proyecto busca descubrir las tendencias y los factores que influyeron en el éxito de los videojuegos a lo largo de las décadas. Centrándose en las reseñas de usuarios y expertos, la popularidad de las plataformas y la distribución de géneros, el análisis sienta las bases para planificar una estrategia de marketing eficaz para 2017. Al comprender estas tendencias, podemos anticipar qué tipos de juegos y plataformas podrían tener más éxito el próximo año.

## Preparación de datos
Para garantizar la calidad y la fiabilidad de nuestro análisis, comenzamos con una rigurosa preparación de datos. El conjunto de datos incluía información sobre nombres de juegos, plataformas, años de lanzamiento, géneros, ventas en diversas regiones y puntuaciones de usuarios y críticos.

name platform  year_of_release         genre  na_sales  \
0                Wii Sports      Wii           2006.0        Sports     41.36   
1         Super Mario Bros.      NES           1985.0      Platform     29.08   
2            Mario Kart Wii      Wii           2008.0        Racing     15.68   
3         Wii Sports Resort      Wii           2009.0        Sports     15.61   
4  Pokemon Red/Pokemon Blue       GB           1996.0  Role-Playing     11.27   

   eu_sales  jp_sales  other_sales  critic_score user_score rating  
0     28.96      3.77         8.45          76.0          8      E  
1      3.58      6.81         0.77           NaN        NaN    NaN  
2     12.76      3.79         3.29          82.0        8.3      E  
3     10.93      3.28         2.95          80.0          8      E  
4      8.89     10.22         1.00           NaN        NaN    NaN  
------------------------------------------------------------------------------------------
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 16715 entries, 0 to 16714
Data columns (total 11 columns):
 #   Column           Non-Null Count  Dtype  
---  ------           --------------  -----  
 0   name             16713 non-null  object 
 1   platform         16715 non-null  object 
 2   year_of_release  16446 non-null  float64
 3   genre            16713 non-null  object 
 4   na_sales         16715 non-null  float64
 5   eu_sales         16715 non-null  float64
 6   jp_sales         16715 non-null  float64
 7   other_sales      16715 non-null  float64
 8   critic_score     8137 non-null   float64
 9   user_score       10014 non-null  object 
 10  rating           9949 non-null   object 
dtypes: float64(6), object(5)
memory usage: 1.4+ MB
None