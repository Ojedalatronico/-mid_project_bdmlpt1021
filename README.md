## Mid project - Eurocup Dasboard

Mid proyect about Api and a Dasboard. Here you going to see general and individual data about eurocup matches

![Imagen](api.png)(https://midprojectbdmlpt1021.herokuapp.com/)
## Goals

L1
- [x] Crear api en FastAPI
- [x] Crear dashboard en streamlit
- [x] Base de datos en MongoDB o PostgreSQL
L2
- [?] Un dashboard de multiples páginas en Streamlit
- [x] Tener la base de datos en el Cloud
<!-- ABOUT THE PROJECT -->

## Installation

Instala todas las librerias en requirements.txt file. Una vez instalado puedes comenzar a utilizar ambos contenidos


### How to use it 

Para usar el dashboard debes ejecutar en tu consola:
```sh
   streamlit src/dashboard/main.py
   ```


## What expected to get

![Imagen](dashimg.png)(https://midprojectbdmlpt1021.herokuapp.com/)

A tu costado izquierdo podrás elegir entre ver general stats o ver los match individualmente.

En cada uno de ellos podrás ver: los goles, los tiros y tarjetas

### Requests to the API

Descripción de las peticiones a la API:

https://uefa2020.herokuapp.com/general -> Devuelve las estadísticas generales
https://uefa2020.herokuapp.com/matches -> Duelve las estadísticas de los partidos
https://uefa2020.herokuapp.com/matche/teams -> Duelve los equipos al darle una fase(stage) 
https://uefa2020.herokuapp.com/matche/rival -> Duelve el equipo rival al darle una fase y equipo
https://uefa2020.herokuapp.com/home/stats -> Deuelve las estadísticas de un equipo (si es considerado home)
https://uefa2020.herokuapp.com/away/stats -> Devuelve las estadísticas de un equipo (si es considerado away)
https://uefa2020.herokuapp.com/events -> Devuelve los eventos ocurridos en un partido al darle fase y equipo

También hice otras requests, la mayoría fueron eliminadas, no obstante me he quedado con unas porque las considero valiosas:

https://uefa2020.herokuapp.com/league -> Devuelve las estadísticas generales de un año específico
https://uefa2020.herokuapp.com/league/goals_each_10 -> Devuelte los goles realizados cada 10 minutos de toda una temporada específicada
https://uefa2020.herokuapp.com/league/goals_each_10 -> Devuelte los goles realizados cada 15 minutos de toda una temporada específicada