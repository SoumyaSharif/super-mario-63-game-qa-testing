
# Game QA Testing Portfolio

A practical portfolio documenting my learning and experience in Game Quality Assurance, including manual testing, test case design, exploratory testing, bug reporting, and QA documentation.

## About This Repository

This repository contains my practical Game QA projects and learning notes. The objective is to understand how games are tested, identify unexpected behaviour, document defects, and follow structured quality assurance practices.

I am building this portfolio to develop the skills required for an entry-level Game QA Tester role.

## Project 1: Super Mario 63 – Manual Game Testing

**Game:** Super Mario 63  
**Version:** 1.6 (63)  
**Platform:** PC / Browser  
**Operating System:** Windows 11  
**Testing Approach:** Manual Testing

### Testing Scope

The project covers the following areas:

- Player movement and controls
- Collision detection and terrain interaction
- Enemy behaviour and interactions
- Screen boundaries
- Level progression
- Pause menu and UI elements
- Graphics quality settings
- Audio settings
- Save slots and progression observations

### Project Deliverables

- Manual test cases
- Detailed bug reports
- Bug tracking sheet
- Game QA master checklist
- Test execution summary
- Gameplay screenshots and evidence

### Key Findings

Issues and observations documented during testing include:

- Player moving beyond the visible screen boundary.
- Player vibration and falling near certain terrain edges.
- Multiple enemies visually overlapping.
- Enemies respawning when revisiting completed sections.
- Overlapping and unclear elements in the pause menu.

Findings that require confirmation of intended game behaviour are marked for further investigation rather than being treated as confirmed defects.

## Bug Reporting Template

The following is the structured bug-reporting format I use to document and investigate defects.

### Bug Report Format

| Field | Description |
|---|---|
| Bug ID | Unique identifier for the reported issue |
| Bug Title | Short and specific description of the defect |
| Feature Affected | Gameplay feature or system where the issue occurs |
| Environment | Game version, operating system, browser and platform |
| Preconditions | Conditions required before reproducing the issue |
| Steps to Reproduce | Exact steps required to trigger the defect |
| Expected Result | Behaviour expected from the game |
| Actual Result | Behaviour actually observed |
| Severity | Critical / Major / Minor / Trivial |
| Priority | High / Medium / Low |
| Reproduction Consistency | Number of attempts and how frequently the issue occurs |
| Evidence | Relevant screenshot or video recording |

### Bug Reporting Guidelines

- Reproduce unexpected behaviour before reporting it.
- Attempt reproduction multiple times and record the results.
- Write clear, numbered reproduction steps.
- Describe expected and actual results separately.
- Include screenshots or recordings wherever possible.
- Distinguish severity (impact of the defect) from priority (urgency of fixing it).
- Record the game build and testing environment.
- Do not report assumptions as confirmed defects.
- If no confirmed defect is found, document the observation accordingly.

## QA Checklist Template

I use a modular checklist approach to ensure that important areas of a game are not overlooked.

### Checklist Structure

| Field | Description |
|---|---|
| Checklist ID | Unique identifier for the check |
| Category | Testing area or game feature |
| Test Item | Specific behaviour or functionality to verify |
| Priority | Critical / Major / Minor |
| Result | Pass / Fail / Blocked / N/A / Not Tested |
| Bug ID | Linked bug report, if applicable |
| Build Version | Game version being tested |
| Environment | Device, operating system and browser |
| Evidence | Screenshot or video reference |
| Comments | Additional observations or notes |

### Testing Checklist Categories

1. Installation and Launch
2. Core Gameplay and Mechanics
3. Level Design and Progression
4. Enemy AI and Physics
5. Graphics and Animation
6. Audio
7. UI and UX
8. Save Data and Settings
9. Compatibility and Input
10. Performance and Stability
11. Accessibility and Localization

### Checklist Guidelines

- Keep checklist sections modular and relevant to the game.
- Prioritize testing based on risk and gameplay impact.
- Link failed checks to their corresponding bug IDs.
- Record the build version and testing environment.
- Attach evidence and comments where necessary.
- Track tested and untested areas separately.
- Retest defects after fixes and record regression results.
- Update the checklist as new features and issues are discovered.

## Game QA Theory and Learning

This repository will also contain notes and practical exercises covering:

- Fundamentals of Game QA
- QA vs QC
- Types of Software Testing
- Functional and Non-Functional Testing
- Smoke, Sanity and Regression Testing
- Exploratory Testing
- Test Case Design Techniques
- Bug Life Cycle
- Severity vs Priority
- Game-Specific Testing
- Agile Methodology and QA Workflows
- Industry Tools and Practices

## Skills Being Developed

- Manual Game Testing
- Test Case Design
- Bug Identification and Reporting
- Exploratory Testing
- Test Execution
- Bug Tracking
- QA Documentation
- Analytical Thinking
- Attention to Detail

## Future Projects

- Manual testing projects across different game genres.
- Advanced gameplay and system testing.
- More detailed test documentation.
- Practical exercises based on professional QA workflows.
- Learning and applying industry tools.

## Objective

To develop practical Game QA skills, understand professional testing workflows, and build the foundation required to work as a Game QA Tester in the gaming industry.

## References

The following resource helped inform the structure and organization of my Game QA testing checklist.

1. **Snoop Game – How to Create a Game Testing Checklist for Indie Developers**

   [Read the article](https://snoopgame.com/blog/how-to-create-a-game-testing-checklist-for-indie-developers/)

   Used as a reference for:

   - Modular checklist organization.
   - Categorizing different game-testing areas.
   - Tracking Pass, Fail, Blocked and Not Tested results.
   - Prioritizing test items.
   - Linking failed checks to bug reports.
   - Maintaining and updating test coverage.

The checklist used in this portfolio is adapted to the scope of the Super Mario 63 testing project.

---

**Created by:** Soumya Sharif  
**Focus:** Game Quality Assurance | Manual Testing | Gaming Industry
