---
ns: STATS
aliases: ["0xb7257ba2550ea10a"]
---
## PLAYSTATS_COPY_RANK_INTO_NEW_SLOT

```c
// 0xB7257BA2550EA10A
void PLAYSTATS_COPY_RANK_INTO_NEW_SLOT(int slotUsed, int copyOption, int propertyAwarded, int characterInSlot, int rank, int previousRank, int totalTime);
```

```
Telemetry sent whenever a new character enters GTAO for first time slotUsed - Character slot used (INT) copyOption - Did player reject the 'copy rank option (INT - "0" = YES, "1" = NO, "2 = Player did not have option). propertyAwarded - Property Awarded (INT - "0" to "4", one for each of the 5 options) characterInSlot - does player have existing character in the other slot? YN (BOOL) rank - rank of existing character in other slot (INT - send '8001' if player doesn't have an existing character) previousRank - if player deleted a character in order to start a new character in the same slot, what rank was that previous character (INT - send '8001' if player did not have to delete a previous character) totalTime - total playing time on deleted character slot (INT - send "0" if player did not have an existing character slot).
```
