# dim_useful_queries
Destiny Item Manager (DIM) Useful Queries

## General
```
/* Possible Delete Weapons */
-kills:>=0 -is:extraperk

/* Old Weapons w/o Origin Trait */
season:<lost -is:origintrait is:legendary is:weapon
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
