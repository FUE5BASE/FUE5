![header2](https://user-images.githubusercontent.com/127543827/235319284-d7505107-d0af-4275-a5be-f65301345823.jpg)
# FUE5
Factorio in Unreal Engine 5 (FUE5) is a fan-made project with the goal to see what would Factorio look like and behave in 3D.

WHAT YOU NEED TO KNOW TO RUN THIS PROJECT:

1. Download and install Unreal Engine 5.1 https://www.unrealengine.com/en-US/download
2. Download this project. Either via GitHub Desktop app or just by getting the .zip file.
3. Run the project by opening FUE5.uproject
4. The project is set to load simple "Welcome" scene containing several buildings. 

#FAQ
**How does it work?**

Nuke wrote a Factorio mod which exports the ingame base as a .json text file. This text file is then automatically imported to the UE5 project and creates the exact 3D replica of your ingame base in UE5 with a click of a button.

*Is there any gameplay?*

No. All you can do is to fly around your base and toy around with existing assets and UE construction and event blueprints. For those with experience in UE there is a lot of fun stuff you can do with the blueprints we've designed for the belt, rail and logistic systems.

*Where did we get the assets?*

We created them from scratch in Cinema4D based on pictures from the game. There were some problems getting the game-ready topology right but with practice I was able to replicate several structures per day.

*Why Unreal Engine 5?*

It looks awesome and it's blueprint system is perfect for replicating Factorio ingame systems if you don't know how to code. It also beats the standard 3D editors like Cinema4D or Blender in this particular application where you need to get realtime results.

*Can my PC run this project?*

I've specifically bought RTX4090 just to be able to work the scenes in this trailer at around 30-60 FPS. I always had the settings on maximum tho. We have poor LODs optimization and the amount of iterations our blueprint systems calculate each tick is through the roof so the performance could be improved ten fold with the proper approach.

Special thanks to Phorge who helped us with some core technical UE problems at the beginning of the project! https://www.artstation.com/phorge
