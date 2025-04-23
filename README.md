# MODULO-2: POSIT CLOUD 
---
title: "PRESENTACION EN R"
author: "ING. ANA DOMINGUEZ"
date: "`r Sys.Date()`"
output:
  slidy_presentation: default
  ioslides_presentation: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
```

# PRESENTACION DE INTEGRANTES DEL GRUPO

## GRUPO INTER

-   Anastasia Bekerman
-   Ana Paula Dominguez
-   Juan Ignacio Fernandez
-   Tomás Aliaga
-   Andrés Landgrebe

# EJERCITACION 9 DE ABRIL

# PESOS DE LAS MUJERES Y DESVIACION ESTANDAR

```{r}
women$weight
sd(women$weight)
```

# PROMEDIOS Y DESVIO ESTANDAR

## PROMEDIO Y DESVIO ESTANDAR DE LOS PESOS DE LAS MUJERES

```{r}
sd(women$weight)
mean(women$weight)
```

# HISTOGRAMA

## HISTOGRAMA DE PESOS DE LAS MUJERES

```{r}
hist(women$weight,main="histograma de pesos")
```

# EJERCITACION NUEVAS 23/04

```{r}
# toda linea que en codigo aparece despues de un numeral es un comentario 
# rutina para convertir de pies a metros
```

# UNO: Como contar la cantidad de filas de una columna

```{r}
length(cars$dist)
```

# DOS: Cómo calcular el promedio de las velocidades

```{r}
mean (cars$speed)
```

# TRES: Cómo calcular la moda de las velocidades

```{r}
mode(cars$speed)
```

# CUATRO: Cómo hacer un grafico velocidad vs distancia

```{r}
plot(cars,main="distancia de frenado del Chevrilet Impala 1963", xlab="distancia en ft", ylab="velocidad en mph")
```

# CINCO: análisis exploratorio del histograma

```{r}
plot(hist(cars$dist, breaks=2))
```

```{r}
plot(hist(cars$dist,breaks=50))
```

# SEIS: DENSIDAD

```{r}
plot(density(cars$dist))
```

# SIETE: Como no utilizar el signo igual al dar valores a una variable

```{r}
a <-23
a
```
# OCHO: Como convertir a vector una variable

```{r}
b <- c(1,2,5,6,30,40,85,86,87,89)
b
```
# NUEVE: Como hacer un histograma de un vector
