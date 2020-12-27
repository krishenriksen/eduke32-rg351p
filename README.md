## How to build

  make -j6 USE_OPENGL=1 SDL_TARGET=2 USE_LIBVPX=0

## Configuration

  `~/.eduke32/eduke32.cfg`

```
[Misc]
Executions = 37

[Setup]
ConfigVersion = 321
ForceSetup = 1
NoAutoLoad = 1
SelectedGRP = "DUKE3D.GRP"

[Screen Setup]
Polymer = 0
ScreenBPP = 32
ScreenHeight = 768
ScreenMode = 0
ScreenWidth = 1024
WindowPositioning = 0
WindowPosX = -1
WindowPosY = -1
MaxRefreshFreq = 0
Out = 0
Password = ""

[Controls]
AutoAim = 1
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
JoystickButton0 = "Crouch"
JoystickButton1 = "Jump"
JoystickButton2 = "Open"
JoystickButton3 = "Jetpack"
JoystickButton4 = "Quick_Kick"
JoystickButton5 = "Fire"
JoystickButton6 = "MedKit"
JoystickButton7 = "Toggle_Crosshair"
JoystickButtonClicked7 = "Show_Menu"
JoystickButton8 = "Map"
JoystickButton9 = "Jetpack"
JoystickButton10 = "Previous_Weapon"
JoystickButton11 = "Next_Weapon"
MouseButton0 = "Fire"
MouseButton1 = "MedKit"
MouseButton2 = "Jetpack"
MouseButton4 = "Previous_Weapon"
MouseButton5 = "Next_Weapon"
MouseAnalogAxes0 = "analog_turning"
MouseAnalogAxes1 = "analog_moving"

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
// this file is automatically generated by EDuke32
unbindall
bind "1" "gamefunc_Weapon_1"
bind "2" "gamefunc_Weapon_2"
bind "3" "gamefunc_Weapon_3"
bind "4" "gamefunc_Weapon_4"
bind "5" "gamefunc_Weapon_5"
bind "6" "gamefunc_Weapon_6"
bind "7" "gamefunc_Weapon_7"
bind "8" "gamefunc_Weapon_8"
bind "9" "gamefunc_Weapon_9"
bind "0" "gamefunc_Weapon_10"
bind "-" "gamefunc_Shrink_Screen"
bind "=" "gamefunc_Enlarge_Screen"
bind "BakSpc" "gamefunc_TurnAround"
bind "Tab" "gamefunc_Map"
bind "Q" "gamefunc_Quick_Kick"
bind "W" "gamefunc_Move_Forward"
bind "E" "gamefunc_Open"
bind "R" "gamefunc_Steroids"
bind "T" "gamefunc_SendMessage"
bind "Y" "gamefunc_Show_Opponents_Weapon"
bind "U" "gamefunc_Mouse_Aiming"
bind "I" "gamefunc_Toggle_Crosshair"
bind "[" "gamefunc_Inventory_Left"
bind "]" "gamefunc_Inventory_Right"
bind "Enter" "gamefunc_Inventory"
bind "LCtrl" "gamefunc_Crouch"
bind "A" "gamefunc_Strafe_Left"
bind "S" "gamefunc_Move_Backward"
bind "D" "gamefunc_Strafe_Right"
bind "F" "gamefunc_Map_Follow_Mode"
bind "H" "gamefunc_Holo_Duke"
bind "J" "gamefunc_Jetpack"
bind "K" "gamefunc_See_Coop_View"
bind "SemiColon" "gamefunc_Previous_Weapon"
bind "'" "gamefunc_Next_Weapon"
bind "LShift" "gamefunc_Run"
bind "N" "gamefunc_NightVision"
bind "M" "gamefunc_MedKit"
bind "/" "gamefunc_Jump"
bind "RShift" "gamefunc_Run"
bind "LAlt" "gamefunc_Strafe"
bind "Space" "gamefunc_Jump"
bind "CapLck" "gamefunc_AutoRun"
bind "ScrLck" "gamefunc_Holster_Weapon"
bind "Kpad7" "gamefunc_Aim_Up"
bind "Kpad8" "gamefunc_Move_Forward"
bind "Kpad9" "gamefunc_Look_Up"
bind "Kpad-" "gamefunc_Shrink_Screen"
bind "Kpad4" "gamefunc_Turn_Left"
bind "Kpad5" "gamefunc_Center_View"
bind "Kpad6" "gamefunc_Turn_Right"
bind "Kpad+" "gamefunc_Enlarge_Screen"
bind "Kpad1" "gamefunc_Aim_Down"
bind "Kpad2" "gamefunc_Move_Backward"
bind "Kpad3" "gamefunc_Look_Down"
bind "Kpad0" "gamefunc_Look_Left"
bind "Kpad." "gamefunc_Look_Right"
bind "KpdEnt" "gamefunc_Inventory"
bind "RCtrl" "gamefunc_Fire"
bind "RAlt" "gamefunc_Strafe"
bind "Home" "gamefunc_Aim_Up"
bind "PgUp" "gamefunc_Look_Up"
bind "Left" "gamefunc_Turn_Left"
bind "Right" "gamefunc_Turn_Right"
bind "End" "gamefunc_Aim_Down"
bind "PgDn" "gamefunc_Look_Down"
bind "Insert" "gamefunc_Look_Left"
bind "Delete" "gamefunc_Look_Right"
osdeditpal "12"
osdtextpal "12"
osdtextshade "2"
in_joystick "1"
wchoice "3457860291"
```
