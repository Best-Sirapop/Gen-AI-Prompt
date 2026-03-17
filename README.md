# Gen-AI-Prompt: Product Classifier System

This repository contains standardized prompts and configuration files used to classify e-commerce products into specific **L4 Categories** using Generative AI.

## 📌 Project Overview
The goal of this system is to ingest raw product names and accurately map them to a predefined taxonomy. This ensures consistency across different platforms.

---

## 📂 Repository Structure

The project is divided by business category to handle specific regulatory and naming nuances:

* **`/beauty-personal-care`**: Logic for Skin Care, Hair Care, Makeup, Fragrance, Oral Care, Skin Cleansing, Deodorants, Personal Care Appliance.
* **`/vitamins-supplements`**: Logic for Health, Vitamins, and Dietary Supplements.
* **`/home-office`**: Logic for laundry and cleaning agents

---

## ⚖️ Compliance & Constraints
* **Beauty**: Focus on sensory attributes and application areas.
* **Vitamins**: Strict adherence to non-medicinal claims; classification must not imply "cures" or "treatments" unless specified in the L4 logic.
---

**Last Updated:** February 2026
