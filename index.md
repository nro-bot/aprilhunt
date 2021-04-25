---
layout: homepage 
---


# Welcome!

This a small puzzle hunt written as practice by a small group of people. There
will be 8 puzzles and one meta, and an answer checker. The puzzles are short, if
we had to guess, it might take intermediate 2-3 people around 4 hours. 
The hunt will run from noon EDT Saturday (24 April 2021) to midnight Sunday, at
which point we will release the solutions. 

# [🆕 The hunt has begun! Click to enter ➡️ ]({{site.baseurl}}/Welcome%20to%20mini%20hunt!.html)


<!--<h2><p style="text-align: center;">Hunt will begin in:</p></h2>-->
<!--<div class="countdown" id="countdown">-->
<!--<ul>-->
<!--<li><span id="days"></span><br>days</li>-->
<!--<li><span id="hours"></span><br>Hours</li>-->
<!--<li><span id="minutes"></span><br>Minutes</li>-->
<!--<li><span id="seconds"></span><br>Seconds</li>-->
<!--</ul>-->
<!--</div>-->

---

## Updates & Errata

If there are any, timestamped errata will appear here.

24 April 23:35 -- [Some Random Poetry] publix should be switched to Walgreens for disambiguation.

---

## Email Notifications 

If you would like to be notified right away when hunt opens and solutions
released, please enter email below. (Note: Strictly optional, this page should
update on day of hunt publicly with passcode to puzzles.) This also helps give us a sense
of numbers.

<iframe
src="https://docs.google.com/forms/d/e/1FAIpQLSddbKOTJN2E_08dYiGlicGEMlBbXj4gFeyfdSeHHt9oPgk2MQ/viewform?embedded=true"
width="600" height="469" frameborder="0" marginheight="0"
marginwidth="0">Loading…</iframe>


---

## FAQ

We made an attempt at an FAQ, though we think only existing puzzlers will find
this hunt. 

- How difficult is this?

The first two puzzles are very beginner friendly (the easier end of
puzzled pint). We think the final two are medium-easy mystery hunt puzzles. **As a
large disclaimer**, we didn't expect that many people to find this in time
(read: maybe 5 people), we testsolved all once but not twice, and never as a
whole hunt. Bring on the feedback >:D and don't take it too seriously please.

[Fri evening update: We had successful solo testsolve of whole hunt]

- What if I want to write puzzles, but don't know how to start?

You should join us! Fill out the contact form :D We made this hunt to learn and
practice puzzle writing.

- Where do I register my team?

There is no team registration, the leaderboard will ask your
(team)name when you get the meta. 

- What are these puzzles?

These are free-form puzzles where there are no instructions, unlike a crossword
puzzle. The answers will usually be a word or short phrase, which you will
somehow extract from the the puzzle. Perhaps see this [blog
post](https://blog.vero.site/post/puzzlehunts) for more info.

- What is a hunt?

Several puzzles meant to be solved together. If the hunt is timed people will
compete to be first to finish the hunt.

- What counts as finishing the hunt?

Solving the meta puzzle is sufficient to enter the leaderboard (if you wish).

- What is a meta?

A meta is a puzzle which uses the answers from other (earlier) puzzles.
Thus, in order to solve the meta (and win the hunt!), you must solve several, if
not all, of the other puzzles.

- Who made this? Who are my emails being stored by? 

We are: nrobot, James, Tchakka, Dbopp, robo, L, Zoz, dwilson, Seth. In 2020, we
hunted with the team known in 2020 as "We can't hear you you're on mute". But we
don't represent the team in any way, and many of us are writing puzzles for the
first time. Any feedback appreciated!

- Why write?

It's a fun social activity, we get together and try each other's puzzles and you
can see the puzzle revision process. Plus it helps improve puzzle solving skills
too. 

- What if I get stuck on a puzzle?

If you feel super frustrated, drop us an email us at mutedpuzzles at gmail with
subject line HINT REQUEST for ["puzzle name"] ["your username"], brackets
included. 

---

## Leaderboard

When people finish the meta, their names will show up here:

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTx5MtV4QKFO5hq7QppPUx2qEvJV29TNfVR80uxloN7fPoFcjyl3qHpCY8d5ZBkIgfYlHJFldXvXIKN/pubhtml?gid=318061438&amp;single=true&amp;widget=true&amp;headers=false" width="500" height="400"></iframe>

---


## Contact Us

<iframe
src="https://docs.google.com/forms/d/e/1FAIpQLSecPTIR03lfSIbjxPjdts8dzLb5_fOnueDb78aLXT0z6CKyBw/viewform?embedded=true"
width="600" height="650" frameborder="0" marginheight="0"
marginwidth="0">Loading…</iframe>


---

## For Beta Testers

<form id="form" onsubmit="return false;">
<input style="padding:0px" type="text" id="submitpass" size="20"/>
<input style="padding:0px" type="submit" value='Enter passphrase' onclick="makeURL();" />
</form>
<div id='divurl'></div>
<noscript>
If you disabled javascript, just append '.html' to the passphrase and enter it
after the website's domain name :)
</noscript>
<br>

---

## Notes

Our hunt is not secure, in good spirit, if you are participating please do not
try to reverse the answers from the source code.

<script>
function makeURL() {
    passphrase = document.getElementById("submitpass").value;
    divurl = document.getElementById('divurl');
    html = '<br><h3>If the passphrase is correct, this URL will work: <br><br>';
    html += '<a href="' + String(passphrase) + '.html">Link</a>';
    html += '<br><br>Otherwise you will get a 404 error</h3>'; 
    divurl.innerHTML = html;
}
</script>

