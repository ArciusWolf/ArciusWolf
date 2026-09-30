<!--
  DESIGN TOKENS (kept in one place so you can retune fast)
  Sunset gradient : #FF8A5B -> #F6A96B -> #E8739E -> #7B68EE   (waves, ribbons)
  Icon ink        : #E0692F ember, #E2557F rose, #7B68EE violet (3:1+ on light AND dark GitHub)
  Text-on-light   : #C2417A rose, #5B47D6 violet               (4.5:1+ on white)
  Text-on-dark    : #E8739E rose, #9D8FFF violet               (4.5:1+ on #0d1117)
  Card ink        : #282A36

  LAYOUT RULE: GitHub strips CSS, so alignment comes from fixed cell widths.
  Every section is 700px wide:  split cards = 480 text + 220 sticker,  grids = 4 x 175.
  Every sticker uses the same height (180) so they read as one set, whatever their aspect ratio.
-->

<!-- ===================== HERO ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF8A5B,35:F6A96B,65:E8739E,100:7B68EE&height=140&section=header" width="100%" alt="" />

<!-- Name: lighter rose on dark mode, deeper rose on light mode. Swap font=Bungee for any Google Font. -->
<a href="https://github.com/ArciusWolf">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Bungee&size=56&letterSpacing=6px&duration=1800&repeat=false&color=E8739E&center=true&vCenter=true&width=560&height=90&lines=CYRUS">
    <img src="https://readme-typing-svg.demolab.com?font=Bungee&size=56&letterSpacing=6px&duration=1800&repeat=false&color=C2417A&center=true&vCenter=true&width=560&height=90&lines=CYRUS" alt="Cyrus" />
  </picture>
</a>

<!-- Rotating roles -->
<a href="https://github.com/ArciusWolf">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=22&letterSpacing=1px&duration=3000&pause=1200&color=9D8FFF&center=true&vCenter=true&width=720&height=40&lines=Unity+Game+Developer+from+Vietnam;Building+gameplay+systems+and+simulation+mechanics;Crafting+Unity+tools+with+C%23;Currently+building+Furever;Polishing+until+it+feels+good+to+play">
    <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=22&letterSpacing=1px&duration=3000&pause=1200&color=5B47D6&center=true&vCenter=true&width=720&height=40&lines=Unity+Game+Developer+from+Vietnam;Building+gameplay+systems+and+simulation+mechanics;Crafting+Unity+tools+with+C%23;Currently+building+Furever;Polishing+until+it+feels+good+to+play" alt="Unity game developer from Vietnam" />
  </picture>
</a>

<br><br>

<!-- TODO: replace the placeholder links below with your real ones -->
<a href="https://youtube.com/@YOUR_CHANNEL"><img src="https://img.shields.io/badge/YouTube-282A36?style=for-the-badge&logo=youtube&logoColor=FF4D4D" height="32" alt="YouTube" /></a>
<a href="https://discord.gg/YOUR_INVITE"><img src="https://img.shields.io/badge/Discord-282A36?style=for-the-badge&logo=discord&logoColor=8EA1E8" height="32" alt="Discord" /></a>
<a href="https://facebook.com/YOUR_PROFILE"><img src="https://img.shields.io/badge/Facebook-282A36?style=for-the-badge&logo=facebook&logoColor=5B9DFF" height="32" alt="Facebook" /></a>
<a href="mailto:cyberdroid133@gmail.com"><img src="https://img.shields.io/badge/Gmail-282A36?style=for-the-badge&logo=gmail&logoColor=FF6B5B" height="32" alt="Email" /></a>

<br><br>

</div>

<!-- ===================== ABOUT  (text 480 | sticker 220, both vertically centered) ===================== -->
<table align="center">
  <tr>
    <td width="480" valign="middle">
      <h3>👋 Hi, I'm Cyrus</h3>
      <img src="https://api.iconify.design/lucide/globe.svg?color=%23E2557F&height=18" height="18" align="absmiddle" alt="" />&nbsp; Game developer from <b>Vietnam</b><br><br>
      <img src="https://api.iconify.design/lucide/gamepad-2.svg?color=%23E0692F&height=18" height="18" align="absmiddle" alt="" />&nbsp; I build gameplay systems, simulation mechanics and Unity tools with <b>C#</b><br><br>
      <img src="https://api.iconify.design/lucide/paw-print.svg?color=%237B68EE&height=18" height="18" align="absmiddle" alt="" />&nbsp; Currently working on <b>Furever</b>, a cozy life simulation game built with <b>Unity 6</b>
    </td>
    <td width="220" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/Messenger_creation_35C484F1-59BC-46A5-A289-D478C335FF1A.png" height="180" alt="Cyrus sticker" />
    </td>
  </tr>
</table>

<br>

<!-- ===================== WHAT I BUILD  (4 x 175) ===================== -->
<h2 align="center"><img src="https://api.iconify.design/lucide/gamepad-2.svg?color=%23E2557F&height=28" height="28" align="absmiddle" alt="" />&nbsp; What I Build</h2>

<table align="center">
  <tr>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/puzzle.svg?color=%23E0692F&height=34" height="34" alt="" /><br><b>Gameplay<br>Architecture</b><br><sub>Reusable, modular systems</sub></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/sprout.svg?color=%23E2557F&height=34" height="34" alt="" /><br><b>Simulation<br>Systems</b><br><sub>Needs, day / night, interactions</sub></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/wrench.svg?color=%237B68EE&height=34" height="34" alt="" /><br><b>Editor<br>Tooling</b><br><sub>Unity tools that speed up workflows</sub></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/zap.svg?color=%23E0692F&height=34" height="34" alt="" /><br><b>Performance<br>&nbsp;</b><br><sub>Performance-conscious Unity development</sub></td>
  </tr>
