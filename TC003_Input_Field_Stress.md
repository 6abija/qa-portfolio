# TC003 - Input Field Stress with Mixed Content

**Title**: Input Form Field with Multi-language, Emojis, Scripts, and Special Characters  
**Objective**: Ensure form input sanitization and internationalization support  

## Steps
1. Enter: `"汉字абв🙂🔥💡<script>alert(1)</script>"` into all text fields  
2. Submit the form  

## Expected Result
- No crash or HTML/JS injection  
- Special characters and emojis are stored and displayed correctly  
- No "XSS" vulnerability triggered  

**Type**: Security, Internationalization  
**Priority**: High