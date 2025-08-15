# Destiny Item Manager (DIM) - Useful Queries
Useful Queries for searching and cleaning your vault

## General
```
/* Likely Never Used Weapons (Kill counter only check the currently set option) */
Kills:<1
```

## Edge of Fate (Season 27)
```
/* Barrier S27 */
breaker:barrier or ((is:scoutrifle or is:pulserifle) -breaker:any)

/* Overload S27 */
breaker:overload or ((is:shotgun or is:autorifle or is:smg) -breaker:any)

/* Unstoppable S27 */
breaker:unstoppable or ((is:sniperrifle or is:handcannon or is:sidearm) -breaker:any)
```


# Old Queries

## General
```
/* Possible Delete Weapons */
-kills:>=0 -is:extraperk

/* Old Weapons w/o Origin Trait */
season:<lost -is:origintrait is:legendary is:weapon
```

## Edge of Fate Prep
```
/* "Illegal" armor for EoF */ 
is:armor -is:exotic ((basestat:mobility:>19 basestat:strength:>19) or (basestat:mobility:>19 basestat:intellect:>19))
```

## Episode: Heresy (Season 26)
```
/* Barrier S26 */
breaker:barrier or ((is:sidearm or is:sniperrifle) -breaker:any)

/* Overload S26 */
breaker:overload or ((is:machinegun or is:tracerifle) -breaker:any)

/* Unstoppable S26 */
breaker:unstoppable or ((is:fusionrifle or is:glaive) -breaker:any)

/* S26 Seasonal Weapons w/o Double Origin Trait */ 
exactperk:"willing vessel"  -exactperk:"runneth over"
```
