📅 8-Week Scrum Plan: Subscription Tracker App
Team: Gayatri (Product + Frontend Dev),
 Shubham (Backend + AI), 
Chandana (UI + QA), 
Nigam (Automation + Testing)
Weekly sprints with 2–3 day check-ins and a demo every Friday

🔄 General Roles
Member	Role
Gayatri	Product Owner, Frontend UI, n8n flows
Shubham	Backend (Supabase, Flask, GPT APIs)
Chandana	UI Design, Component Styling, QA Testing
Nigam	n8n setup, Notification Automation, Testing

🧭 Sprint Summary Table
Week	Sprint Goal	Heavy Load (Gayatri & Shubham)	Moderate Load (Chandana & Nigam)
1	Project Setup & Auth Flow	Supabase/Firebase setup, login logic (Shubham), Flutter/React login screens (Gayatri)	App logo + splash screen (Chandana), user stories in Notion + project board setup (Nigam)
2	Subscription CRUD & DB Integration	Backend schema + API endpoints (Shubham), Add/edit UI screens (Gayatri)	UI polish (Chandana), Test data input manually (Nigam)
3	Subscription List View + Monthly Cost Calc	Fetch/display logic, group by date (Gayatri), server-side filtering logic (Shubham)	UI design feedback (Chandana), write test cases (Nigam)
4	Reminder Logic (n8n + Twilio/Email)	Build DB to cron reminder connector (Shubham), WhatsApp/email trigger flow (Gayatri)	Twilio setup, dummy flows test (Nigam), create reminder template UI (Chandana)
5	Smart GPT Insights & Optimization Tips	Flask API + GPT prompt handler (Shubham), frontend display of suggestions (Gayatri)	UI for suggestions card (Chandana), test API responses (Nigam)
6	Cancellation Assistant & GPT Chat Commands	GPT "cancel" prompt builder (Shubham), UI buttons for cancel flow (Gayatri)	Build FAQ/help screen (Chandana), test each cancellation use case (Nigam)
7	Polish & Refactor + Chatbot Integration	Bug fixing + GPT flow improvements (Shubham), chatbot interface setup (Gayatri)	UI theme consistency (Chandana), chatbot test conversations (Nigam)
8	Final Testing + Launch	Deployment, README, launch (Shubham), pitch site + final polish (Gayatri)	User manual PDF (Chandana), cross-device testing (Nigam)

🧱 Weekly Sprint Breakdown
🗓️ Week 1: Setup & Auth
Sprint Goal: Complete login/signup using Supabase Auth

Shubham: Supabase setup, user auth schema, initial DB

Gayatri: Frontend login/signup forms, connect to Supabase

Chandana: Create onboarding UI screen + logo

Nigam: Set up project board in Notion + task management

🗓️ Week 2: Subscriptions CRUD
Sprint Goal: Build subscription add/edit/delete UI & backend

Shubham: CRUD APIs for subscriptions

Gayatri: Add/Edit/Delete screens with validation

Chandana: Style buttons/forms, field validations

Nigam: Add sample subs for testing, DB integrity checks

🗓️ Week 3: Dashboard + Monthly Summary
Sprint Goal: Display subscriptions & total spend

Shubham: Backend filter by month logic, cost summary API

Gayatri: Dashboard layout with card-style views

Chandana: UI enhancements, icons for services

Nigam: Build test cases, try weird edge inputs

🗓️ Week 4: Reminder Notifications
Sprint Goal: n8n flow to send reminders before due date

Shubham: Script to fetch subs due in 3 days

Gayatri: Build n8n flow + webhook to Twilio/SendGrid

Chandana: Reminder card UI, test screens

Nigam: Run and validate reminder flows on test data

🗓️ Week 5: GPT-Based Optimization
Sprint Goal: Show AI-powered suggestions to save money

Shubham: Build Flask route + GPT call to analyze subs

Gayatri: Display GPT response in a neat "Tip Card"

Chandana: Design Tip Card UI and animation

Nigam: Validate tips make sense, check prompt reliability

🗓️ Week 6: Cancellation Flow
Sprint Goal: GPT-assisted cancellation instructions

Shubham: Prompt library for “cancel [service]”

Gayatri: UI buttons + display steps, optional email generator

Chandana: Help screen design (FAQ style)

Nigam: Run cancel tests for 5 services (Netflix, Hotstar etc.)

🗓️ Week 7: Final Polish + Chatbot
Sprint Goal: Add a chatbot and polish UX/UI

Shubham: Bug fixes in backend, chatbot API integration

Gayatri: Chat UI and command parser

Chandana: Theme styling, check dark mode

Nigam: Full flow test + chatbot convo test cases

🗓️ Week 8: Final Testing & Launch
Sprint Goal: Launch MVP publicly and polish

Shubham: Deploy backend (Render), clean codebase

Gayatri: Landing page (Carrd or React), app store deploy/test

Chandana: Create user guide PDF, marketing screenshots

Nigam: Final QA test, cross-device compatibility check

📂 Project Tools
Purpose	Tool
Task Management	Notion or Trello
Code Repo	GitHub
Backend	Supabase + Flask
Frontend	Flutter or React
Automations	n8n + GPT API + Twilio
Communication	WhatsApp / Discord
