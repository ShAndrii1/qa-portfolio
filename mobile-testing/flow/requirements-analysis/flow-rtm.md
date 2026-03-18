# Requirements Traceability Matrix (RTM)

## Overview
This Requirements Traceability Matrix maps the documented product requirements of the **Flow** mobile application to the related test cases prepared and executed in **TestRail**.

The matrix was created to demonstrate requirement coverage, support traceability, and show how the tested functionality is linked to the designed test set.

### Global Coverage
- **Total covered test cases linked through RTM:** 216

---

## 1. Initial Access and First-Time Setup

| Requirement | Covered by Test Cases |
|---|---|
| Flow is a free, open-source expense tracker | C2102, C2105, C2108, C2115 |
| The application is working fully offline and running across platforms | C2300, C2301, C2302, C2335 |
| The application provides a list of supported languages, including Arabic, English, French, German, Italian, Mongolian, Russian, Spanish, Turkish, Ukrainian, and Czech | C2229, C2303, C2304, C2305, C2336 |
| The application should launch successfully on supported mobile devices | C2010, C2041, C2337 |
| The user should be able to access core functionality without requiring a constant internet connection | C2300, C2301, C2302 |
| On first launch, the application should provide usable initial access to the main product flow | C2010, C2016, C2023, C2028, C2041 |
| Core product functionality should remain available even before optional features are configured | C2028, C2321, C2285, C2297, C2298 |
| The application is expected to display usable localized content for supported languages available in the tested build | C2303, C2304 |
| Localization should remain understandable enough for core product use | C2304, C2305 |
| Language-related behavior should be validated for possible impact on date, amount, or number presentation where relevant | C2305 |

**Module coverage:** 34 linked test cases

---

## 2. Main Navigation and Core Screens

| Requirement | Covered by Test Cases |
|---|---|
| Flow is described as an expense tracker designed to help users efficiently track finances | C2067, C2068, C2071, C2164 |
| The product helps users reflect on their spendings | C2165, C2167, C2179, C2186 |
| The user should be able to navigate between major product areas required for core finance tracking | C2130, C2164, C2189, C2071 |
| Main screens should provide access to the primary user flows without blocking the user from using the application | C2041, C2071, C2130, C2164, C2189 |
| Core screen behavior should remain stable and understandable during normal use | C2308 |
| Displayed financial information on core screens should correspond meaningfully to the stored user data | C2067, C2068, C2069, C2070 |
| Changes in core data, such as newly added or updated transactions, should be reflected consistently in the relevant screens | C2070, C2128, C2129, C2186, C2187, C2188 |

**Module coverage:** 28 linked test cases

---

## 3. Transaction Management

| Requirement | Covered by Test Cases |
|---|---|
| Flow is described as an expense tracker | C2102, C2105, C2108 |
| The URI automation description shows that transactions may include fields such as title, amount, transaction date, category, tags, and account UUID | C2085, C2086, C2088, C2089, C2090, C2091, C2341 |
| The product supports adding one or more transactions through flow-mn schema URIs | C2338, C2339 |
| The product supports categories, supports tags and file attachments | C2090, C2312, C2201, C2089, C2206, C2207, C2092, C2258, C2260, C2263, C2264 |
| Flow can be supercharged with Eny, an AI-based receipt parser, and that a user can snap a photo of a receipt inside Flow and add it through that integration | C2259, C2340 |
| The product supports geo tagging, marked as optional | C2282, C2283, C2284, C2285 |
| The application should allow the user to create transactions through the main UI | C2071, C2072, C2073, C2074, C2102, C2105, C2108 |
| A transaction is expected to contain meaningful financial information such as amount and title, and where supported, date, category, tags, and account relation | C2085, C2086, C2088, C2089, C2090, C2091 |
| Saved transactions should remain available after the application is closed and reopened | C2116, C2117, C2306 |
| If transaction editing or deletion is available in the tested build, it should work consistently | C2118, C2119, C2120, C2121, C2122, C2123, C2124 |
| The user should be able to assign a category to a transaction where this functionality is available | C2090 |

**Module coverage:** 53 linked test cases

---

## 4. Accounts and Currencies

