# Sublime Preferences

## sublime-user-setttings

```
{
	"added_words":
	[
		"lightheadedness",
		"Angiotensin",
		"carvedilol",
		"succinate",
		"bisoprolol",
		"aldosterone",
		"Hydralazine",
		"Warfarin",
		"warfarin",
		"afib",
		"hydralazine",
		"nirtrate",
		"dyspnea",
		"affordability",
		"Bp",
		"multimorbidity",
		"comorbidities",
		"dropdown",
		"timedoc",
		"valign",
		"javascript",
		"js",
		"admin",
		"sms",
		"meth"
	],
	"font_size": 10,
	"ignored_packages":
	[
		"Vintage"
	],
	"ignored_words":
	[
		"Wks",
		"meds",
		"nokogiri",
		"regexes"
	],
	"spell_check": true,
	"tab_size": 2,
	"translate_tabs_to_spaces": true
}

```

## sublime-key-bindings
The keybindings I use in sublime text to maximize my productivity


 ```
[
  { "keys": ["alt+a"], "command": "move_to", "args": {"to": "bol", "extend": false} },
  { "keys": ["alt+e"], "command": "move_to", "args": {"to": "eol", "extend": false} },
  { "keys": ["shift+alt+a"], "command": "move_to", "args": {"to": "bol", "extend": true} },
  { "keys": ["shift+alt+e"], "command": "move_to", "args": {"to": "eol", "extend": true} },
  { "keys": ["alt+b"], "command": "move", "args": {"by": "characters", "forward": false} },
  { "keys": ["alt+f"], "command": "move", "args": {"by": "characters", "forward": true} },
  { "keys": ["shift+alt+b"], "command": "move", "args": {"by": "characters", "forward": false, "extend": true} },
  { "keys": ["shift+alt+f"], "command": "move", "args": {"by": "characters", "forward": true, "extend": true} },
  { "keys": ["ctrl+alt+b"], "command": "move", "args": {"by": "words", "forward": false} },
  { "keys": ["ctrl+alt+f"], "command": "move", "args": {"by": "word_ends", "forward": true} },
  { "keys": ["ctrl+shift+alt+b"], "command": "move", "args": {"by": "words", "forward": false, "extend": true} },
  { "keys": ["ctrl+shift+alt+f"], "command": "move", "args": {"by": "word_ends", "forward": true, "extend": true} },
  { "keys": ["alt+u"], "command": "move", "args": {"by": "lines", "forward": false} },
  { "keys": ["alt+d"], "command": "move", "args": {"by": "lines", "forward": true} },
  { "keys": ["alt+shift+u"], "command": "move", "args": {"by": "lines", "forward": false, "extend": true} },
  { "keys": ["alt+shift+d"], "command": "move", "args": {"by": "lines", "forward": true, "extend": true} },
  { "keys": ["ctrl+alt+u"], "command": "swap_line_up" },
  { "keys": ["ctrl+alt+d"], "command": "swap_line_down" },
  { "keys": ["ctrl+tab"], "command": "next_view" },
  { "keys": ["ctrl+shift+tab"], "command": "prev_view" },
  { "keys": ["alt+k"], "command": "scroll_lines", "args": {"amount": 1.0 } },
  { "keys": ["alt+j"], "command": "scroll_lines", "args": {"amount": -1.0 } },
  { "keys": ["ctrl+alt+w"], "command": "close_all" }
]
```
