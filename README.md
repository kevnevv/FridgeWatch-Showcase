# 🧊 FridgeWatch — Intelligent Inventory & AI Culinary Assistant

[![Mobile: Flutter](https://img.shields.io/badge/Mobile-Flutter%20%7C%20Dart-02569B.svg)](#features)
[![Backend: Supabase](https://img.shields.io/badge/Backend-Supabase%20%7C%20PostgreSQL-3ECF8E.svg)](#architecture)
[![Vision AI: Gemini](https://img.shields.io/badge/Vision%20AI-Google%20Gemini%20Flash-4285F4.svg)](#features)
[![Status: Showcase Only](https://img.shields.io/badge/Repository-Showcase%20%28No%20Code%29-lightgrey.svg)](#overview)

> **FridgeWatch** is a cross-platform pantry management and meal recommendation application. By pairing camera-based computer vision with zero-waste culinary recommendations, FridgeWatch tracks food freshness, monitors expiration dates, and synthesizes step-by-step recipes from ingredients already in your kitchen.

---

## 📱 App Highlights

* **Instant Fridge & Pantry Audits**: Capture a photo of your fridge or pantry shelf to detect ingredients, condiments, produce, and dairy automatically.
* **Deterministic Freshness & Expiry Tracking**: Extracts items into structured JSON with estimated shelf lives, notifying users before items spoil.
* **Zero-Waste Recipe Generator**: Synthesizes custom recipes prioritizing items expiring soonest to cut kitchen food waste.
* **Offline-Ready Pantry Sync**: Powered by a local-first cache with cloud synchronization via Supabase.

---

## 🛠️ Technical Stack & Architecture

* **Client**: Cross-platform mobile client built with **Flutter / Dart** for native iOS and Android performance.
* **AI & Vision Pipeline**: Multi-modal vision analysis using **Google Gemini Flash** with strict JSON schema parsing and ingredient normalization.
* **Database & Auth**: **Supabase (PostgreSQL)** with Row-Level Security (RLS) for user authentication and inventory storage.
* **State Management**: Reactive state management handling offline caching and real-time inventory updates.

---

## 🔒 Source Code Notice

> **Notice**: This repository is a **public showcase and architectural summary**. The core source code is maintained in a private repository for personal use.  
> Demos and technical walkthroughs are available upon request for interview purposes.
