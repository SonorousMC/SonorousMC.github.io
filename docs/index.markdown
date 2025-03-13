---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!-- SonorousMC - Your Immersed Fantazy Minecraft Server -->


## Enter a New World!

Welcome to SonorusMC, the ultimate immersive Fantasy Minecraft server!  Step into a world brimming with magical abilities, custom structures, powerful mobs, and an exciting RPG experience. ⚡

---

## About SonorousMC

SonorusMC is a server dedicated to providing a deep and rewarding Minecraft experience.  We leverage the power of Paper and custom plugins to deliver a dynamic and unforgettable adventure.

---

## Key Features ✨

*   **SonorousAbilities:** Master potent magic with our comprehensive ability system.
*   **SonousModels:**  Bring your 3D creations to life as stunning block-display entities!
*   **SonorousWorldGen:** Explore a vast and ever-evolving custom world.
*   **SonorousRPG:** Dive into a core RPG system brimming with quests, characters, and challenges.
*   **SonorousMobs:** Face off against dynamic and captivating NPCs.
*   **SonorousNPCs:**  Control and interact with NPCs exhibiting realistic, dynamic behaviors.

---

## News
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
