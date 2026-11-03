# The-Red-Lantern-VR
VR Mod for The Red Lantern

**TEST BUILD** **TEST BUILD** **TEST BUILD** **TEST BUILD**

CONTROLS - the Quest controllers are the game's gamepad (the game shows gamepad prompts)
-
  A ..................... Confirm 
  
  B ................... Cancel / back
  
  X ..................... Camp  
  
  Y ................... Map (hold)
  
  Left stick click ...... Pause    
  
  Right stick click ... Show resources
  
  Left trigger .......... hold breath / lean left  Right trigger ....... fire / lean right
                          (right trigger on an orange dot also confirms: pet a dog...)
                          
  Left grip ............. LB
  
  Right grip .......... RB (toggle laser)
  
  Left stick ............ left stick (menus: move the selection)
  
  Right stick ........... turn (snap 30 degrees, or smooth); in menus it is the game's right stick
  
  Right controller laser  menus / story box: point at a button = it is selected, right trigger = press it.
                          In the world: point at a dog / thing (orange dot = clickable), right trigger = Confirm.
                          
  Both stick clicks ..... re-centre the view
  
  Hold both stick clicks 1.2 s ... VR SETTINGS MENU (stick up/down choose, left/right change, A toggle, B close)
  
  The game window must have focus (click it once) - the game ignores all input otherwise.
  
  Gamepad off: [Controls] Gamepad = false. Extra keyboard keys on buttons: [Controls.ExtraKeys].

VIEW
-
  * Riding / camp: you sit at the game's sled camera and look around freely with your head. When the trail bends your
    view turns with the sled ("View turns with the sled"). The right stick turns you on top of that.
  * The hood moves with your head (VR settings menu: Hood = FollowHead / Hidden / Game, with forward / up offsets).
  * The HUD stays in front of your eyes (setting "HUD stays in front of your eyes"; size / distance in the menu).
  * Pointing: Settings menu > Pointing > "Reticle follows": RightController (laser) or Head (look at things).
  * The story / choice box: shown on a screen in front of you (the world stays in VR); point at a choice, trigger.
  * Encounters / cut-scenes with their own camera: you stand at that camera; your view turns with it on a shot change.
  * Menus (start, pause, journal, options, save, map) or time stopped: the game's picture on a screen in front of you;
    point the laser at it, trigger = click / press the button, grip = right click.
  * The game's flat window shows only the HUD in play (the VR eyes draw the world - faster); black = see-through.
  * The game's post-processing (colours, bloom) is used for the VR eyes.
  * Headset picture upside down: FlipEyes. Menus upside down / laser up-down wrong: ScreenPictureFlip / ScreenGeometryFlip.
  * Render scale (restart), world scale, eye height, near clip: VR settings menu or the config.
