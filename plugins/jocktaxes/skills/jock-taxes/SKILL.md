---
name: jock-taxes
description: Calculate NHL, NFL, MLB, and NBA jock tax, equivalent salary, and player movement with the Jock Taxes tools.
---

Use the Jock Taxes MCP tools for professional-athlete tax questions.

Call `list_tax_calculator_inputs` for leagues, seasons, filing statuses, and team codes. Do not invent team codes.

Call `calculate_nhl_tax`, `calculate_nfl_tax`, `calculate_mlb_tax`, or `calculate_nba_tax` for one team. Call `equivalent_nhl_salary`, `equivalent_nfl_salary`, `equivalent_mlb_salary`, or `equivalent_nba_salary` to match after-tax income on another team. Call `player_movement_nhl`, `player_movement_nfl`, `player_movement_mlb`, or `player_movement_nba` to compare the same pay after a move.

Filing status is `Single` or `Married_Joint`. When the user is signed in, `get_profile` returns the linked Jock Taxes account.
