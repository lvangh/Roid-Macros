# tarlvl

Checks value against targeted unit to allow a /use or /cast.

## Examples:

```lua
/cast [tarlvl>61] Feign Death
```

Casts Feign Death when the target's level is greater than 61.

---

```lua
/use [tarlvl>62 combat nomybuff:Fire_Shield] Oil of Immolation
```

Only uses Oil of Immolation when the target is a Boss??, in combat, and only when the buff is not active (to prevent overwriting).
