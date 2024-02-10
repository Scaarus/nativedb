---
ns: NETWORK
aliases: ["0xf7b2cfde5c9f700d"]
---
## NETWORK_FIND_MATCHED_GAMERS

```c
// 0xF7B2CFDE5C9F700D
bool NETWORK_FIND_MATCHED_GAMERS(int nActivityID, float fSkill, float fLowerLimit, float fUpperLimit);
```

Request a listing of the gamers in the given crew that are currently active


## Parameters
* **nActivityID**: activity ID to use
* **fSkill**: skill at activity from 0.0 to 1.0
* **fLowerLimit**: lower limit of matched skill value (i.e. no lower than 0.7). Default of -1.0 means 0.1 less than provided skill
* **fUpperLimit**: upper limit of matched skill value (i.e. no higher than 0.7). Default of -1.0 means 0.1 more than provided skill
