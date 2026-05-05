## XSS notes
- Reflected XSS, where the malicious script comes from the current HTTP request.
- Stored XSS, where the malicious script comes from the website's database.
- DOM-based XSS, where the vulnerability exists in client-side code rather than server-side code.
- 🟢 HTML context   document.write
- 🟡 Attribute context  setAttribute("href", x)
- 🔴 JS context  
  eval(x)
  setTimeout(x)
  var x = "USER_INPUT"
- 🔵 jQuery context  $(location.hash)

HTML → тег
attribute → javascript:
JS → закрыть строку
