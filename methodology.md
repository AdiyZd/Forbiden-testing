# Testing Methodology

## Tools Used
- Manual testing with browser
- Basic SQL injection payloads

## Test Cases
1. Basic SQLi:
   - `' or 1=1 --`
   - `' or 1=1 #`
   - `admin' --`

2. Error-based detection:
   - `'`
   - `"`

## Protection Detection
- 403 Forbidden: WAF likely present
- Generic error: Basic sanitization
- No error: Possible vulnerability
