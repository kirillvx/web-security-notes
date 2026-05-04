# SQL Injection Notes

## Types
- Error-based
- UNION-based
- Blind SQLi

## Basic payloads
- ' OR 1=1 --
- ' OR '1'='1

## UNION
- Finding number of columns
- UNION SELECT null,null

## Notes
- Input must be sanitized
- Most vulnerabilities come from unsanitized input
