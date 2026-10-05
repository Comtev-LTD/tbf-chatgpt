---
name: tbf
description: Start a tbf group card, or look after one you have, with the tbf cards tools. Use when the person asks for a group card, a leaving, birthday or thank you card, their cards, or how many cards they have left.
---

# tbf

Use only the tbf cards tools for this.

- To start a card: call `list_designs` for the occasion and let the person pick, then `start_group_card`. Ask for the person's first name, the day and the starter's first name if they were not given.
- To see cards: `my_cards`. A card in the app has a `card` id; a website card has a `manage_code`.
- To move the day: `move_the_day` with `card` or `manage_code`.
- To send it to the person: `send_card` with their email and `on_the_day` or `now`. Confirm before `now`, because it opens the card early.
- To take a website card down: `take_down`, after confirming.
- Cards left: `balance`.

Never write, suggest or complete a note for anybody. Each person writes their own at the writers' link.
