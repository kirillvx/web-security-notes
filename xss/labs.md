## XSS Labs completed (PortSwigger)
- Reflected XSS into HTML context with nothing encoded (in the search functionality) 
- Reflected XSS into HTML context with nothing encoded (in the comment functionality) 
- DOM XSS in document.write sink using source location.search // <script>alert(1)</script>
- DOM XSS in innerHTML sink using source location.search // <img src=x onerror=alert(1)>
- DOM XSS in jQuery anchor href attribute sink using location.search source // By URL - ?returnPath=javascript:alert(document.cookie)
