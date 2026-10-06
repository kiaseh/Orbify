# Orbify
Duckable's Orbify improved

## How to use
1) Import the module from the 'Releases' tab
2) Place it in any area accessible by the client (ReplicatedStorage recommended)
3) Create a LocalScript in `StarterPlayer/StarterPlayerScripts`
4) In the aforementioned script, require 'Orbify'

```
const RepicatedStorage = game:GetService('ReplicatedStorage')

const Orbify = ReplicatedStorage.Orbify -- Recommended that you put the module under a folder named 'Packages', 'Libraries' or 'Modules'
```
5) Now call the Create Method from the module.

```
Orbify:Create(...)
```
6) Fill out the parameters

startPosition: Where the orb(s) will appear from
target: The Part/Vector3 the orb(s) will follow to complete the animation.
```
Orbify:Create(startPosition: Vector3, target: BasePart | Vector3)
```

The animation should now play.


https://github.com/user-attachments/assets/db6445d7-8050-49ba-831e-4523d87ea25f

You did it!

## Config
If you noticed, there was a third parameter named 'config'.
config allows you to configure 
