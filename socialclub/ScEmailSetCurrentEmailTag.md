---
ns: SOCIALCLUB
aliases: ["0x07dbd622d9533857"]
---
## SC_EMAIL_SET_CURRENT_EMAIL_TAG

```c
// 0x07DBD622D9533857
bool SC_EMAIL_SET_CURRENT_EMAIL_TAG(string tag);
```

Sets current 'tag' used for email messages. You can set these tags - {"gta5email", "gta5mkt_en", "gta5mkt_fr", "gta5mkt_ge", "gta5mkt_it", "gta5mkt_sp", "gta5mkt_pt", "gta5mkt_pl", "gta5mkt_ru", "gta5mkt_ko", "gta5mkt_ch", "gta5mkt_ja", "gta5mkt_me", "gta5mkt_cn"} -. By default the system will reset the current email tag to "gta5email" when you call [`SC_EMAIL_RETRIEVE_EMAILS`](#_0x040ADDCBAFA1018A) for the cases You forget to do it. So your code should always have something like this when you want to retrieve marketing messages: SC_EMAIL_SET_CURRENT_EMAIL_TAG("gta5mkt_en" | "gta5mkt_fr" | "gta5mkt_ge", etc ...) SC_EMAIL_RETRIEVE_EMAILS(...) ==> this way you dont need to worry about if you are using the correct tag or not.

