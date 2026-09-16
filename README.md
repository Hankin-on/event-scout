# Event Scout

Phone app JSON feeds. Split into 14-day parts so each file stays under the GitHub connector cap.

This repo ships two independent feeds. Point phone Settings at the raw index URLs for that person.

## User (feed 1)
https://raw.githubusercontent.com/Hankin-on/event-scout/main/index-local.json
https://raw.githubusercontent.com/Hankin-on/event-scout/main/index-away.json

Fallback merged (optional until Settings follows the index):
https://raw.githubusercontent.com/Hankin-on/event-scout/main/local-events.json
https://raw.githubusercontent.com/Hankin-on/event-scout/main/away-events.json

Parts: local-p1.json .. local-p4.json, away-p1.json .. away-p4.json

## User 2 (feed 2)
https://raw.githubusercontent.com/Hankin-on/event-scout/main/user2-index-local.json
https://raw.githubusercontent.com/Hankin-on/event-scout/main/user2-index-away.json

Fallback merged (optional):
https://raw.githubusercontent.com/Hankin-on/event-scout/main/user2-local-events.json
https://raw.githubusercontent.com/Hankin-on/event-scout/main/user2-away-events.json

Parts: user2-local-p1.json .. user2-local-p4.json, user2-away-p1.json .. user2-away-p4.json
