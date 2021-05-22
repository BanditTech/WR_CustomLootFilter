This will act as a resource for sharing CLF ideas. 

Add to the README in each category folder, or make a new file with a descriptive name.

Shared code must be valid JSON sections.

Example Code:

```JSON
{
 "~~Generic Filter": {
  "ElementList": [
   { "ElementList": [
     { "#Key": "TopTierES",   "Eval": ">=",   "Min": 1,   "Type": "Prop",   "Weight": 1 },
		 { "#Key": "TopTierLife",   "Eval": ">=",   "Min": 1,   "Type": "Prop",   "Weight": 1 },
		 { "#Key": "# to maximum Life",   "Eval": ">=",   "Min": 99,   "Type": "Affix",   "Weight": 1 }
    ], "GroupType": "Count", "TypeValue": 1, "Weight": 2 },
   { "ElementList": [
     { "#Key": "# to maximum Energy Shield",   "Eval": "<=",   "Min": 0,   "Type": "Prop",   "Weight": 1 },
		 { "#Key": "# to maximum Life",   "Eval": "<=",   "Min": 0,   "Type": "Prop",   "Weight": 1 },
		 { "#Key": "PrefixCount",   "Eval": "<=",   "Min": 2,   "Type": "Prop",   "Weight": 1 }
    ], "GroupType": "And", "TypeValue": 3, "Weight": 1 },
   { "ElementList": [
     { "#Key": "# to maximum Energy Shield",   "Eval": ">=",   "Min": 1,   "Type": "Prop",   "Weight": 1 },  
		 { "#Key": "#% increased Energy Shield",   "Eval": ">=",   "Min": 1,   "Type": "Prop",   "Weight": 1 }
    ], "GroupType": "And", "TypeValue": 2, "Weight": 1 },
   { "#Key": "TopTierMS", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "#Key": "% increased Movement Speed", "Eval": ">=", "Min": 31, "Type": "Affix", "Weight": 2 },
   { "#Key": "#% to Cold Damage over Time Multiplier", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Cold Damage over Time Multiplier", "Eval": ">=", "Min": 24, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Cold Damage over Time Multiplier", "Eval": ">=", "Min": 34, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Fire Damage over Time Multiplier", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Fire Damage over Time Multiplier", "Eval": ">=", "Min": 24, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Fire Damage over Time Multiplier", "Eval": ">=", "Min": 34, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Physical Damage over Time Multiplier", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Physical Damage over Time Multiplier", "Eval": ">=", "Min": 24, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Physical Damage over Time Multiplier", "Eval": ">=", "Min": 34, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Chaos Damage over Time Multiplier", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Chaos Damage over Time Multiplier", "Eval": ">=", "Min": 24, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Chaos Damage over Time Multiplier", "Eval": ">=", "Min": 34, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Damage over Time Multiplier", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Damage over Time Multiplier", "Eval": ">=", "Min": 12, "Type": "Affix", "Weight": 1 },
   { "#Key": "#% to Damage over Time Multiplier", "Eval": ">=", "Min": 16, "Type": "Affix", "Weight": 1 },
   { "#Key": "# to Level of Socketed Gems", "Eval": ">=", "Min": 1, "Type": "Affix", "Weight": 1 },
   { "#Key": "# to Level of Socketed Gems", "Eval": ">=", "Min": 2, "Type": "Affix", "Weight": 2 },
   { "#Key": "# to Level of Socketed Gems", "Eval": ">=", "Min": 3, "Type": "Affix", "Weight": 2 },
   { "#Key": "Attacks have #% to Critical Strike Chance", "Eval": ">=", "Min": 0.9, "Type": "Affix", "Weight": 2 },
   { "#Key": "#% to Spell Critical Strike Chance", "Eval": ">=", "Min": 0.9, "Type": "Affix", "Weight": 2 },
   { "#Key": "TopTierResists", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "#Key": "TopTierResists", "Eval": ">=", "Min": 2, "Type": "Prop", "Weight": 2 },
   { "#Key": "TopTierRarity", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "#Key": "TopTierRarity", "Eval": ">=", "Min": 2, "Type": "Prop", "Weight": 2 },
   { "#Key": "TopTierCritChance", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "#Key": "TopTierCritMulti", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "ElementList": [
			{ "#Key": "TopTierCritChance", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
			{ "#Key": "TopTierCritMulti", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 }
    ], "GroupType": "And", "TypeValue": 2, "Weight": 2 },
   { "#Key": "TopTierCastSpeed", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 },
   { "#Key": "TopTierAttackSpeed", "Eval": ">=", "Min": 1, "Type": "Prop", "Weight": 1 }
  ],
  "GroupType": "Count",  "StashTab": 11,  "TypeValue": 4
 }
}
```