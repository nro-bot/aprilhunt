---
layout: homepage 
---


<!-- Text can be **bold**, _italic_, or ~~strikethrough~~ -->


<!--- ![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png) -->

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

---



## Leaderboard

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTx5MtV4QKFO5hq7QppPUx2qEvJV29TNfVR80uxloN7fPoFcjyl3qHpCY8d5ZBkIgfYlHJFldXvXIKN/pubhtml?gid=1309153968&amp;single=true&amp;widget=true&amp;headers=false"  width="500" height="400"></iframe>

Our hunt is not secure, in good spirit please do not try to reverse the answers
from the source code.


---

## Enter passphrase

<!--[Link to another page](./another-page.html). -->


<form id="form" onsubmit="return false;">
<input style="padding:0px" type="text" id="submitpass" size="20"/>
<input style="padding:0px" type="submit" value='Check passphrase' onclick="makeURL();" />
</form>


<div id='divurl'></div>

<noscript>
If you disabled javascript, just append '.html' to the passphrase :P
</noscript>


<script>
    function makeURL() {
    console.log('hi');
    passphrase = document.getElementById("submitpass").value;
    divurl = document.getElementById('divurl');
    html = '<br><h3>If the passphrase is correct, this URL will work: <br><br>';
    html += '<a href="' + String(passphrase) + '.html">Link</a>';
    html += '<br><br>Otherwise you wil get a 404 error</h3>'; 
    divurl.innerHTML = html;

    }

</script>
