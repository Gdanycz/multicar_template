Gdany car template
Web: gdany.eu

do složky stream soubory: .ytd .ytf
do složky data: modelname vozu a do ní soubory od vozu (.meta)

ve vehicles.meta najít:

<gameName>riot</gameName>

a změnit na modelname stejně jako je zde:

<modelName>riot</modelName>

a poté v vehicle_names.lua:
AddTextEntry('modelname', 'ingamename')

a přepíšeme modelname, který jsme si nastavili v gameName a modelName a do ingamename si pojmenujeme, 
jak se má ukazovat název vozu ve hře

AddTextEntry('riot', 'BlackBetty')