# Product Search Test Cases

## Module: Product Search

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result |
|---------------|---------------|------------|-----------|-----------------|
| TC-021 | Search using a valid product name | Enter a valid product name and click Search | Laptop | Matching products are displayed. |
| TC-022 | Search using an invalid product name | Enter a product name that does not exist | ABCXYZ | "No products found" message is displayed. |
| TC-023 | Search using a partial product name | Enter part of a product name | Lap | Relevant matching products are displayed. |
| TC-024 | Search is case insensitive | Search using uppercase and lowercase letters | laptop / LAPTOP | Same search results are displayed. |
| TC-025 | Search with special characters | Enter special characters in the search box | @#$% | Appropriate validation or no results displayed. |
| TC-026 | Search with empty input | Click Search without entering any text | Blank | User is prompted to enter a search term or all products are displayed. |
| TC-027 | Verify search suggestions | Type the first few letters of a product | Sam | Search suggestions appear. |
| TC-028 | Search using product category | Select a category and search | Electronics | Products from the selected category are displayed. |
| TC-029 | Verify search after applying filters | Apply filters and search | Brand: Dell | Results match the applied filters. |
| TC-030 | Verify product details from search results | Click a product from the results | Laptop | Product Details page opens successfully. |
