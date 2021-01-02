## How to build

  make -j6 USE_OPENGL=1 SDL_TARGET=2 USE_LIBVPX=0

## Configuration

  `~/.eduke32/eduke32.cfg`

```
[Misc]
Executions = 20

[Setup]
ConfigVersion = 321
ForceSetup = 1
NoAutoLoad = 1
SelectedGRP = "DUKE3D.GRP"

[Screen Setup]
Polymer = 0
ScreenBPP = 32
ScreenHeight = 320
ScreenMode = 0
ScreenWidth = 480

[Controls]
AutoAim=1
JoystickAnalogAxes0 = "analog_strafing"
JoystickAnalogScale0 = -1000
JoystickAnalogDead0 = 2000
JoystickAnalogSaturate0 = 1000000
JoystickAnalogAxes1 = "analog_moving"
JoystickAnalogScale1 = -98304
JoystickAnalogDead1 = 2000
JoystickAnalogSaturate1 = 32768
JoystickAnalogAxes2 = "analog_turning"
JoystickAnalogScale2 = 32768
JoystickAnalogDead2 = 2000
JoystickAnalogSaturate2 = 562500
JoystickAnalogAxes3 = "analog_lookingupanddown"
JoystickAnalogScale3 = 16384
JoystickAnalogDead3 = 3000
JoystickAnalogSaturate3 = 16384
JoystickDigitalAxes3_0 = "Run"
# A
JoystickButton0 = "Crouch"
# B
JoystickButton1 = "Jump"
# X
JoystickButton2 = "Open"
# Y
JoystickButton3 = "Jetpack"
JoystickButtonClicked3 = "Holo_Duke"
# l1
JoystickButton4 = "Quick_Kick"
# l2
JoystickButton10 = "Previous_Weapon"
# l3
JoystickButton8 = "Map"
JoystickButtonClicked8 = "NightVision"
# r1
JoystickButton5 = "Fire"
# r2
JoystickButton11 = "Next_Weapon"
# r3
JoystickButton9 = "MedKit"
JoystickButtonClicked9 = "Steroids"
# start
JoystickButton6 = "Toggle_Crosshair"
# select
JoystickButton7 = "Show_Menu"

[Comm Setup]
PlayerName = ""
RTSName = "DUKE.RTS"
CommbatMacro#0 = "An inspiration for birth control."
CommbatMacro#1 = "You're gonna die for that!"
CommbatMacro#2 = "It hurts to be you."
CommbatMacro#3 = "Lucky son of a bitch."
CommbatMacro#4 = "Hmmm... payback time."
CommbatMacro#5 = "You bottom dwelling scum sucker."
CommbatMacro#6 = "Damn, you're ugly."
CommbatMacro#7 = "Ha ha ha... wasted!"
CommbatMacro#8 = "You suck!"
CommbatMacro#9 = "AARRRGHHHHH!!!"
```

`~/.eduke32/settings.cfg`

```
in_joystick "1"
```