| Requirement | Covered by Test Cases |
|---|---|
| The product supports infinite accounts and currencies | C2142, C2143, C2145, C2343 |
| The product supports multiple currencies, including various cryptos | C2154, C2158, C2159, C2161, C2162, C2330, C2344 |
| The developer states that currencies are based on the account in URI automation and cannot be specified separately there at the moment | C2158, C2159, C2161, C2345 |
| The user should be able to create and use multiple accounts for finance tracking | C2142, C2143, C2145, C2110, C2111 |
| Since currencies are account-based, each account is expected to have an associated currency | C2142, C2143, C2145, C2110, C2111 |
| The application should allow the user to distinguish transactions belonging to different accounts | C2091, C2161, C2162, C2163 |
| The user should be able to work with accounts that use different currencies | C2161, C2162, C2163, C2330 |
| Currency-related information should be presented clearly enough for the user to understand which currency is used in a given account or transaction context | C2160, C2161, C2162 |
| If multi-currency behavior affects calculations, balances, or statistics, this behavior should be validated during testing | C2330, C2346 |

**Module coverage:** 38 linked test cases

---

## 5. Statistics and Spending Overview

| Requirement | Covered by Test Cases |
|---|---|
| The product helps users reflect on their spendings | C2165, C2167, C2179 |
| The application is expected to provide some form of spending overview, summary, or statistics based on recorded data | C2165, C2167, C2179 |
| Displayed financial insights should correspond in a meaningful way to the transactions stored in the application | C2185, C2186, C2187, C2188 |
| If the application includes charts, summaries, or grouped spending views, they should update consistently after relevant transaction changes | C2165, C2179, C2186, C2187, C2188 |
| If category-related behavior affects reporting or grouped views, this behavior should remain consistent with the stored transaction data | C2174, C2175, C2185 |
| If currency differences affect summaries or analytics, the application should present this behavior clearly enough for the user to understand the result | C2347 |

**Module coverage:** 19 linked test cases

---

## 6. Profile and Settings

| Requirement | Covered by Test Cases |
|---|---|
| The product gives full control over user data | C2217, C2218, C2219, C2220, C2221, C2223, C2224 |
| The product supports fully recoverable backups in ZIP and JSON formats | C2219, C2220, C2348, C2349 |
| The product supports periodic auto-backups to iCloud | C2350 |
| The product supports CSV and PDF export | C2218, C2221 |
| The application is expected to behave as a privacy-focused finance tool from the user’s perspective | C2044, C2045, C2046, C2246, C2247 |
| Core product use should not depend on unnecessary external accounts or tracking infrastructure | C2300, C2301, C2302 |
| The user should be able to manage and preserve personal data through the product’s available backup and export capabilities | C2217, C2218, C2219, C2220, C2221, C2222 |
| The user should be able to create backup data in the supported format(s) available in the tested build | C2218, C2219, C2220, C2221 |
| If restore functionality is available, backed-up financial records should be recoverable in a meaningful and usable form | C2351 |
| Backup-related behavior should support preservation of user data and should be validated through observable results during testing | C2222, C2332 |

**Module coverage:** 35 linked test cases

---

## 7. Optional / Advanced Features

| Requirement | Covered by Test Cases |
|---|---|
| The application is described as fully offline | C2300, C2301, C2302 |
| Core product functionality should remain usable without internet access | C2300, C2301, C2302 |
| The user should be able to access existing financial data and record core transaction information offline | C2300, C2301 |
| Optional online-dependent features, if any, should not prevent the user from using the core expense-tracking functionality | C2302 |

**Module coverage:** 9 linked test cases

---

## Coverage Notes
- The RTM reflects practical coverage based on the created and executed manual test set in TestRail.
- Some test cases support more than one requirement because a single user flow may validate multiple aspects of product behavior.
- Requirement coverage includes both core feature validation and selected supporting/advanced feature checks.
- URI-based automation coverage was expanded through additional test cases validated using documented `flow-mn` deep links on Android.

---

## Final Traceability Summary
The RTM demonstrates that the main product requirements for **Flow** were mapped to the available manual test coverage across the following areas:

- Initial access and usability
- Core navigation and finance-tracking flows
- Transaction creation and management
- Accounts and currencies
- Statistics and financial overview
- Backup, restore, export, and settings
- Offline behavior and selected advanced features

This matrix supports the overall testing scope and provides traceability between documented requirements and the executed test design.
