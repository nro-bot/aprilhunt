---
layout: homepage 
---


<!-- Text can be **bold**, _italic_, or ~~strikethrough~~ -->


<!--- ![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png) -->





# Welcome!

This a small puzzle hunt written as practice by a small group of people. There
will be 8 puzzles and one meta, and an answer checker. The puzzles are short, if
we had to say, it might take 2-3 people no more than 4 hours.

<h2><p style="text-align: center;">Hunt will begin in:</p></h2>
<div class="countdown" id="countdown">
<ul>
<li><span id="days"></span><br>days</li>
<li><span id="hours"></span><br>Hours</li>
<li><span id="minutes"></span><br>Minutes</li>
<li><span id="seconds"></span><br>Seconds</li>
</ul>
</div>

---

## Email Notifications 

If you would like to be notified right away when 1. hunt opens 2. solutions
released, please enter email below. (Note: Strictly optional, webpage should
update on day of hunt with passcode to puzzles)

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSddbKOTJN2E_08dYiGlicGEMlBbXj4gFeyfdSeHHt9oPgk2MQ/viewform?embedded=true" width="600" height="469" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>


---

## FAQ

We made an attempt at an FAQ, but honestly this is just for our friends right now so we
assume you are familiar with puzzlehunts...

- What is a puzzle?

These are free-form puzzles where there are no instructions, unlike a crossword
puzzle. The answers will usually be a word or short phrase, which you will
somehow extract from the the puzzle. e.g.


- What is hunt?

- What is a meta?

A meta is a puzzle which uses the answers from other (earlier) puzzles.
Thus, in order to solve the meta (and win the hunt!), you must solve several, ir
not all, of the other puzzles.

---

## Leaderboard

When people finish the meta, their names will show up here:

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTx5MtV4QKFO5hq7QppPUx2qEvJV29TNfVR80uxloN7fPoFcjyl3qHpCY8d5ZBkIgfYlHJFldXvXIKN/pubhtml?gid=1309153968&amp;single=true&amp;widget=true&amp;headers=false"  width="500" height="400"></iframe>


---

## For Beta Testers

<!--[Link to another page](./another-page.html). -->


<form id="form" onsubmit="return false;">
<input style="padding:0px" type="text" id="submitpass" size="20"/>
<input style="padding:0px" type="submit" value='Enter passphrase' onclick="makeURL();" />
</form>


<div id='divurl'></div>

<noscript>
If you disabled javascript, just append '.html' to the passphrase :P
</noscript>



---

## Notes

Our hunt is not secure, in good spirit, if you are participating please do not
try to reverse the answers from the source code.


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
