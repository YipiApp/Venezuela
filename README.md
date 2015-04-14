Utilerias para Venezuela
==========================

## Sobre el contenido del Repositorio

- zonas_postales.pdf - Fuente de donde se obtuvieron los Codigos Postales de Venezuela (IPOSTEL)
- zonas_postales.json - Parser del PDF de Ipostel en formato JSON
- zonas_postales.csv - Parser del PDF de Ipostel en formato CSV
- zonas_postales.sql - Parser del PDF de Ipostel en formato SQL

## Sobre los Autores

Creado por Kijam López B. Desarrollador de https://cuado.co/

## Sobre el Uso y Licencia

Todo el contenido publicado se puede editar, distribuir y utilizar solo bajo los terminos de la Licencia GPLv3 - Ver GPL.md

## Sobre zonas_postales.json

El formato del JSON contiene la siguiente estructura:
```
{
	'[REGION]': {
		'[ESTADO]': {
			'[MUNICIPIO]': {
				'[PARROQUIA]': {
					'zonas': {
						'[ZONA]': [CODIGO_POSTAL], ...
					},
					'ciudad': [CIUDAD],
					'urbana': true|false
				}, ...
			}, ...
		}, ...
	}, ...
}
```
