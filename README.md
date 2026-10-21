# 🧊 FridgeWatch — Intelligent Inventory & AI Culinary Assistant

<div align="center">
  <img src="screenshots/app_logo.png" alt="FridgeWatch Logo" width="100" />
  <h3>Zero-Waste Kitchen Intelligence & Personalized Meal Recommendations</h3>

  [![Mobile: Flutter](https://img.shields.io/badge/Mobile-Flutter%20%7C%20Dart-02569B.svg)](#features)
  [![Backend: Supabase](https://img.shields.io/badge/Backend-Supabase%20%7C%20PostgreSQL-3ECF8E.svg)](#technical-stack--architecture)
  [![Vision AI: Gemini](https://img.shields.io/badge/Vision%20AI-Google%20Gemini%20Flash-4285F4.svg)](#features)
  [![Nutrition: USDA FoodData](https://img.shields.io/badge/Nutrition-USDA%20FoodData%20Central-green.svg)](#features)
  [![Status: Showcase Only](https://img.shields.io/badge/Repository-Showcase%20%28No%20Code%29-lightgrey.svg)](#source-code-notice)
</div>

---

> **FridgeWatch** is a cross-platform pantry management and AI culinary assistant application. By pairing computer vision with zero-waste culinary intelligence, FridgeWatch tracks food freshness, monitors expiration dates across custom kitchen locations, and synthesizes step-by-step recipes from ingredients already in your kitchen.

---

## 📱 Visual Feature Showcase

### 1. Smart Inventory & Expiry Tracking
Track items across custom kitchen storage zones (**Fridge**, **Freezer**, **Pantry**) with deterministic shelf-life calculation, category color tagging, and color-coded expiration indicators (Urgent, Soon, Good).

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <img src="screenshots/01_inventory_home.png" alt="Pantry & Fridge Inventory Home View" width="280" /><br />
        <b>Inventory Home Screen</b><br />
        <i>Real-time freshness counters, category badges, and quick location switching</i>
      </td>
      <td align="center" width="50%">
        <img src="screenshots/02_inventory_pantry_view.png" alt="Pantry Category View" width="280" /><br />
        <b>Pantry & Dry Storage View</b><br />
        <i>Multi-location inventory tracking with item quantities and shelf life</i>
      </td>
    </tr>
  </table>
</div>

---

### 2. AI Sous-Chef & Zero-Waste Meal Planning
Powered by **Google Gemini Flash**, the in-app culinary assistant analyzes your current stock, identifies ingredients nearing expiration, suggests recipes to prevent waste, and executes natural-language pantry commands (e.g. *"I ate a kiwi"*, *"Add 2 avocados with 4 days shelf life"*).

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <img src="screenshots/03_ai_culinary_assistant.png" alt="AI Culinary Assistant" width="280" /><br />
        <b>AI Culinary Assistant Chat</b><br />
        <i>Conversational recipe creation, meal planning, and dynamic culinary suggestions</i>
      </td>
      <td align="center" width="50%">
        <img src="screenshots/04_ai_assistant_audit.png" alt="Pantry Audit & Recommendations" width="280" /><br />
        <b>Intelligent Kitchen Audit</b><br />
        <i>Automated expiry review, multi-location disambiguation, and meal prioritization</i>
      </td>
    </tr>
  </table>
</div>

---

### 3. USDA Nutrition Analytics & Consumption History
Integrates an offline laboratory reference database of **480+ USDA FoodData Central** staple foods. Calculates daily and weekly calorie totals, macronutrient splits (Protein, Carbs, Fats, Fiber), and allows users to shift logged dates or recalibrate metrics in real time.

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <img src="screenshots/05_usda_nutrition_analytics.png" alt="Nutrition Analytics" width="280" /><br />
        <b>USDA Nutritional Breakdown</b><br />
        <i>Weekly consumption progress, macronutrient distribution bars, and logged meals</i>
      </td>
      <td align="center" width="50%">
        <img src="screenshots/06_daily_intake_filter.png" alt="Daily Intake Filters" width="280" /><br />
        <b>Granular Day Filtering</b><br />
        <i>Dynamic day chips (Today, Yesterday, Custom) with one-tap date shifting</i>
      </td>
    </tr>
  </table>
</div>

---

### 4. Item Details, Restocking & Grocery Management
Tap any food card to view full nutrition data, adjust shelf life, change storage locations, or set reminders. When consuming food, a smart confirmation dialog offers instant restoration back to stock or additions to your shopping list.

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="screenshots/07_item_details_editor.png" alt="Item Details Editor" width="260" /><br />
        <b>Shelf Life & Item Editor</b><br />
        <i>Edit quantity, location, expiration date, and reminder intervals</i>
      </td>
      <td align="center" width="33%">
        <img src="screenshots/08_consumption_restock_dialog.png" alt="Smart Consumption Dialog" width="260" /><br />
        <b>Smart Consumption Dialog</b><br />
        <i>Cross-off verification with optional inventory restoration</i>
      </td>
      <td align="center" width="33%">
        <img src="screenshots/10_smart_shopping_list.png" alt="Smart Shopping List" width="260" /><br />
        <b>Integrated Shopping List</b><br />
        <i>Cross off purchased groceries and sync directly into pantry stock</i>
      </td>
    </tr>
  </table>
</div>

---

### 5. Zero-Waste Challenges & Household Milestones
Stay motivated to cut household food waste through goal-oriented challenges, waste-reduction streaks, and milestone achievements.

<div align="center">
  <img src="screenshots/11_zero_waste_challenges.png" alt="Zero-Waste Challenges" width="300" /><br />
  <b>Zero-Waste Challenges & Streaks</b><br />
  <i>Track waste reduction goals, active streaks, and food-saving achievements</i>
</div>

---

### 6. Power-User Workflows & Local Intent Routing
Designed for speed with local short-circuit intent routing (0 LLM tokens, <50ms response for inventory queries), instant undo capabilities, customizable quick prompts, and background push reminders.

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="screenshots/09_navigation_drawer.png" alt="Navigation Drawer" width="260" /><br />
        <b>Modular Navigation</b><br />
        <i>Quick access to scanner, calendar, assistant, and settings</i>
      </td>
      <td align="center" width="33%">
        <img src="screenshots/13_custom_ai_prompts.png" alt="Custom AI Prompts" width="260" /><br />
        <b>Custom AI Prompts</b><br />
        <i>Create personalized one-tap prompts for common culinary routines</i>
      </td>
      <td align="center" width="33%">
        <img src="screenshots/14_instant_zero_token_undo.png" alt="Instant Zero-Token Undo" width="260" /><br />
        <b>Zero-Token Local Undo</b><br />
        <i>Instant in-memory reversal stack with non-blocking feedback</i>
      </td>
    </tr>
  </table>
</div>

---

## 🛠️ Technical Stack & Architecture

* **Client**: Cross-platform mobile client built with **Flutter / Dart** for high-framerate iOS and Android performance.
* **AI & Vision Pipeline**: Multi-modal vision analysis using **Google Gemini Flash** with strict JSON schema parsing, preset enrichment, and prompt compression (~65% token reduction).
* **Local-First Routing Engine**: Tier 0 pre-LLM regex short-circuiting routing frequent pantry queries locally in 0ms and 0 tokens.
* **Nutrition Database**: Offline registry of **480+ USDA FoodData Central** items with dynamic macronutrient scaling.
* **Backend & Auth**: **Supabase (PostgreSQL)** with Row-Level Security (RLS) for cloud synchronization, multi-device backup, and inventory data storage.
* **Offline Cache**: Local SQLite / Shared Preferences cache ensuring 100% offline functionality.

---

## 🔒 Source Code Notice

> **Notice**: This repository is a **public showcase and architectural summary**. The core source code is maintained in a private repository for personal use.  
> Demos and technical walkthroughs are available upon request for interview purposes.
