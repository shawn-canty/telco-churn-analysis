# Telco Customer Churn: Behavioral Segmentation & Retention Strategy

**Role:** Lead Data Analyst

## 1. Business Problem & Context

Facing a spike in month-to-month subscription cancellations, the marketing team needs data-driven guidance to optimize a limited retention budget. They require clarity on which customer segments to target and which retention offers (e.g., tech support, discounts) will effectively alter behavior.

## 2. Project Objective

To identify the behavioral trends, service combinations, and account characteristics most highly correlated with customer churn.

## 3. Validation Criteria

* **High-Risk Cohort Isolation:** Identify customer segments whose churn rates exceed the company baseline, proving they are the primary source of revenue leakage.
* **Strategic Actionability:** Tie insights to controllable business variables (e.g., service add-ons, contract terms, billing methods) instead of static demographics, providing marketing with actionable levers to alter behavior.

## 4. Methodological Scope & Controls

* **Methodology:** Exploratory and cohort-based analysis of customer service choices, contract terms, and billing preferences.
* **Key Variables:** Contract Types (Month-to-Month, 1-2 Year), Service Add-ons (Tech Support, Online Security, Fiber/DSL), Billing/Payment Types, and Age (Senior Status).
* **Out of Scope:** Excludes financial revenue forecasting and entertainment add-on analysis to focus strictly on core behavioral retention drivers.
* **Expected Deliverables:** An Interactive Excel Dashboard for dynamic cohort filtering, and an Executive Summary delivering high-ROI business recommendations targeting vulnerable segments.

---

## Executive Summary: Telco Retention Strategy

### Strategic Recommendation

Target the retention budget exclusively at the high-risk month-to-month segment.
**Action:** Offer customers a feature bundle including Free Tech Support and Online Security to encourage switching to 1- or 2-Year contracts. Customers must sign up for Auto-Pay to get this offer. This campaign reduces contract risk, increases customer retention, and removes payment issues that cause most cancellations.

### Key Findings

* The overall churn rate for the organization is 26.5%.
* **M2M High-Risk Churn:** Customers on month-to-month contracts without tech support cancel at a rate of 50.4%, representing 1,350 lost accounts.
* **Independent Compounding Risk:** In this group of month-to-month customers, churn increases even more when any of the following conditions are present:
  * **Billing Type:** Customers who pay by electronic check have a churn rate of 58.4%.
  * **Internet Type:** Customers using fiber optic service have a churn rate of 57.5%.
  * **No Online Security:** Customers without the Online Security add-on have a 54.7% churn rate.
