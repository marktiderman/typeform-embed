# typeform-embed

Typeforms are powerful.  If you embed them in your existing site or app they can make a seamless experience.  However the options typeform outpots for the embed code includes a lot of opinionated code.  I've broken down their embed code and stripped out any opinionated code.  Enjoy. 

## Vanilla Embed Code
```
<a  
    data-auto-open=true    
    class="typeform-share button"
    href="https://streamlined.typeform.com/to/DJ4GJt"
    data-mode="popup"
    data-hide-headers=true 
    data-hide-footer=true 
    data-submit-close-delay="0" 
    target="_blank"
    >Launch me </a>
<script> (function () { var qs, js, q, s, d = document, gi = d.getElementById, ce = d.createElement, gt = d.getElementsByTagName, id = "typef_orm_share", b = "https://embed.typeform.com/"; if (!gi.call(d, id)) { js = ce.call(d, "script"); js.id = id; js.src = b + "embed.js"; q = gt.call(d, "script")[0]; q.parentNode.insertBefore(js, q) } })() </script>
```

## Embed code for Salient Theme
```
<a  
    data-auto-open=true    
    class="typeform-share nectar-button large regular accent-color regular-button"
    href="https://streamlined.typeform.com/to/DJ4GJt"
    data-mode="popup"
    data-hide-headers=true 
    data-hide-footer=true 
    data-submit-close-delay="0" 
    target="_blank"
    >Launch Me - Salient</a>
<script> (function () { var qs, js, q, s, d = document, gi = d.getElementById, ce = d.createElement, gt = d.getElementsByTagName, id = "typef_orm_share", b = "https://embed.typeform.com/"; if (!gi.call(d, id)) { js = ce.call(d, "script"); js.id = id; js.src = b + "embed.js"; q = gt.call(d, "script")[0]; q.parentNode.insertBefore(js, q) } })() </script>
```
