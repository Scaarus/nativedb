---
ns: NETWORK
aliases: ["0x74fb3e29e6d10fa9"]
---
## NETWORK_GET_NP_UNAVAILABLE_REASON

```c
// 0x74FB3E29E6D10FA9
np_unavailability_reason NETWORK_GET_NP_UNAVAILABLE_REASON();
```

```
Returns the reason why the NP service is unavailable. Will return REASON_INVALID if this function is called when Np is available and will assert

Possible return values:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 238 | Other |
| 239 | System Update |
| 240 | Game Update |
| 241 | Signed Out |
| 242 | Age |
| 243 | Connection |
```
