# Roll

Weechat plugin to roll dice with modifiers

## example syntax:

| input:           | result: |
| ---------------- |:--------|
| /roll            | display help text |
| /roll hello         | "[1d20] hello" |
| /roll 10            | "[1d10]" |
| /roll 10 subway     | "[1d10] subway" |
| /roll 1d6           | "[1d6]" |
| /roll 2d20 to save  | "[2d20] to save" |
| /roll 10 + 2        | "[1d10] + 2" |
| /roll 1d6 + 2       | "[1d6+2]" |
| /roll 1d6+2 to hit  | "[1d6+2] to hit" |

you can use a negative modifier to the dice roll (e.g. 1d6-4).
If you do so, the lowest it will return is 1