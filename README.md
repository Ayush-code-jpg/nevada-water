<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Every Drop Counts: Water in Nevada</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&family=Inter:wght@400;500;600&display=swap">
<style>
:root{--bg:#EEF5F8;--surface:#FFFFFF;--ink:#0B2A3C;--muted:#46606F;--accent:#1B6F94;--on-accent:#FFFFFF;--teal:#0F5675;--line:#C5D8E2;--hero:#0B2A3C;--hero-ink:#EEF5F8;--hero-accent:#F2A33A;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);color-scheme:light}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0B1A24;--surface:#12303F;--ink:#E6F0F5;--muted:#A9BCC6;--accent:#6CC0E6;--on-accent:#0B2A3C;--teal:#7CC8E8;--line:#2A4655;--hero:#07131A;--hero-ink:#E6F0F5;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0B1A24;--surface:#12303F;--ink:#E6F0F5;--muted:#A9BCC6;--accent:#6CC0E6;--on-accent:#0B2A3C;--teal:#7CC8E8;--line:#2A4655;--hero:#07131A;--hero-ink:#E6F0F5;color-scheme:dark}
*{box-sizing:border-box}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 72px)}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Inter,system-ui,sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--hero);z-index:10}
h1,h2,h3{font-family:'Space Grotesk',system-ui,sans-serif;line-height:1.15;margin:0}
a{color:var(--teal)}
header.nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:9;background:var(--hero);color:var(--hero-ink);display:flex;flex-wrap:wrap;gap:8px 12px;align-items:center;padding:12px 24px}
.tabs{display:flex;gap:8px;overflow-x:auto;max-width:100%;order:1}
.theme{order:2;background:transparent;color:var(--hero-ink);border:1px solid var(--hero-accent);border-radius:999px;padding:8px 16px;font:600 14px Inter,system-ui,sans-serif;min-height:40px;cursor:pointer;white-space:nowrap}
.theme:hover{background:var(--hero-accent);color:#1F2A30}
header.nav a{min-height:40px;display:inline-flex;align-items:center}
@media (max-width:640px){header.nav{padding:10px 16px}.tabs{order:3;width:100%}.wrap{padding:0 16px}.hero{padding:40px 0 48px}main{padding:40px 0 56px}}
header.nav b{font-family:'Space Grotesk',sans-serif;white-space:nowrap;margin-right:auto;padding-right:16px}
header.nav a{color:var(--hero-ink);text-decoration:none;font-size:15px;font-weight:600;white-space:nowrap;padding:8px 18px;border-radius:999px;border:1px solid transparent}
header.nav a:hover{border-color:var(--hero-accent)}
header.nav a[aria-current="page"]{background:var(--hero-accent);color:#1F2A30}
.wrap{max-width:1000px;margin:0 auto;padding:0 24px}
.hero{background:var(--hero);color:var(--hero-ink);padding:56px 0 64px}
.eyebrow{font-size:13px;font-weight:600;letter-spacing:2px;color:var(--accent);text-transform:uppercase;margin:0 0 12px}
.hero .eyebrow{color:var(--hero-accent)}
.hero h1{font-size:clamp(34px,6vw,58px)}
.hero p{font-size:18px;max-width:640px;margin:16px 0 0}
main{padding:56px 0 72px}
main h2{font-size:clamp(26px,4vw,38px);margin-bottom:10px}
.lead{font-size:18px;max-width:720px;color:var(--muted);margin:0 0 32px}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px;margin-bottom:32px}
.stat{background:var(--hero);color:var(--hero-ink);border-radius:12px;padding:22px}
.stat b{display:block;font-family:'Space Grotesk',sans-serif;font-size:36px;color:var(--hero-accent);line-height:1.1}
.stat span{font-size:14px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:24px;display:flex;flex-direction:column;gap:10px}
.card h3{font-size:21px}
.card p,.card li{font-size:15px;margin:0}
.card ul{margin:0;padding-left:20px;display:flex;flex-direction:column;gap:6px}
.tag{font-size:12px;font-weight:600;letter-spacing:1.5px;color:var(--accent);text-transform:uppercase}
.pill{display:inline-block;font-size:12px;font-weight:600;border:1px solid var(--line);border-radius:999px;padding:2px 12px;margin-right:6px;color:var(--muted)}
.btn{display:inline-block;align-self:flex-start;background:var(--accent);color:var(--on-accent);text-decoration:none;font-weight:600;padding:10px 20px;border-radius:8px;font-size:15px;margin-top:auto}
.note{margin-top:28px;background:var(--surface);border-left:4px solid var(--accent);padding:16px 20px;border-radius:0 8px 8px 0;font-size:15px}
.steps{list-style:none;padding:0;margin:0 0 32px;display:flex;flex-direction:column;gap:12px}
.steps li{display:flex;gap:16px;background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:16px 20px}
.steps .n{flex:none;width:32px;height:32px;border-radius:16px;background:var(--teal);color:var(--surface);font-weight:700;display:flex;align-items:center;justify-content:center}
.sources{background:var(--surface);border-top:1px solid var(--line);padding:32px 0;font-size:14px}
.sources summary{cursor:pointer;font-weight:600;font-size:16px}
.sources ul{padding-left:20px}
.sources li{margin-bottom:8px;word-break:break-word}
footer{background:var(--hero);color:var(--hero-ink);padding:28px 0;font-size:14px}
[hidden]{display:none!important}
</style>
</head>
<body>
<header class="nav"><b>Every Drop Counts</b><button id="theme" class="theme" type="button" aria-label="Switch to dark mode">Dark mode</button><nav class="tabs"><a href="#driving-question" data-tab="driving-question">Driving Question</a><a href="#issue" data-tab="issue">The Issue</a><a href="#organizations" data-tab="organizations">Organizations</a><a href="#how-to-help" data-tab="how-to-help">How to Help</a><a href="#digital-campaign" data-tab="digital-campaign">Digital Campaign</a></nav></header>

<div class="hero"><div class="wrap">
<p class="eyebrow">Water in Nevada</p>
<h1>Every drop counts in the desert</h1>
<p>What’s going wrong, who’s working on it, and how you can help them.</p>
</div></div>

<main><div class="wrap">

<div id="driving-question">
<p class="eyebrow">Our driving question</p>
<h2>How can we leverage our digital influence to amplify a local organization’s real-world impact on a critical social/community issue?</h2>
<p class="lead">We focused on water conservation in Nevada and the organizations working on it. Each tab answers one part of the question.</p>
<div class="grid">
<div class="card"><span class="tag">The issue</span><h3>Why water matters</h3><p>Nevada’s water supply is shrinking, and Lake Mead is at a record low.</p><a class="btn" href="#issue">See the issue</a></div>
<div class="card"><span class="tag">The organizations</span><h3>Who’s working on it</h3><p>Four Nevada groups protecting water, from Las Vegas to Reno to the Great Basin.</p><a class="btn" href="#organizations">Meet them</a></div>
<div class="card"><span class="tag">How to help</span><h3>Ways to support them</h3><p>One specific action for each organization, plus easy steps at home.</p><a class="btn" href="#how-to-help">Take action</a></div>
<div class="card"><span class="tag">Our answer</span><h3>The digital campaign</h3><p>How social media can send people to real actions and how we measure results.</p><a class="btn" href="#digital-campaign">See the plan</a></div>
</div>
<p class="note">Short answer: use posts to point people to real actions, like becoming a member, volunteering or showing up to an event, work with each organization to get the facts right, and judge success by results instead of likes.</p>
</div>

<div id="issue" hidden>
<p class="eyebrow">Tab 2 · The main issue</p>
<h2>Nevada is running short on water</h2>
<p class="lead">Southern Nevada gets most of its water from Lake Mead, and the Colorado River that fills it is shrinking.</p>
<div class="stats">
<div class="stat"><b>1,040.4 ft</b><span>Lake Mead’s level on Aug. 7, 2026, its lowest since it filled about 90 years ago</span></div>
<div class="stat"><b>&lt; 2%</b><span>Nevada’s share of the Colorado River, the smallest of any state in the basin</span></div>
<div class="stat"><b>36%</b><span>Less Lake Mead water used in Southern Nevada than two decades ago, even as the region grew</span></div>
<div class="stat"><b>Jan. 1, 2027</b><span>Nevada law bans Colorado River water on nonfunctional grass at most non-single-family properties</span></div>
</div>
<div class="grid">
<div class="card"><span class="tag">Why it’s a problem</span><h3>Less river, more demand</h3><p>Years of overuse, drought, and rising temperatures have drained Lake Mead and Lake Powell. The seven states that share the river haven’t agreed on how to divide the shortfall, and current guidelines expire at the end of 2026.</p></div>
<div class="card"><span class="tag">Where the water goes</span><h3>Mostly outdoors</h3><p>The Southern Nevada Water Authority says outdoor landscape watering is the region’s largest category of water use. That’s why grass removal is a major focus.</p></div>
<div class="card"><span class="tag">It’s statewide</span><h3>Not just Las Vegas</h3><p>Northern and rural Nevada face their own pressures, including a shrinking Walker Lake and fights over groundwater, desert springs and wetlands.</p></div>
</div>
<p class="note">Why you should care: everyone in the desert shares the same limited supply, and small choices at home and in our communities add up.</p>
</div>

<div id="organizations" hidden>
<p class="eyebrow">Tab 3 · Who’s working on it</p>
<h2>Nevada organizations tackling the problem</h2>
<p class="lead">Four groups, from a water agency to nonprofits, working on different parts of the issue across the state.</p>
<div class="grid">
<div class="card"><span class="pill">Las Vegas</span><span class="pill">Water agency</span><h3>Southern Nevada Water Authority</h3><p>Manages Southern Nevada’s water supply and runs the Water Smart Landscapes rebate, which pays people to replace thirsty grass with desert landscaping.</p><a class="btn" href="https://www.snwa.com/">Visit SNWA</a></div>
<div class="card"><span class="pill">Las Vegas</span><span class="pill">Nonprofit</span><h3>Southern Nevada Conservancy</h3><p>Partners with the Bureau of Land Management at Red Rock Canyon on education, visitor services and volunteer programs. It teaches people why desert resources are worth protecting.</p><a class="btn" href="https://southernnevadaconservancy.org/">Visit SNC</a></div>
<div class="card"><span class="pill">Reno</span><span class="pill">Nonprofit</span><h3>Walker Basin Conservancy</h3><p>Leads the effort to restore and maintain Walker Lake, and also offers environmental education and community engagement programs.</p><a class="btn" href="https://www.walkerbasin.org/">Visit WBC</a></div>
<div class="card"><span class="pill">Great Basin</span><span class="pill">Nonprofit</span><h3>Great Basin Water Network</h3><p>Formed by environmentalists, tribes, farmers and ranchers to protect groundwater, desert springs and wetlands in one of the driest regions in the country. It relies on volunteers.</p><a class="btn" href="https://greatbasinwater.org/">Visit GBWN</a></div>
</div>
</div>

<div id="how-to-help" hidden>
<p class="eyebrow">Tab 4 · Take action</p>
<h2>How to help these organizations</h2>
<p class="lead">Pick one action this week. Confirm details with each organization first.</p>
<ol class="steps">
<li><span class="n">1</span><div><b>Southern Nevada Water Authority:</b> use its Water Smart Landscapes rebate. Single-family homeowners were being paid $5 per square foot for the first 10,000 square feet of grass converted when we checked, so confirm current rates on snwa.com. Businesses and HOAs should check the 2027 turf deadline.</div></li>
<li><span class="n">2</span><div><b>Southern Nevada Conservancy:</b> become a member (from $10 a month), volunteer, donate, or attend an event, then invite a friend.</div></li>
<li><span class="n">3</span><div><b>Walker Basin Conservancy:</b> donate or join its education and community programs.</div></li>
<li><span class="n">4</span><div><b>Great Basin Water Network:</b> contact them about volunteering, and share their work with people who care about water.</div></li>
</ol>
<div class="grid">
<div class="card"><span class="tag">At home</span><h3>Cut your own use</h3><ul><li>Fix leaks</li><li>Follow local watering schedules</li><li>Swap grass for desert plants</li></ul></div>
<div class="card"><span class="tag">Online</span><h3>Spread the word</h3><ul><li>Share these organizations’ posts</li><li>Tell friends about rebates and events</li><li>Credit the source and keep facts accurate</li></ul></div>
<div class="card"><span class="tag">In your community</span><h3>Show up</h3><ul><li>Join a volunteer day</li><li>Bring a friend or classmate</li><li>Follow Colorado River news</li></ul></div>
</div>
</div>

<div id="digital-campaign" hidden>
<p class="eyebrow">Tab 5 · Our digital campaign</p>
<h2>How we use our digital influence to amplify them</h2>
<p class="lead">Our answer: use social media to send people to real actions, one clear ask at a time, and measure results, not likes.</p>
<ol class="steps">
<li><span class="n">1</span><div><b>Weeks 1–2, co-create.</b> Ask each organization what limits its impact most (money, volunteers, or awareness) and get approval on facts, photos and wording before posting.</div></li>
<li><span class="n">2</span><div><b>Weeks 3–4, build.</b> Make a shared Desert Water Pledge page and 6–8 posts. Line up 2–3 local partners, like schools, shops or creators.</div></li>
<li><span class="n">3</span><div><b>Weeks 5–8, launch.</b> Every post points to one link with two options: take the free pledge, or support one of the organizations. Host or promote a real event and ask everyone to bring a friend.</div></li>
<li><span class="n">4</span><div><b>Week 9, report back.</b> Share results, thank supporters, and keep sign-ups on an email list the organizations own.</div></li>
</ol>
<div class="grid">
<div class="card"><span class="tag">What we post</span><h3>Content that moves people</h3><ul><li>Myth vs. fact slides</li><li>Short videos on how desert plants and animals survive on little water</li><li>Desert-smart yard before and afters</li><li>Pledge challenge: take it, tag a friend</li></ul></div>
<div class="card"><span class="tag">Attention into action</span><h3>Real-world asks</h3><ul><li>Take the water pledge (free)</li><li>Join as a member or donate</li><li>Sign up for a volunteer day</li><li>Attend an event or hike</li></ul></div>
<div class="card"><span class="tag">Audit example: SNC</span><h3>What we found online</h3><ul><li>Homepage doesn’t mention water</li><li>Facebook, Instagram, LinkedIn and X are linked from the site</li><li>A separate Red Rock Canyon site lists events</li><li>To record: [followers], [posts per month], [top posts]</li></ul></div>
<div class="card"><span class="tag">How we measure</span><h3>Results, not likes</h3><ul><li>New members and donors</li><li>Volunteer sign-ups</li><li>Event attendance</li><li>Email list growth</li></ul></div>
</div>
<p class="note">Ground rules: get each organization’s approval, verify every fact, never collect classmates’ personal info, and never handle money yourself. Send people to the organization’s own pages.</p>
</div>
</div></main>

<section class="sources"><div class="wrap"><details><summary>Sources</summary>
<ul>
<li>Associated Press, “Lake Mead hits historic low water level as Colorado River struggles,” Aug. 2026.</li>
<li>Nevada Current, “As November deadline nears, Colorado River states ‘nowhere close to an agreement,’” 2025 (Nevada’s share, 36% reduction).</li>
<li>Las Vegas Review-Journal, “Lake Mead’s water woes deepen: Nevada’s share slashed once again,” Aug. 15, 2025.</li>
<li>Las Vegas Review-Journal, reporting on Nevada’s nonfunctional turf law taking effect Jan. 1, 2027.</li>
<li>Press release (Mar. 13, 2026) relaying SNWA’s statement on outdoor water use, and Nevada Real Estate Group guide to SNWA rebate rates (read Oct. 23, 2026).</li>
<li>Southern Nevada Conservancy, southernnevadaconservancy.org; Walker Basin Conservancy, walkerbasin.org; Anthropocene Alliance profile of Great Basin Water Network.</li>
<li>Drafted with Claude (Anthropic), Nov. 2026. Add your teacher’s required AI citation.</li>
</ul></details></div></section>
<footer><div class="wrap">Student project · Not affiliated with or endorsed by the organizations listed. Facts as of November 2026; confirm details before acting.</div></footer>

<script>
(function(){
var views=['driving-question','issue','organizations','how-to-help','digital-campaign'];
function show(){
var h=location.hash.slice(1);
if(views.indexOf(h)<0)h='driving-question';
views.forEach(function(v){
document.getElementById(v).hidden=(v!==h);
var a=document.querySelector('[data-tab="'+v+'"]');
if(v===h)a.setAttribute('aria-current','page');else a.removeAttribute('aria-current');
});
window.scrollTo(0,0);
}
window.addEventListener('hashchange',show);
show();
var root=document.documentElement,btn=document.getElementById('theme'),mq=window.matchMedia('(prefers-color-scheme: dark)');
function apply(t){root.setAttribute('data-theme',t);btn.textContent=t==='dark'?'Light mode':'Dark mode';btn.setAttribute('aria-label','Switch to '+(t==='dark'?'light':'dark')+' mode');}
var saved=null;try{saved=localStorage.getItem('theme');}catch(e){}
apply(saved||(mq.matches?'dark':'light'));
btn.addEventListener('click',function(){var n=root.getAttribute('data-theme')==='dark'?'light':'dark';apply(n);try{localStorage.setItem('theme',n);}catch(e){}});
})();
</script>
</body>
</html>