</table>

<br>

<!-- ===================== TECH STACK ===================== -->
<h2 align="center"><img src="https://api.iconify.design/lucide/layers.svg?color=%237B68EE&height=28" height="28" align="absmiddle" alt="" />&nbsp; Tech Stack</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=unity,cs,blender,figma,git,github&perline=6" alt="Unity, C#, Blender, Figma, Git, GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/GradientRibbon.png" width="100%" alt="" />
</p>

<!-- ===================== FUREVER  (text 480 | sticker 220, then 4 x 175 grid) ===================== -->
<h2 align="center"><img src="https://api.iconify.design/lucide/paw-print.svg?color=%23E2557F&height=28" height="28" align="absmiddle" alt="" />&nbsp; Currently Building: Furever</h2>

<table align="center">
  <tr>
    <td width="480" valign="middle">
      A <b>cozy life simulation game</b> built with <b>Unity 6</b>.<br><br>
      <img src="https://img.shields.io/badge/Unity_6-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity 6" />
      <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" /><br>
      <img src="https://img.shields.io/badge/Genre-Cozy_Life_Sim-C2417A?style=for-the-badge" alt="Genre: cozy life sim" />
      <img src="https://img.shields.io/badge/Mode-Single_Player-B8501A?style=for-the-badge" alt="Mode: single player" />
      <img src="https://img.shields.io/badge/Status-In_Development-5B47D6?style=for-the-badge" alt="Status: in development" />
    </td>
    <td width="220" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/Kh%C3%B4ng%20C%C3%B3%20Ti%C3%AAu%20%C4%90%E1%BB%8140_20241015121319.png" height="180" alt="Cyrus peace sticker" />
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/hand.svg?color=%23E0692F&height=30" height="30" alt="" /><br><b>Interaction<br>System</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/drama.svg?color=%23E2557F&height=30" height="30" alt="" /><br><b>Player<br>States</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/hammer.svg?color=%237B68EE&height=30" height="30" alt="" /><br><b>Build<br>Mode</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/backpack.svg?color=%23E0692F&height=30" height="30" alt="" /><br><b>Inventory</b></td>
  </tr>
  <tr>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/sun-moon.svg?color=%23E2557F&height=30" height="30" alt="" /><br><b>Day /<br>Night</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/fish.svg?color=%237B68EE&height=30" height="30" alt="" /><br><b>Fishing</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/bed.svg?color=%23E0692F&height=30" height="30" alt="" /><br><b>Player<br>Needs</b></td>
    <td align="center" valign="top" width="175"><img src="https://api.iconify.design/lucide/sliders-horizontal.svg?color=%23E2557F&height=30" height="30" alt="" /><br><b>Editor<br>Tools</b></td>
  </tr>
</table>

<!-- TODO: add a gameplay GIF or screenshot here. It is the single biggest upgrade you can make.
<p align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/furever-preview.gif" width="700" alt="Furever gameplay" />
</p>
-->

<p align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/GradientRibbon.png" width="100%" alt="" />
</p>

<!-- ===================== DEV DASHBOARD ===================== -->
<h2 align="center"><img src="https://api.iconify.design/lucide/activity.svg?color=%23E0692F&height=28" height="28" align="absmiddle" alt="" />&nbsp; Dev Dashboard</h2>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ArciusWolf&background=282A36&border=E8739E&stroke=6272A4&ring=F6A96B&fire=E8739E&currStreakNum=F8F8F2&sideNums=F8F8F2&currStreakLabel=F6A96B&sideLabels=BD93F9&dates=6272A4&border_radius=10" alt="GitHub contribution streak" />
</p>

<div data-importer="stats" align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/stats-output/stats.svg?hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false&order=1" height="150" alt="GitHub stats" />
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/languages-output/languages.svg?locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" height="150" alt="Top languages" />
</div>

<br>

<div align="center">
  <picture data-importer="pacman">
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/pacman-output/pacman-contribution-graph-dark.svg?game=pacman">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/pacman-output/pacman-contribution-graph.svg?game=pacman">
    <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/pacman-output/pacman-contribution-graph.svg?game=pacman">
  </picture>
</div>

<br>

<!-- ===================== RECENTLY PLAYED  (music card 480 | sticker 220) ===================== -->
<h2 align="center"><img src="https://api.iconify.design/lucide/headphones.svg?color=%237B68EE&height=28" height="28" align="absmiddle" alt="" />&nbsp; Recently Played</h2>

<table align="center">
  <tr>
    <td width="480" align="center" valign="middle">
      <div data-importer="music" align="center">
        <a href="https://open.spotify.com/user/21nn7zabugvrfazixrvtljp4i">
          <img src="https://spotify-recently-played-readme.vercel.app/api?user=21nn7zabugvrfazixrvtljp4i&count=5&unique=false" alt="Spotify recently played" />
        </a>
      </div>
      <sub>fueled by coffee and music</sub>
    </td>
    <td width="220" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/IMG_6790.PNG" height="180" alt="Sleepy Cyrus with coffee" />
    </td>
  </tr>
</table>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/GradientRibbon.png" width="100%" alt="" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ArciusWolf/ArciusWolf/main/Cyrus%20Head%20Gift%20%281%29.png" height="88" alt="Pixel Cyrus" />
</p>

<p align="center">
  <sub>Building systems, testing ideas, and polishing them until they feel good to play.</sub>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ArciusWolf&label=Profile+views&color=C2417A&style=flat-square" alt="Profile views" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF8A5B,35:F6A96B,65:E8739E,100:7B68EE&height=100&section=footer" width="100%" alt="" />
