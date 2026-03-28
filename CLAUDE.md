# Euro Summer Travel Planning Workspace

This is a travel planning workspace for a European summer trip. Claude Code acts as a travel planning assistant that remembers all plans, preferences, and logistics.

## How This Workspace Works

- All travel data lives in structured Markdown files under `plans/`
- Claude should read these files to understand the current state of the trip
- When the user updates plans, Claude should edit the relevant files to keep everything in sync
- Always respond in the user's language (Korean preferred)

## Directory Structure

- `plans/itinerary.md` - Day-by-day travel itinerary
- `plans/budget.md` - Budget tracking and expenses
- `plans/accommodations.md` - Hotel/hostel/Airbnb bookings
- `plans/flights.md` - Flight information and bookings
- `plans/packing.md` - Packing checklist
- `plans/food.md` - Restaurant recommendations and food plans
- `plans/activities.md` - Activities, tours, and attractions
- `plans/notes.md` - General notes, tips, and reminders

## Conventions

- Dates use `YYYY-MM-DD` format
- Currency amounts include the currency code (e.g., `€150`, `$200`)
- Status markers: `[ ]` = pending, `[x]` = done/booked, `[~]` = in progress
- Priority markers: `(!)` = important, `(?)` = need to decide
