QE Domain Lead Interview Exercise: The Calculator App Refactor
===

### Introduction
You are joining the "Core Utilities" domain as a QE Domain Lead. Your first major initiative is overseeing the complete refactor of our worldwide popular **[worldwide popular calculator app](https://apps.apple.com/app/calculator/id1069511488) for iOS devices**. This app has millions of daily active users who rely on it for everything from splitting bills to complex field engineering calculations.

The engineering team is moving to a **Continuous Delivery** model (releasing weekly). Historically, the team relied on manual regression testing at the end of sprints. Your goal is to transition the team to **Modern Quality Engineering practices**, embedding quality ownership within the development squad and implementing a Shift-Left approach.

### Product Requirements (The "Scope")
The Product Manager has outlined the MVP for the refactored app.
- **Platform**: iOS 16+ (SwiftUI codebase).
- **Core Functions**: Add, Subtract, Multiply, Divide (supporting decimals, negative numbers, and percentages).
- **Memory Logic**: "Clear Entry" (CE) clears the current input; "All Clear" (AC) resets the full state.
- **Accessibility**: Must be fully VoiceOver compatible (WCAG AA standard).
- **Performance**: App launch time must be under 0.8 seconds.

### The Challenge
We are **not** looking for a list of 100 manual test cases. We want to understand how you think, how you strategize, and how you enable the team to build high-quality software efficiently.

### Deliverables
Please prepare a document or presentation covering the following three sections. We expect you to spend no more than **3-4** hours on this.

## Part 1: The Shift-Left Strategy (Prevention over Detection)
- **Requirement Review**: Review the requirement: *"The app allows users to clear the current entry and preserve the memory."* As a QE Lead involved in the design phase, what questions would you ask the Product Manager and Developers to clarify ambiguity and prevent bugs before a line of code is written?
- **Developer Enablement**: How would you guide the developers to test their own code? Define a **Testing Pyramid** specifically for this Calculator app. What types of tests belongs in Unit vs. Integration vs. UI? Give concrete examples of what logic should be tested at which layer.

## Part 2: The Quality Pipeline (Process & Automation)
- **CI/CD Integration**: Sketch or describe a high-level CI/CD pipeline for this app. Where do your automated tests run? What are your "Quality Gates"?
- **Release Confidence**: Since we are moving away from full manual regression, what signals (metrics, test results, observability) would you need to see to give a "Go" for a release?

## Part 3: Critical Scenarios & BDD
- **Risk-Based Scenarios**: Identify the top 3-5 "High Risk" areas for a calculator app (areas where a bug would be catastrophic to user trust).
- **BDD Examples**: Select one complex flow (e.g., Mixing operators with clear entry logic) and write it in Gherkin (Given/When/Then) format. Ensure this is written in a way that could be used as a "Living Documentation" or an executable specification.

### Notes / Tips
- **Think Accessibility**: How does your strategy ensure a blind user can calculate a tip correctly?
- **Think Architecture**: Why is UI automation often considered "flaky," and how will your strategy mitigate that for a calculator?
- **Tools**: Feel free to mention specific tools (e.g., XCTest, Maestro, Appium, Fastlane) you would recommend to the team.

## Important Note on AI Tools
- While we embrace AI tools for productivity in our daily work, for this assessment we ask that you complete the work without using AI tools to generate solutions. This helps us evaluate your foundational skills and problem-solving approach. Limited reference use is acceptable, but please note any AI assistance you do utilize.
- Submissions that appear to be primarily AI-generated may result in disqualification. We appreciate your understanding as we strive to make the assessment process fair and effective.
