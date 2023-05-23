This mod works by changing your crosshair as it's one of the only TF2 HUD elements that can be dynamically changed by commands
to install this mod
===============
open your hud and add:

#base "radialpreload.res"

to the "mainmenuoverride.res" file that your hud has in resource/ui

then add:

+exec radialmain.cfg

to your TF2 launch options

PLEASE check out the files in the config folder or else upon installing this mod all of your crosshair settings will be reset to TF2's default, you have to set the settings in there to the crosshair settings you have before installing this mod

after all is said and done just extract the files from the zip to a new folder in your custom folder
===============
Some huds will have the crosshair beneath other panels, you can fix this by setting the zpos value of the hudcrosshair in whatever hudlayout that the hud uses to control the hudcrosshair:

HudCrosshair
{
	"fieldName"	"HudCrosshair"
	"visible"		"1"
	"enabled"		"1"
	"wide"		"640"
	"tall"		"480"
	"zpos"		"9999999"
}


===============
not compatible with the default hud, you have to install a hud due to the dependency on a mainmenuoverride.res
===============
Mod by Niterux
