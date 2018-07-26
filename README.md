# Modification touche clavier No Man's Sky Next

Il est possible de changer l'attribution des touches du jeu via le fichier :

> Steam\steamapps\common\No Man's Sky\Binaries\SETTINGS\TKGAMESETTINGS.MXML

## Modification

Il faut ajouter la propriété **RemappedKey** avec la [valeur ASCII](http://sebastienguillon.com/test/jeux-de-caracteres/windows-ascii-fr.html) qui correspond à la touche souhaitée.

Par exemple pour que le joueur avance avec la touche Z :

    <Property name="Player_Forward" value="GcInputActionMapping.xml"/>

devient

    <Property name="Player_Forward" value="GcInputActionMapping.xml">
    	<Property name="RemappedKey" value="122" />
    </Property>

## Valeurs courantes
|Touche|Valeur  |
|--|--|
|A|97|
|Q|113|
|Z|122|
|W|119|
