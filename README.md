# Escape: Your Weekend Adventure

TITLE: ESCAPE — Weekend Trip Planner | FRONTEND-ONLY | NO BACKEND | NO DATABASE



IMPORTANT — STRICT DEVELOPMENT CONSTRAINT:

Build this project as a 100% FRONTEND-ONLY application.



DO NOT create, configure, or use:

- Any backend server

- Supabase

- Firebase

- PostgreSQL / MySQL / MongoDB

- Authentication backend

- Server-side API routes

- Edge functions

- Backend services

- Database tables

- Cloud functions

- Any server-side data persistence



Do not add backend-related files, integrations, or dependencies.



Use ONLY frontend technologies and mock/static/local data.

The application must work completely in the browser without any backend.



PROJECT:

ESCAPE — Weekend Trip Planner



GOAL:

Create a polished, modern, responsive weekend trip planning web application that helps users quickly discover a destination, plan activities, estimate the trip budget, create an itinerary, and view the complete weekend plan in one place.



TECH STACK:

- React

- Vite

- Tailwind CSS

- Lucide React icons

- Frontend component architecture

- Mock JSON/static JavaScript data only

- localStorage may be used only for client-side persistence



DESIGN:

Create a premium travel-product experience.

The UI should feel modern, clean, visual, and highly polished.



Use:

- Responsive mobile-first design

- Beautiful destination cards

- Large travel imagery / image placeholders

- Rounded cards

- Subtle shadows

- Clear typography

- Strong visual hierarchy

- Smooth hover and transition effects

- Consistent spacing

- Accessible contrast

- Responsive layout for mobile, tablet, and desktop



CORE USER FLOW:

Home → Discover Destination → Select Weekend Trip → Customize Trip → Build Itinerary → Budget Summary → Final Trip Plan



FEATURES:



1. HOME / HERO

Create a strong landing section with:

- App name: ESCAPE

- Tagline: "Plan your perfect weekend getaway."

- Short supporting description

- Destination search input

- Start date selector

- End date selector

- Number of travelers selector

- "Plan My Weekend" CTA



Add a visually attractive travel hero section.



2. DESTINATION DISCOVERY

Show popular weekend destinations using static mock data.



Each destination card should contain:

- Destination image

- Destination name

- State / country

- Short description

- Estimated travel time

- Estimated starting budget

- Best for tags such as:

  Nature / Adventure / Beach / Food / Culture / Relaxation

- "Explore" button



Include search and filter UI.



Filters:

- Budget

- Distance

- Trip type

- Popularity



3. TRIP CUSTOMIZATION

After selecting a destination, show a trip setup screen.



Allow users to choose:

- Number of travelers

- Trip dates

- Accommodation preference

- Travel preference

- Activity interests

- Approximate budget



Use interactive frontend controls such as:

- Buttons

- Chips

- Sliders

- Dropdowns

- Date inputs



4. ITINERARY BUILDER

Generate a sample weekend itinerary completely on the frontend using mock data.



Example:

DAY 1 — Friday

- Travel

- Hotel check-in

- Dinner



DAY 2 — Saturday

- Breakfast

- Main attraction

- Lunch

- Activity

- Evening exploration

- Dinner



DAY 3 — Sunday

- Breakfast

- Local sightseeing

- Lunch

- Return journey



Allow users to:

- Add activity

- Remove activity

- Reorder activities

- Edit activity details

- Mark activity as completed



All interactions must happen locally in the browser.



5. ACTIVITY CARDS

Each activity should display:

- Activity name

- Time

- Duration

- Location

- Category

- Estimated cost

- Short description



Provide attractive icons for categories.



6. BUDGET PLANNER

Create a frontend budget summary.



Categories:

- Transport

- Stay

- Food

- Activities

- Miscellaneous



Show:

- Category-wise cost

- Total estimated cost

- Cost per traveler

- Remaining budget



Include a clean visual budget breakdown.



7. FINAL TRIP DASHBOARD

Create a final trip overview page containing:

- Destination

- Trip dates

- Number of travelers

- Total budget

- Day-by-day itinerary

- Selected activities

- Accommodation

- Travel information



Add CTA buttons:

- Edit Trip

- Save Trip

- Start Over



"Save Trip" should use localStorage only.



8. SAVED TRIPS

Create a simple saved trips section using localStorage.



Users can:

- View saved trips

- Open a saved trip

- Delete a saved trip



Do not use any database or backend.



9. MOCK DATA

Create realistic static mock data for:

- 8–12 destinations

- Activities

- Hotels/accommodation

- Transport options

- Estimated costs

- Recommended itineraries



No real API calls are required.



10. RESPONSIVENESS

The entire application must be fully responsive.



Desktop:

- Multi-column layouts

- Dashboard-style experience



Tablet:

- Adaptive grid



Mobile:

- Single-column layout

- Touch-friendly controls

- Sticky bottom CTA where appropriate

- Compact navigation



11. ACCESSIBILITY

Implement:

- Semantic HTML

- Proper labels

- Keyboard navigation

- Visible focus states

- ARIA labels where needed

- Accessible buttons and inputs



12. COMPONENT STRUCTURE

Use reusable React components such as:

- Navbar

- HeroSection

- SearchBar

- DestinationCard

- DestinationGrid

- FilterPanel

- TripSetup

- ActivityCard

- ItineraryDay

- BudgetSummary

- TripOverview

- SavedTrips

- Footer



13. UX DETAILS

Add:

- Empty states

- Loading-style skeleton only where visually useful

- Form validation

- Helpful error messages

- Toast notifications for local actions

- Smooth transitions

- Hover states

- Active states



IMPORTANT:

The app must be completely functional using frontend logic and mock/static data.



FINAL RESTRICTIONS:

NO BACKEND.

NO DATABASE.

NO SUPABASE.

NO FIREBASE.

NO API SERVER.

NO SERVER ACTIONS.

NO AUTHENTICATION BACKEND.

NO SERVER-SIDE STORAGE.



Everything must run entirely in the browser.



The final result should look like a hackathon-quality travel planning product, not a basic template.

Prioritize a polished UI, responsive experience, clear user flow, and functional interactions that can be demonstrated within a short live demo.



Before implementing anything, ensure the architecture is frontend-only and does not introduce any backend service.

Only build frontend only

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://escape-my-weekend.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/aac72898-9afc-4b9d-88bc-dccef132f7c2).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
