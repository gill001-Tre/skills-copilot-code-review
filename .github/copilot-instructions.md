# GitHub Copilot Instructions

## Repository Guidelines

This repository contains the Mergington High School Activities web application, a platform for managing extracurricular activities and student registrations.

## Code Review Standards

When reviewing code in this repository, please focus on:

### Security

- Validate input sanitization practices.
- Search for risks that might expose user data.
- Prefer loading configuration and content from the database instead of hard coded content. If absolutely necessary, load it from environment variables or a non-committed config file.

### Code Quality

- Use consistent naming conventions.
- Try to reduce code duplication.
- Prefer maintainability and readability over optimization.
- If a method is used a lot, try to optimize it for performance.
- Prefer explicit error handling over silent failures.

### Performance
- Look for unnecessary database queries
- Check for potential memory leaks
- Verify efficient DOM manipulation
- Ensure proper resource cleanup

### Accessibility
- Verify ARIA labels are present
- Check color contrast ratios
- Ensure keyboard navigation works
- Validate semantic HTML usage

### Best Practices
- Use modern JavaScript (ES6+) features
- Follow RESTful API conventions
- Ensure responsive design principles
- Maintain clean and readable code

## Technology Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Backend**: Python with FastAPI
- **Database**: SQLite (via database.py)
- **Authentication**: Custom implementation

## Specific Considerations

- This is an educational project for a high school
- Code should be easy to understand and maintain
- Focus on practical security without over-engineering
- Prioritize user experience and accessibility
