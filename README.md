# Spacefree
Portal Central IG
git clone https://github.com/fullcalendar/fullcalendar-example-projects.git
cd fullcalendar-example-projects/react
npm install


# Smart Expense AI - iOS App

## Context
You are an expert iOS developer using Swift and SwiftUI. 
Build a modern, scalable, and intelligent expense tracking app that goes beyond basic functionality by integrating smart insights and automation.

## Objective
Create an iPhone app that works as an intelligent financial assistant, helping users track expenses, understand spending behavior, and improve financial habits.

---

## Technical Stack
- Language: Swift
- UI Framework: SwiftUI
- Architecture: MVVM (Model-View-ViewModel)
- Persistence: CoreData
- AI Logic: Local logic + optional API integration
- OCR: Apple Vision Framework
- Reactive: Combine (if needed)

---

## Core Features
- Add expense manually
- Add expense using voice input (basic placeholder)
- Scan receipts using camera (OCR)
- Automatically categorize expenses
- Store and retrieve expenses locally
- Edit and delete expenses

---

## Smart Features (IMPORTANT)
- Predict future expenses based on historical data
- Generate automatic insights:
  Example: "You spent 25% more on food this week"
- Budget alerts:
  Example: notify user when close to limit
- Basic financial assistant logic (rule-based)

---

## UI/UX Requirements
- Clean Apple-style interface
- Minimalist design
- Use NavigationStack
- Dashboard with:
  - Total expenses
  - Expense list
  - Basic chart (placeholder allowed)
- Smooth animations
- Color feedback:
  - Green = healthy spending
  - Yellow = warning
  - Red = over budget

---

## Architecture Rules
- Separate clearly:
  - Models
  - Views
  - ViewModels
  - Services
- Use ObservableObject and @Published
- Keep code modular and reusable

---

## Data Model
Create an Expense model with:
- id: UUID
- amount: Double
- category: String
- date: Date
- note: String?

---

## Services to Implement
1. ExpenseService
   - CRUD operations
2. CategorizationService
   - Categorize based on keywords
3. OCRService
   - Extract text from images using Vision
4. InsightsService
   - Generate spending insights
5. PredictionService
   - Estimate future expenses

---

## Views to Create
- DashboardView
- AddExpenseView
- ExpenseListView

---

## ViewModels
- ExpenseViewModel
- DashboardViewModel

---

## Tasks (Execution Order)
1. Create project structure
2. Implement Expense model
3. Build ExpenseViewModel
4. Create Dashboard UI
5. Add AddExpense screen
6. Implement persistence (CoreData)
7. Add categorization logic
8. Add OCR scanning
9. Add insights generation
10. Add prediction logic

---

## Coding Instructions
- Generate clean, readable Swift code
- Add comments explaining logic
- Follow best practices
- Avoid unnecessary complexity
- Ensure code is production-ready

---

## Goal
The result should feel like a real fintech-level app, not a basic demo.
Focus on clarity, intelligence, and user value.
