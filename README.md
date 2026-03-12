# Manual QA Testing – Sauce Demo E-Commerce

Manual testing project for a demo e-commerce website (saucedemo.com).

## Scope
- Login functionality
- Inventory (product browsing, sorting, add to cart)
- Checkout flow

## Contents

| File | Description |
|------|-------------|
| `TestPlan.md` | Testing strategy and scope |
| `TestCases.xlsx` | Full test case suite with pass/fail results |
| `BugReports.md` | Bugs identified during testing |

## Bugs Found

| Bug ID | Summary | Severity |
|--------|---------|----------|
| BUG-001 | Checkout allowed with empty cart | High |
| BUG-002 | Zip code field accepts non-numeric characters | Medium |

## Test Coverage
Total test cases executed: 15  
- Passed: 13  
- Failed: 2

## Environment
- Browser: Chrome (latest)
- OS: Windows 11
- Test site: https://www.saucedemo.com