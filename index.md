---
layout: home
title: Home
---

A collective, that focuses on shared growth


## A possible home

Explore a future home for the collective: private suites, shared spaces, a growing pavilion, a planted solar roof and walk-your-bike access to the basements.

<div class="collective-building-preview" style="margin: 1.5rem 0;">
  <iframe id="collective-building" src="{{ '/assets/building.html' | relative_url }}?embed=1" title="Interactive 3D design of a possible home for The Collective" loading="lazy" style="display:block;width:100%;height:1150px;border:1px solid #d5daca;border-radius:10px;background:#f5f3eb;"></iframe>
  <p style="margin-top:.75rem;"><a href="{{ '/assets/building.html' | relative_url }}" target="_blank" rel="noopener">Explore the building in a full window →</a></p>
</div>
<script>
(function () {
  var frame = document.getElementById('collective-building');
  window.addEventListener('message', function (event) {
    if (event.source !== frame.contentWindow || event.origin !== window.location.origin) return;
    if (!event.data || event.data.type !== 'collective-building-size') return;
    var height = Number(event.data.height);
    if (Number.isFinite(height) && height > 0) frame.style.height = Math.max(600, Math.min(2400, height)) + 'px';
  });
})();
</script>


## Okay, Why does this random repository exist?

I am actually very very optimistic with regard to the growth of collective services in my era, The advent of trains has been a boon, I believe that by creating a collective with my friends, I would be able to combine efforts to reduce individualistic effort, so everyone collectively lives a healthier lifestyle.

## Tell me more

- Anything, done as a collective is **so** much easier (provided group harmony exists)
- A group cooking for 20 people is far easier than those people cooking by themselves
- Everyone can share a laundry machine, there's no need for everyone to own their own machines
- It takes a child to raise a village, having people with shared morals only helps more people become parents, and collectively find help at raising kids.
- Everyone in the group has more time to themselves
- Something wrong happened?, Feeling Emotionally down?, We're there for you!

## So how do we get started?

- I've no clue, I guess I started by creating this webpage, it runs on something called markdown goto https://github.com/therealadityashankar/the-collective, simply edit the page and you should get an overview on how it works, here's a [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- I have a ton of friends in a group chat, so let's see if anything actually manifests :)

- I probably should start reading books on better structural planning, to see the things that can be collectively done better

## Stuff we probably have to collectively read and learn

- [Non-violent communication](https://en.wikipedia.org/wiki/Nonviolent_Communication) (for calmer interactions)

