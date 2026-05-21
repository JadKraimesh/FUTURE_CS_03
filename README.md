# FUTURE_CS_03 - API Security Risk Analysis

## Task
Cyber Security Internship Task 3 by Future Interns.

## Objective
The objective of this project is to perform a read-only API security risk analysis on a public demo API and identify common API security risks such as open endpoints, missing authentication, excessive data exposure, and limited rate-limiting visibility.

## Scope
This project only focuses on ethical and read-only API analysis.

No exploitation, bypass attempts, flooding, denial-of-service testing, or harmful activity was performed.

## API Tested
ReqRes API  
https://reqres.in

## Tools Used
- Postman
- Browser DevTools
- ReqRes API
- GitHub
- Canva / Google Docs / MS Word

## Assessment Areas
- Authentication requirements
- API headers and responses
- Open or unauthenticated endpoints
- Excessive data exposure
- Predictable endpoint structure
- Rate-limiting observations
- Input validation observations

## Repository Structure

FUTURE_CS_03/
│
├── report/
│   └── API_Security_Risk_Analysis_Report.pdf
│
├── screenshots/
│   ├── users_endpoint.png
│   ├── single_user_endpoint.png
│   ├── resource_endpoint.png
│   ├── headers_analysis.png
│   └── authentication_analysis.png
│
├── analysis/
│   └── findings.md
│
└── README.md

## Methodology
1. Selected a safe public demo API for testing.
2. Reviewed available API endpoints.
3. Sent read-only GET requests using Postman.
4. Inspected API responses, headers, and status codes.
5. Checked whether authentication was required.
6. Identified possible API security risks.
7. Classified each risk by severity.
8. Suggested business-friendly remediation steps.

## Key Findings
| Finding | Severity |
|---|---|
| Publicly accessible API endpoints | Medium |
| No authentication required for selected endpoints | Medium |
| Predictable endpoint structure | Low |
| Limited visible rate-limiting protection | Medium |
| Response metadata exposure | Low |

## Deliverables
- API Security Risk Analysis Report
- Postman request screenshots
- Security findings and risk classifications
- Public GitHub documentation

## Disclaimer
This project was completed for educational purposes as part of the Future Interns Cyber Security Internship Program. Only public demo APIs were tested, and all activity remained read-only and ethical.

## Author
Jad Kraimesh  
Cyber Security Intern — Future Interns
