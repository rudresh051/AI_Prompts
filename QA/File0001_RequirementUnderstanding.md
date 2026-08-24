# Prompt 1

Act as a Senior QA Engineer, Business Analyst, Solution Architect, Security Engineer, Performance Engineer, and Support Engineer.

Your goal is NOT to generate test cases immediately.

Instead, help me deeply understand the requirement before testing.

Analyze the following requirement from multiple perspectives:

1. Business Perspective
- What business problem is being solved?
- Who are the stakeholders?
- What are the expected business outcomes?
- Are there any business rules that appear to be missing?

2. End User Perspective
- How will different user roles interact with this feature?
- What user expectations should be considered?
- What usability or accessibility concerns exist?
- What user scenarios might have been overlooked?

3. Developer / Technical Perspective
- What implementation assumptions might developers make?
- Which modules, APIs, databases, or services could be affected?
- What integration points should be considered?
- What technical risks exist?

4. QA Perspective
Identify:
- Missing requirements
- Ambiguous statements
- Hidden assumptions
- Inconsistent requirements
- Boundary conditions
- State transition scenarios
- Validation rules
- Error handling scenarios
- Data integrity concerns
- Regression risk areas

Do NOT generate detailed test cases unless explicitly requested.

5. Security Perspective
Consider:
- Authentication
- Authorization
- Input validation
- Sensitive data exposure
- Injection risks
- Privilege escalation
- Audit logging
- Compliance considerations

6. Performance & Reliability Perspective
Consider:
- Large datasets
- Concurrent users
- High transaction volume
- Timeouts
- Retry behaviour
- Scalability
- Resource utilization
- Availability

7. Operations / Support Perspective
Consider:
- Logging
- Monitoring
- Alerting
- Troubleshooting
- Error messages
- Recoverability
- Support impact

8. Risk Analysis
Identify:
- High-risk scenarios
- Production risks
- Data loss risks
- Financial impact
- Customer impact
- Operational impact

9. Requirement Gaps
Create a table with:

| Requirement Gap | Why it Matters | Question to Ask |

10. Clarification Questions
Generate all important questions I should ask the Product Owner, Business Analyst, Developer, or Architect before testing.

Prioritize them as:
- Critical
- High
- Medium
- Low

11. Testing Strategy (High-Level Only)
Suggest:
- Areas requiring deep testing
- Areas suitable for exploratory testing
- Possible regression impact
- Automation candidates
- Non-functional testing opportunities

Important Instructions:
- Challenge the requirement instead of accepting it.
- Point out implicit assumptions.
- Identify what could fail in production.
- Highlight scenarios that are commonly forgotten.
- Explain your reasoning.
- Do not invent requirements; clearly state assumptions when information is missing.
- Focus on improving understanding rather than producing test cases.

Requirement:
<PASTE REQUIREMENT HERE>