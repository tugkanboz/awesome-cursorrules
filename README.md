# Test Automation .cursorrules Collection

This repository contains a curated collection of `.cursorrules` configurations for various test automation frameworks and tools. It aims to provide standardized AI assistance for test automation development using Cursor AI.

## Supported Frameworks and Tools
- Selenium (Java, Python, .NET)
- Cypress
- Playwright
- Appium
- RestAssured
- JMeter
- k6
- And more...

## Repository Structure
```
awesome-cursorrules/
├── selenium-java/
│   └── .cursorrules       # Selenium Java specific rules
├── cypress/
│   └── .cursorrules       # Cypress specific rules
├── playwright/
│   └── .cursorrules       # Playwright specific rules
└── ... other frameworks
```

## What is .cursorrules?

`.cursorrules` is a configuration file that acts as a bridge between developers and Cursor AI, enabling customized and context-aware code assistance. It allows teams to define project-specific instructions that guide how the AI understands and generates code for your project.

## Key Benefits

### 1. Intelligent Code Understanding
- Functions like a knowledgeable team member who understands your codebase
- Learns project-specific patterns and conventions
- Adapts to your unique development workflow

### 2. Code Style Enforcement
- Automatically aligns with defined coding standards
- Ensures consistency across generated code
- Reduces time spent on code formatting and style reviews

### 3. Project Context Awareness
- Maintains knowledge of your project's architecture
- Understands specific libraries and dependencies
- Considers project-specific constraints and requirements

### 4. Enhanced Productivity
- Generates more accurate code suggestions
- Reduces need for manual code adjustments
- Speeds up development workflow

### 5. Team Collaboration
- Serves as a single source of truth for AI interactions
- Ensures consistent code generation across team
- Maintains coding standards without manual enforcement

### 6. Custom AI Training
- Adapts AI behavior to project needs
- Provides project-specific recommendations
- Creates a personalized coding assistant

## Implementation Benefits

### For Individual Developers
- Personalized code suggestions
- Faster development cycles
- Reduced context switching

### For Teams
- Consistent coding practices
- Easier onboarding for new members
- Shared understanding of project standards

### For Projects
- Maintained code quality
- Documented best practices
- Scalable development process

## Best Practices for .cursorrules

### 1. Structure
- Keep rules organized and categorized
- Use clear, descriptive names
- Include examples where helpful

### 2. Maintenance
- Regular updates as project evolves
- Version control for rule changes
- Team review of major updates

### 3. Documentation
- Clear explanation of rules
- Examples of correct usage
- Common pitfalls to avoid

## Getting Started

1. Create a `.cursorrules` file in your project root
2. Define basic coding standards
3. Add project-specific requirements
4. Include common patterns and preferences
5. Share with team members
6. Iterate based on feedback

## Example Structure

```plaintext
project/
├── .cursorrules          # AI instruction file
├── src/                  # Source code
├── tests/                # Test files
└── README.md            # Project documentation
```

## Test Automation Use Cases

### 1. Framework Development
- Enforces consistent test structure across automation frameworks
- Maintains standard patterns for page objects, test cases, and utilities
- Ensures proper error handling and logging practices

### 2. Test Case Generation
```plaintext
# Example .cursorrules for test case generation
TEST CASE STRUCTURE:
- Use descriptive test method names (format: should_doSomething_when_condition)
- Include proper setup and teardown methods
- Implement proper wait strategies
- Add meaningful assertions
- Include test data management
```

### 3. Common Test Scenarios
```plaintext
# Login Test Example
SCENARIO: User Login
GIVEN: 
- Page Object pattern is used
- Explicit waits are implemented
- Test data is externalized
WHEN:
- Methods follow naming convention
- Proper assertions are used
THEN:
- Generate structured test case
```

### 4. Test Maintenance
- Suggests refactoring opportunities for test code
- Helps maintain consistent logging patterns
- Ensures proper exception handling
- Guides test data management

### 5. Cross-Browser Testing
```plaintext
# Browser Configuration Rules
BROWSER SETUP:
- Use WebDriverManager for setup
- Implement cross-browser support
- Handle browser-specific scenarios
- Include mobile responsiveness tests
```

### 6. API Testing Structure
```plaintext
# API Test Guidelines
API TESTS:
- Use proper request/response structures
- Implement schema validation
- Handle authentication properly
- Include status code verification
```

### 7. Performance Testing
```plaintext
# Performance Test Rules
PERFORMANCE:
- Define proper load patterns
- Include appropriate assertions
- Monitor system metrics
- Generate comprehensive reports
```

### 8. Real Example: Selenium Test Case
```java
// Generated based on .cursorrules
@Test
public void should_successfullyLogin_when_validCredentialsProvided() {
    // Structured according to rules
    loginPage
        .openLoginPage()
        .enterUsername(TEST_USER)
        .enterPassword(TEST_PASS)
        .clickLoginButton();
    
    // Assertions following rules
    Assert.assertTrue(
        "User should be redirected to dashboard",
        dashboardPage.isDashboardVisible()
    );
}
```

## How to Use This Collection

1. Choose your test automation framework/tool
2. Copy the corresponding `.cursorrules` file from this repository
3. Place it in your project's root directory
4. Start using Cursor AI for intelligent test automation assistance

### Example Usage with Selenium Java

1. Copy the `.cursorrules` from `selenium-java/` directory
2. Place it in your Selenium project root
3. Cursor AI will now understand:
   - Page Object Model patterns
   - Best practices for waits and assertions
   - Test organization standards
   - Reporting requirements
   
```bash
# Example project structure
my-selenium-project/
├── .cursorrules           # Copied from this repository
├── src/
│   ├── test/
│   │   ├── java/
│   │   └── resources/
│   └── main/
└── pom.xml
```

## Contributing

Feel free to contribute by:
1. Adding new framework configurations
2. Improving existing rules
3. Sharing best practices
4. Adding examples and documentation

## Conclusion

This collection of `.cursorrules` transforms Cursor AI into a specialized test automation assistant that understands and respects each framework's unique characteristics and best practices. By using these configurations, teams can ensure consistent, high-quality test automation code that aligns perfectly with industry standards and best practices.