## Understanding Software Construction and Collaboration  
**Group Assignment – End of Week 2 (Theory-Based)**

### 1. Difference between programming and software construction (with one real-world example)
**Programming** focuses on translating logic into a programming language through the act of writing code to solve a specific problem or to implement an algorithm to solve a hypothesis.
**Software Construction** is a much broader engineering concept that integrates programming plus other activities needed to build a working software system such as designing mocules, writing tests, debugging the code, integrating different components, managing the code quality and ensure that the code is maintainable.
*Real-world example: Building an E-commerce Shopping Cart*
**Programming perspective** A programmer writes a function to calculate the total price of items in a buyer's cart.
**Software Construction perspective** A software engineer building the above same feature will have to consider;
1. Error handling: What should happen if an item has an unvailable quantity of an invalid price.
2. Testing: Writing standard tests to verify that the calculation works with cases like an empty cart, discounts.
3. Integration: How this particular code connects to the database, payment gateway
4. Performance: How will it perform when the cart has 100+ items?
5. Maintainability: Using clear naming, adding documentation, following team coding standards
6. Extensibility: Ensuring that the code can be maintained for example adding dynamic pricing later.

### 2. Situation where poor maintainability could cause serious problems
**Poor maintainability occurs when code is hard to understand, change, or fix due to messy structure, lack of documentation, or 
accumulated technical debt making updates, fixes, or scaling difficult and unreliable.

**Example:** The biometric voter verification system (BVVKs) used in the 2026 general elections.
Due to neglected maintenance and poor software upkeep, many devices failed on election day (January 15, 2026), rejecting fingerprints and refusing to start. This forced polling stations to revert to manual registers, causing long delays, reduced voter turnout, widespread frustration, and serious questions about electoral integrity.
Better maintainability — through regular updates, thorough testing, and cleaner code — could have prevented these widespread failures and preserved trust in the voting process.

### 3. Why version control is critical in team-based software development.
Version control on GitHub tracks changes made to code over time, allowing developers to return to older versions and work together safely, which helps prevent mistakes and makes teamwork easier.
In our group of five working on a project, we use GitHub as our version control platform, and under it we use Git, which is the actual version control system. Git is responsible for tracking changes, saving versions, and managing the project history. Through GitHub, we use tools like commits to save our work, branches to work on different features separately, and merges to combine our work into the main project. This setup allows everyone to work in an organised way, avoid conflicts, and return to earlier versions if mistakes happen.

### 4. How code reviews improve both software quality and developer skills.
Code reviews improve software quality by allowing team members to examine each other’s code before it is merged into the main project. On platforms like GitHub, this is usually done through pull requests, where changes are reviewed before approval. During the review process, team members can spot bugs, logical errors, security issues, or inefficient code early, reducing the chance of serious problems later. Code reviews also help ensure that agreed coding standards and project requirements are followed consistently across the team.

Code reviews also support developer learning and skill improvement. Through comments and feedback on pull requests, developers learn better ways to structure code, write clearer logic, and follow best practices. Reviewing others’ pull requests helps team members understand different approaches to solving problems and improves their ability to read and evaluate code. The approval process on GitHub encourages collaboration and accountability, ensuring that code is not merged without review. Over time, this leads to improved teamwork, stronger coding skills, and higher-quality software.

### 5. How AI can help in understanding code without replacing learning
Explains complex code clearly – Breaks down difficult logic step by step and translates jargon into plain language.

Supports smarter debugging – Helps users understand why errors occur, not just how to fix them.

Uses helpful analogies – Connects abstract concepts to real-world examples for better understanding.

Acts as a learning assistant, not a shortcut – Encourages writing your own code first, then reviewing with AI feedback.

Improves code quality – Suggests optimizations, best practices, and alternative approaches.

Saves time on syntax – Reduces frustration so learners focus on problem-solving and design thinking.

Builds deeper understanding – Strengthens intuition and reasoning instead of promoting copy-paste habits.

Takeaway: AI accelerates learning and understanding—but real mastery still comes from active practice, debugging, and thinking through problems. AI should be used as a study partner or guide, not as a shortcut. When used responsibly, it supports learning rather than weakening it.

**Submitted by:** 
- Rebecca Alinda
- Anna Akumu
- Oscar Odongkara
- Namaganda Precious Wakabi
- Mukama Joseph
  
**Date:** February 2026
