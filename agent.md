# Agent Instructions

## Operating Mode

Always work in planning mode unless the user explicitly says `execute`.

Before doing any implementation, file creation, file editing, booking, research action, or final itinerary decision:

1. Analyze the task.
2. Ask clarifying questions.
3. Propose a structured plan.
4. Wait for user approval before executing.

If the user says `execute`, proceed with the approved task while keeping changes scoped and transparent.

## Project Context

Project: Singapore trip planning.

Current trip assumptions:

- Destination: Singapore.
- Travelers: 2 adults.
- Stay: 10-15 November 2026.
- Hotel nights: 5 nights.
- Arrival in Singapore: 10 November 2026 at 18:40.
- Departure from Singapore: 15 November 2026 at 21:00.
- Usable time: arrival evening, 4 full days, and a partial departure day.
- Travel style: comfortable, quiet, safe, walkable, and not rushed.
- Climate consideration: Singapore heat and humidity require rest time daily.
- Hotel budget: approximately 150-200 EUR per night.
- Preferred hotel base: City Hall or Bugis.
- Transport: MRT when easy; taxi/Grab when it reduces heat, walking, or fatigue.
- Food: convenient, good-quality food along the route; food is not the main theme.
- Sentosa: optional only if it fits naturally without rushing.

## Planning Preferences

Use a balanced itinerary style:

- One main outing per day.
- One light evening option per day.
- Daily rest block, especially during midday heat.
- Moderate walking only.
- Avoid noisy nightlife areas and overly packed schedules.

Group attractions geographically to reduce backtracking:

- Marina Bay and waterfront.
- Gardens by the Bay.
- Civic District and museums.
- Bugis / Kampong Glam.
- Chinatown / Telok Ayer if useful.
- Botanic Gardens / Orchard only if it fits the pacing.

## Constraints

- Do not book anything.
- Do not finalize the itinerary without approval.
- Clearly mark assumptions.
- Prefer quiet, safe, central hotel areas.
- Include weather, crowd, and fatigue considerations in planning.
