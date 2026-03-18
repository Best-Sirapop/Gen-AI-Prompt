# Gen-AI-Prompt: Product Classifier System

This repository contains standardized prompts and configuration files used to classify e-commerce products into specific **L4 Categories** using Generative AI.

## 📌 Project Overview
The goal of this system is to ingest raw product names and accurately map them to a predefined taxonomy. This ensures consistency across different platforms.

---

## 📂 Repository Structure
The project is organized by business category to account for category-specific logic, regulatory requirements, and naming conventions:

* **`/beauty-personal-care`** Covers Skin Care, Hair Care, Makeup, Fragrance, Oral Care, Skin Cleansing, Deodorants, and Personal Care Appliances.
Focuses on product attributes such as texture, scent, and application areas.

* **`/vitamins-supplements`**: Covers Health, Vitamins, and Dietary Supplements.
Emphasizes strict compliance with regulatory guidelines for health-related claims.

* **`/home-office`**: Covers Laundry and Cleaning Agents, as well as Home & Office maintenance products.
Focuses on functional attributes such as usage purpose, surface compatibility, and cleaning performance.
---

## ⚖️ Compliance & Constraints
* **Beauty**: Focus on sensory attributes and application areas.
* **Vitamins**: Strict adherence to non-medicinal claims; classification must not imply "cures" or "treatments" unless specified in the L4 logic.
* Home&Office**: Focus on functional and usage-based classification (e.g., cleaning type, surface, or environment).
---

**Last Updated:** March 2026
