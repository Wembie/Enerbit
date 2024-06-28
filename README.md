# Enerbit
# Simulación de Batalla Pokémon

Este proyecto permite simular batallas entre Pokémon utilizando datos de la PokeAPI.

## Estructura del Proyecto

- **main.py**: Archivo principal que inicia la simulación de batalla.
- **datos.py**: Contiene funciones para guardar y cargar los datos de batallas.
- **extraerPokemon.py**: Contiene la función para extraer los datos de un Pokémon desde la PokeAPI.
- **peleaPokemon.py**: Contiene las funciones para imprimir las estadísticas y simular la pelea entre Pokémon.
- **preguntarPokemon.py**: Contiene la función para pedir al usuario el nombre de los Pokémon participantes.
- **simularBatalla.py**: Contiene la lógica para gestionar la simulación de la batalla.

## Requisitos

- Python 3.x
- Biblioteca `requests`

## Instalación

1. Clona este repositorio en tu máquina local:
   ```sh
   git clone https://github.com/Wembie/Enerbit.git
   cd Enerbit
2. Instala la biblioteca requests si no la tienes instalada
   ```sh
   pip install requests
# Ejecución
Para ejecutar la simulación de batalla Pokémon, sigue estos pasos:

1. Asegúrate de estar en el directorio del proyecto:
   ```sh
   cd Enerbit
2. Ejecuta el archivo main.py:
   ```sh
   python main.py

Esto iniciará el proceso de simulación de batalla, donde se te pedirá ingresar los nombres de dos Pokémon. El sistema extraerá los datos de la PokeAPI y simulará la batalla entre ellos, mostrando los resultados en la consola.
