Gdany car template
Website: gdany.eu

to the stream files folder: .ytd .ytf
into the data folder: modelname of the car and into it the files from the car (.meta)

in vehicles.meta find:

<gameName>riot</gameName>

and change it to modelname as it is here:

<modelName>riot</modelName>

and then in vehicle_names.lua:
AddTextEntry('modelname', 'ingamename')

and overwrite the modelname we set in gameName and modelName and name the ingame,
how the car name should appear in the game

AddTextEntry('riot', 'BlackBetty')