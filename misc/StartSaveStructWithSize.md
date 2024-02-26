---
ns: MISC
aliases: ["0xbf737600cddbeadd"]
---
## START_SAVE_STRUCT_WITH_SIZE

```c
// 0xBF737600CDDBEADD
void START_SAVE_STRUCT_WITH_SIZE(Any* StructToSave, int SizeOfStruct, string pNameOfStructInstance);
```

More Info

Tells the game that all REGISTER_..._TO_SAVE commands up to the matching [STOP_SAVE_STRUCT](#_0xEB1774DF12BB9F12) are within an instance of this STRUCT. The game can save a bit of memory if you write a procedure to register each struct e.g. PROC RegisterMyStruct(MyStruct &TestMyStruct, STRING NameOfInstanceOfMyStruct) START_SAVE_STRUCT(TestMyStruct, NameOfInstanceOfMyStruct) [REGISTER_INT_TO_SAVE](#_0x34C9EE5986258415)(TestMyStruct.IntWithinMyStruct, "IntWithinMyStruct") STOP_SAVE_STRUCT() ENDPROC You can then call your procedure to register each instance of your STRUCT. You can save STRUCTs within STRUCTs.

