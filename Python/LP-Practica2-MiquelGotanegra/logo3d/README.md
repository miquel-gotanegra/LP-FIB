# GEI-LP (edici贸 2020-2021 Q2): Logo3D 馃悽

Implementacio d'un int猫rpret d'un llenguatge de programaci贸 anomenat Logo3D per permetre pintar amb una tortuga en 3D.

## Instalaci贸n 馃敡

Per instalar les llibreries necessaries per executar el programa fem servir la comanda: 

```
$ pip install -r requirements.txt
```

## Compilacio 馃枼

Abans de poder utilitzar l'interpret l'haurem de compilar perqu猫 generi els arxius que fara servir el main.

Ho fem amb la seg眉ent comanda:

```
$ antlr4 -Dlanguage=Python3 -no-listener -visitor logo3d.g
```

## Execuci贸 馃殌

Per executar el programa fem servir:
```
$ python3 logo3d.py input_file.l3d
```

Per defecte s'executa el programa partint del **main**, si volem que es comen莽i desde qualsevol altre dels procediments haurem de utilitzar:
```
$ python3 logo3d.py input_file.l3d procediment param1 param2..
```
On el procedmient pot ser tant de la input file com una de les funcions de Turtle3D, seguida de els seus par脿metres.


Esta incl贸s a la carpeta l'arxiu *test-01.l3d*, un exemple de input_file


## Autor 鉁掞笍



* **Miquel Gotanegra Esta帽ol** 
