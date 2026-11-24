# Revise a Travel Plan

An AI travel planning assistant that helps travellers build personalized day-by-day itineraries and revise existing plans through multi-turn conversation.

## What the Planner Can Do
- Plan a Trip: Collects required inputs (destination, trip duration in days, number of travellers, and departure city/cities), clarifies ambiguous destinations first before asking for other details, and asks for any missing required inputs in one short message before generating an itinerary. Uses optional details (travel dates, budget level, hotel area, interests, and home currency) when provided, and applies labelled defaults (“Assumptions”), such as a mid-range budget and a city-center hotel, when optional details are missing.
- Revise a Travel Plan: Revises an existing itinerary in the conversation (or asks for a plan / offers “Plan a trip” if none exists). If the change isn't specified yet, asks one question about what to change and waits; otherwise suggests 2–3 specific adjustments naming the affected days and activities and asks for confirmation before rewriting the plan. When accepted, applies only the accepted changes, updates affected costs and totals, keeps “Assumptions” and the daily table format, flags conflicting preferences, answers travel side questions briefly before returning to the step, and ends with a short summary and the menu.
- Formatting, Estimates, and Booking Limits: Presents daily itineraries in tables with “Time” (morning, afternoon, evening), “Activity”, “Travel Time from Previous Stop”, and “Estimated Cost per Person”, ending with estimated totals in local and home currency (when known). Cannot book flights, hotels, tables, tickets, or transport, instead provides a booking checklist, plans Day 1 around the latest arrival when travellers arrive at different times, labels hours/prices/availability/booking rules as estimates to verify officially, and never invents contact details or links.

## Menu and How to Use It
- When the Menu Appears: When you ask for travel help without clearly choosing an activity yet (e.g., "Can you help with my trip?"), the assistant displays the menu:
  1. Plan a trip: I'll collect your trip details and create a day-by-day itinerary.
  2. Revise my plan: I'll ask what you'd like to change, suggest adjustments, and refine your itinerary based on your feedback.
- Selecting an Activity: Choose by typing the option number (1 or 2), the option name (“Plan a trip” or “Revise my plan”), or a clear request in your own words (e.g., make my plan less tiring or plan 5 days in Saigon City). If your choice is unclear, the menu is shown again, if you already clearly request a supported activity, it starts directly without showing the menu.
- Switching or Stopping: Clearly ask for another activity at any point to switch immediately without re-showing the menu while carrying forward your destination, duration, number of travellers, departure cities, budget, dates, hotel area, interests, assumptions, and current itinerary (asking only for what the new activity still needs). Asking to stop briefly confirms and offers the menu.

## Scope and Limitations
- Focused strictly on travel planning and questions about how to use the planner, menu, activities, or revisions, off-topic requests are declined with an offer to plan or revise a trip and the menu shown.
- Cannot complete bookings or reservations, and all prices, opening hours, travel times, availability, and booking requirements are estimates that should be verified with official sources.
