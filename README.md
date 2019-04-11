# HackYourWay_InfoSec
The tool kit you need to break into Info Sec - Application Security focused.
This resource assumes knowledge of basic HTML and JavaScript. I've linked resources here in this blog: https://medium.com/@lovelydreamer/how-many-hours-to-learn-to-code-862-67916333cce2


First you should learn how browsers and web applications work. Then you will better understand how they break and why.
Then you will need to install and use a web application proxy. After that I've listed some web vulnerability resources in what they are and some practice sites. Lastly, vulnerable applications and other helpful tools outside of appsec. 

  
## Understanding Browsers & Browser Security Models:
  The Tangled Web by: Michał Zalewski: https://nostarch.com/tangledweb
  HTML5Rocks - How browsers work: https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
  Mozilla CORS documentation:https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS
  Mozilla SOP documentation:https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy
  Web Security Lecture: http://css.csail.mit.edu/6.858/2015/lec/l11-web-security.txt
  NetSparker Same Origin Policy: https://www.netsparker.com/whitepaper-same-origin-policy/#WorldWithoutSameOriginPolicy
  
  ## Application Proxy
  Bugcrowd University - Intro to Burp Suite: https://www.youtube.com/watch?v=h2duGBZLEek
  Using Burp to attack Session management: https://support.portswigger.net/customer/portal/articles/1964053-using-burp-to-attack-session-management
  Installing Burp Suite Application proxy: https://medium.com/@lovelydreamer/installing-burp-suite-application-proxy-757e5a4e85a8
  
## How do applications work?
  Anatomy of HTTP: http://blog.catchpoint.com/2016/08/19/revisiting-anatomy-http-part/
  Ale - What Happens When: https://github.com/alex/what-happens-when
  
## Web Vulnerabilties:
   
  ****XSS****
  XSS Hunter - Blind XSS callbacks https://xsshunter.com/signup
  Google XSS Challenge: https://www.google.com/about/appsecurity/learning/xss/

    
  ****CSRF****
  Hacksplaining CSRF: https://www.hacksplaining.com/exercises/csrf#/start
  CSRF custom headers: https://www.owasp.org/index.php/Cross-     Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet#Use_of_Custom_Request_Headers  
  NCC Group Common CSRF Misconceptions: https://www.nccgroup.trust/us/about-us/newsroom-and-events/blog/2017/september/common-csrf-prevention-misconceptions/
  Mozilla Set-Cookie Docs (samesite cookie flag): https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie
  
  ****Access Control****
  Function Level Access Control: 
  https://www.owasp.org/index.php/Top_10_2013-A7-Missing_Function_Level_Access_Control
  SSRF:
  https://www.owasp.org/index.php/Server_Side_Request_Forgery
  https://cwe.mitre.org/data/definitions/918.html
  Using burp to attack session management: https://support.portswigger.net/customer/portal/articles/1964053-using-burp-to-attack-session-management
  
  
  -- BOOKS --
    Web Application Hackers Handbook by Dafydd Stuttard and Marcus Pinto
    The Tangled Web by: Michał Zalewski: https://nostarch.com/tangledweb
  
  
  -- VIDEOS --
  Bugcrowd Researcher tutorials: https://forum.bugcrowd.com/t/researcher-resources-tutorials/370?u=samhouston
  Bugcrowd University: https://github.com/bugcrowd/bugcrowd_university
  
  -- Cheat Sheets --
  OWASP Top 10: https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet
    
 ## Intentionally vulnerable apps:
  Google Gruyere: https://google-gruyere.appspot.com/
  Rapid7 Metasploitable 3: https://blog.rapid7.com/2016/11/15/test-your-might-with-the-shiny-new-metasploitable3/
  Badstore https://www.vulnhub.com/entry/badstore-123,41/
  
  ## Unintentionally vulnerable apps:
      *** Strongly recommend working within a bounty. There can be legal repercussions for testing a website, even with  the best of intentions.***
      
    Bugcrowd
    Hackerone
   
   
Other:   
## Bash

  
## Python
  Black Hat Python
  
