# Sight and light
**Note: This topic is not that easy and short to explain, so this tutorial is much longer than others!**
**To make the topic a little bit more catchy, here is a video from Encounter Library 
which goes into parts of this topic: https://www.youtube.com/watch?v=s60nS56jIH8** 


## Scene settings - grid
In the scene, besides the section *Sight and Lighting*, there is also the grid scaling. The value entered here 
affects the visibility and light range of individual elements in this scene. (Ex.: If a token has a 10 at twilight visibility,
it makes a big difference if a grid is 2 or 20 units. With 2 it can see 5 boxes, with 20 only 2 boxes). 
This setting is directly related to the [Settings on token](en-sight-light#token-settings).  
  
![Gitter 2](images/en-sight-light_0.png)
![Gitter 20](images/en-sight-light_1.png)

## Scene settings - visibility and lighting
1. **Figure View**: If unchecked, all players will always be able to see everything from the map. Furthermore light sources and walls are ignored 
marked tokens are ignored as far as visibility restrictions are concerned. (Movement restrictions still apply).    
2. **Global Lighting**: If unchecked, the map is completely dark. This darkness is only caused by light sources 
or light and sight settings of the tokens (LINK TO TOKEN INSTRUCTION). (Master tip: In maps with outdoor and indoor area deactivate hooks 
and work with light sources in the outdoor area)  
3. **Fog Exploration**: This can be used to influence the gradual uncovering of the map. If the check mark is deactivated, the invisible and/or 
and/or illuminated area will be covered again when the player leaves the area. If the hook is active, at least the scene remains visible, but not the tokens
not the tokens that are there.  
4 **Darkness**: Changes the general darkness value of the scene. If day or night is selected on the map via the sidebar, 
the value for the scene will be set to 0 for day or 1 for night.   
5. **Threshold**: for global illumination** If the check mark is set, the global illumination on the scene will be automatically deactivated as soon as the 
threshold value reached in the controller is exceeded. 
  
![Sicht und Beleuchtung](images/en-sight-light_0.png)

## Token settings
The token has again a completely own setting for its own visibility in darkness (advantage: dark visibility) as well as for the light emitted by it 
emitted light (keyword: torch).  
**Short note** If you open the following settings via a token on the game field, the change only applies to the token placed there.
If you then drag the token from the actors to the field, it will have the "old" values again.   
Open the settings of the desired token via the actor menu. At the top of the window must be [Prototype figure]! 1.  
1. in this window under *Vision* the complete vision and the light of the token is controlled. 
   
![Prototyp Token Vision](images/en-sight-light_0.png)  

### Important settings for TDE: (personal opinion of *tsaath*)
1. **Has Vision**: When checked, all vision restrictions due to lights, walls, etc. apply. If it is deactivated the actor can look over the whole scene.    
2. **Dawn Sight**: Units the actor can see far in the dark with dim light. (Advantage: dark vision)    
3. **Light Vision**: Units the actor can see far in the dark with bright light.  
4. **Radius dim light**: Units in which the actor emits dim light around him (keyword: torch).  
5. **Radius bright light**: Units in which the actor emits bright light around him (keyword: torch).  
6. **Light color**: Color of the emitted light  
7. **color intensity**: Strength of the emitted light  
8. **Animation type**: Whether the light has an effect (keyword: torch).  
Ex: Hero with a torch  
  
![Geron Fackel](images/en-sight-light_1.png)


## Default settings visibility
To avoid having to set the visibility settings to your own default for every new actor you create, 
there are the items *Default visibility (vague)* (4) (*Dawn visibility* in the token) under *Gear* (Settings) (1) -> *Customize settings* (2) -> *System settings* (3)
and *default visibility (clear)* (5) (*bright visibility* in the token). Every newly created actor gets these settings. (Personal opinion: I have both at 0
and control the visibility during daytime only by obstacles, during darkness by twilight vision and flares)  
  
![Systemeinstellungen Sichtweite](images/en-sight-light_0.png)


*Translation information*  
*[x] updated: 2021-06-07*  
*[x] german entry [linked](de/de-sicht_und_licht.md)*  
*[x] automatic translation*  
*[ ] proof read*  
*[ ] change pictures with EN version*
*[ ] change links*  

