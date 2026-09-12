# War Thunder — Manual QA Test Plan

**Status:** Prepared for execution

## Objective
Demonstrate structured manual game testing on a live PC title using reproducible test cases, checklists, exploratory testing, and truthful defect reporting.

## Test Environment
- Windows PC
- AMD Ryzen 7 7800X3D
- PNY GeForce RTX 5070 Ti
- 32 GB DDR5 6000 MHz
- ASUS B650E-I

## Scope
- Launch and login flow
- Main menu navigation
- Graphics settings
- Display modes and resolution
- Audio settings
- Control settings and key rebinding
- Settings persistence after restart
- Alt+Tab behavior
- Entering and leaving a battle
- Basic battle HUD behavior
- Post-battle flow
- Non-standard user actions around menus/settings

## Out of Scope
- Server-side load testing
- Anti-cheat validation
- Source-code testing
- Console/mobile platforms
- Internal Gaijin tools

## Test Types
- Smoke testing
- Functional testing
- Exploratory testing
- Regression-style rechecks

## Entry Criteria
- Game installed and updated
- Stable internet connection
- Test account available
- Build/version recorded before execution

## Exit Criteria
- Planned smoke checks executed
- Core test cases executed
- Failed tests documented
- Real defects, if found, documented with evidence
- Short final test report prepared

## Reporting Rule
No defect is reported as confirmed unless it is actually observed and reproducible in the test environment.
