---
type: character
campaign: "Journeys Beyond Dusk"
cssclass: character
dg-publish: true
---

# Vuldar Jensen (Mantis)


## Backstory

Something unknown in Vuldar's past has made him a recluse, roaming around the Forge and offering his services to anyone who can offer him an opportunity to assuage his guilt.

## Stats and Meters
```dataview
TABLE Edge, Heart, Iron, Shadow, Wits
FROM #stats
```
```dataview
TABLE Health, Spirit, Supply, Wealth, Momentum
FROM #meters
```
## CONDITIONS
### Misfortunes
```dataview
TABLE WITHOUT ID Wounded, Shaken, Unprepared
FROM #conditions 
```
### Lasting Effects
```dataview
TABLE WITHOUT ID Harmed, Traumatized
FROM #conditions 
```
### Burdens
```dataview
TABLE WITHOUT ID Doomed, Tormented, Indebted
FROM #conditions 
```

## Legacies
```dataview
TABLE TrackImage
FROM #legacy
```
```dataview
TABLE XPEarned, XPSpent
FROM #legacy 
```
## Vows IN-PROGRESS
```dataview
TABLE Name, TrackImage
FROM #incomplete WHERE file.name != "Progress_Template" 
```
