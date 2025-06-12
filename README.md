# GourmetGhar



8-Week Scrum-Based Timeline (June 17 – August 12, 2025)
🔁 Sprint Format
Sprint Duration: 1 week

Sprint Review: Every Sunday evening

Daily Standup: Async (Google Chat/Notion update)

Tools: GitHub, Notion/Trello, Postman, VSCode Live Share (for remote collab)

🏁 Sprint 0 – Planning & Setup (June 17–23)
Task	Owner
Define architecture, modules, and features	Both
Set up GitHub repo, board, virtual envs	Person A
React.js + Bootstrap setup	Person B
Wireframes: Pantry, Recipe, Cart, Analytics	Person B
Dataset Collection: Pantry items, recipes, nutrition info	Person A
Define data flow (image → ingredients → recipes → cart)	Both

✅ Deliverables: Dev environment ready, wireframes, task board setup

🧱 Sprint 1 – Core Setup (June 24–30)
Task	Owner
Backend skeleton (FastAPI + DB models)	Person A
YOLOv8 installation and trial training	Person B
Static React UI pages: Profile, Pantry, Cart	Person B
Define schema: User, PantryItem, Recipe, CartItem	Person A
Frontend pages scaffolded with dummy content	Person B

✅ Deliverables: UI templates, backend skeleton, early YOLO test

🔍 Sprint 2 – Pantry Detection & Upload (July 1–7)
Task	Owner
Complete YOLOv8 pantry detection pipeline	Person B
Backend API: /upload-image returns detected ingredients	Person A
React upload form with detection result display	Person B
Pantry view component to edit/verify items	Person B
Save pantry data in backend (Postgres/SQLite)	Person A

✅ Deliverables: Pantry detection from image working end-to-end

🧠 Sprint 3 – Recipe Matching Engine (July 8–14)
Task	Owner
Recipe dataset curation + normalization	Person A
Implement ingredient-based recipe filtering	Person A
API: /get-recipes from pantry ingredients	Person A
RecipeCard UI component	Person B
Integrate frontend filters → API	Person B

✅ Deliverables: Ingredient-matching recipe suggestions shown on UI

🥗 Sprint 4 – Macros + Nutrition Goals (July 15–21)
Task	Owner
Add profile setup: age, calorie, macro targets	Person B
Integrate Nutrition API (Edamam/Nutritionix)	Person A
Enhance recipe filtering using macro similarity	Person A
Add sliders: Calories, Protein, Carbs, Fats	Person B
Add macro bar in recipe cards	Person B

✅ Deliverables: Personalized recipes based on macro targets

🛒 Sprint 5 – Cart Agent + Reordering Logic (July 22–28)
Task	Owner
Auto-cart logic: compare pantry vs recipe needs	Person A
Cart component UI with editing features	Person B
Backend API: /generate-cart, /place-order	Person A
Pantry expiry alerts (APScheduler / daily check)	Person A
Toast alerts, confirmation modals	Person B

✅ Deliverables: Smart cart + reorder assistant completed

📈 Sprint 6 – Analytics + Final Polish (July 29–Aug 4)
Task	Owner
Macro/Calorie tracking dashboard (Recharts)	Person B
Weekly intake vs target bar/pie charts	Person B
Add loader/spinners, polish UI	Person B
Endpoint for daily intake logging (if time permits)	Person A
Minor bug fixing & code cleanup	Both

✅ Deliverables: Beautiful and informative analytics dashboard

🎯 Sprint 7 – Testing, Documentation & Demo (Aug 5–12)
Task	Owner
Final integration testing	Both
Prepare demo walkthrough (video or slides)	Person B
Write README with setup steps + endpoints	Person A
Collect user feedback from peers	Both
Polish UI and animations	Person B

✅ Deliverables: Project ready to showcase, fully functional

🗂 Suggested Tools
Category	Tool
Version Control	GitHub
Frontend	React.js, Bootstrap, Axios, Recharts
Backend	Python, FastAPI, SQLite/Postgres, Nutritionix/Edamam API
ML & CV	OpenCV, YOLOv8, PyTorch
Project Mgmt	Trello, Notion
Testing	Postman, React Testing Library, pytest
Deployment (optional)	Render / Vercel / Docker (if desired)
