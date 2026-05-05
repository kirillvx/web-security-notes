## XSS Labs completed (PortSwigger)
- Reflected XSS into HTML context with nothing encoded (in the search functionality) 
- Reflected XSS into HTML context with nothing encoded (in the comment functionality) 
- DOM XSS in document.write sink using source location.search // <script>alert(1)</script>
- DOM XSS in innerHTML sink using source location.search // ?search=<img src=1 onerror=alert(1)
- DOM XSS in jQuery anchor href attribute sink using location.search source // By URL - ?returnPath=javascript:alert(document.cookie)
- DOM XSS in jQuery selector sink using a hashchange event // <iframe src="https://____.__/#" onload="this.src+='<'img' src=1 onerror=print()>'">
- Reflected XSS into attribute with angle brackets HTML-encoded 
- Stored XSS into anchor href attribute with double quotes HTML-encoded
- Reflected XSS into a JavaScript string with angle brackets HTML encoded
