# Planet-Simulator
My personal version of Bobert13's Planet Simulator for Sid Meier's Civilization V. Specifically based on LamilLerran's LL3 version, and a lot of the climate-generation code being originally from Cephalo's PerfectWorld3 Mapscript. Not too polished yet, but it works just fine if you like what I like. 

**Main Features**
  - Desert tiles bordering forest or jungle are turned into plains.
  - Jungle tiles surrounded by enough mountains get grassland under them. This is to simulate subtropical highlands. 
  - Mountains are assigned continent art-types based on elevation. No visual problems were found in testing on my end.
  - A lot more plains should spawn under forest, especially for the Standard and Arid settings.

**Rainfall Settings**
  - Arid: Small band of jungle, large and reliable band of desert
  - Standard: Modest band of jungle, still large band of desert but with intrusions of plains and jungle poleward more common
  - Wet: Reliably generates intrusions of plains into desert regions, especially along coasts.     

**Temperature Settings**
- Cool: Tundra and grassland in temperate latitudes with scattered forests toward the equator. equatorward retreat of deserts.
- Standard: Should be roughly earth-like in biome distributions. Modest amount of tundra/snow.
- Hot: Expansion of deserts poleward, temperate forests go almost to the edges of the map. Small amount of tundra/snow
