# Theme & Palette

|                     | light   | dark    |
| ------------------: | ------- | ------- |
| <b><i>board</i></b> | mono_e0 | mono_1f |
| <b><i>paper</i></b> | mono_ff | mono_00 |
| <b><i>title</i></b> | mono_00 | mono_ff |
| <b><i>notes</i></b> | mono_2f | mono_d0 |

|                     | color   | plain   | clean   |
| ------------------: | ------- | ------- | ------- |
| <b><i>frame</i></b> | details | (notes) | (paper) |
| <b><i>glare</i></b> | elegant | (notes) | (paper) |

|                     | fill    | none    |
| ------------------: | ------- | ------- |
| <b><i>paint</i></b> | summary | (paper) |

---

## preview

<div class="preview">
  <style>
    .preview .light { --board: #e0e0e0; --paper: #ffffff; --title: #000000; --notes: #2f2f2f; --frame: #ffdb18; --glare: #ff65e9; --paint: #65fefe; }
    .preview .dark  { --board: #1f1f1f; --paper: #000000; --title: #ffffff; --notes: #d0d0d0; --frame: #ffdb18; --glare: #ff65e9; --paint: #2776a7; }
    .preview { display: flex; flex-wrap: wrap; text-align: center; vertical-align: middle; font-size: 1.5em; font-weight: 800; }
    .preview > div { background: var(--board); border: 0.2em solid var(--glare); border-radius: 0.5em; flex: 1 0 auto; padding: 0.5em; }
    .preview > div > div { background: var(--paper); border-radius: 0.5em; padding: 0.5em; }
    .preview > div > div > p { color: var(--notes); display: flex; justify-content: space-around; }
    .preview > div > div > p > small { color: var(--glare); flex: 1 1 1em; font-size: 0.6em; line-height: 2em; }
    .preview > div > div > p > span { flex: 1 1 9em; border: 0.2em solid transparent; border-radius: 1em; margin: 0 0.5em; line-height: 2em; }
    .preview > div > div > p > span:nth-of-type(odd) { background: var(--paint); }
    .preview > div > div > p > span > span:first-of-type {color: var(--title); }
    .preview > div > div > p.color-frame > span { border: 0.2em solid var(--frame); }
    .preview > div > div > p.plain-frame > span { border: 0.2em solid var(--notes); }
    .preview > div > div > p.color-glare > span { border: 0.2em solid var(--glare); color: var(--glare); }
    .preview > div > footer { color: var(--notes); } .preview > div > footer > u { color: var(--title); }
  </style>
  <div class="light">
    <div>
      <p class="color-frame"><small>color<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="plain-frame"><small>plain<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="clean-frame"><small>clean<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="color-glare"><small>color<br/>glare</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
    </div>
    <footer>theme mode: <u>light</u></footer>
  </div>
  <div class="dark">
    <div>
      <p class="color-frame"><small>color<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="plain-frame"><small>plain<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="clean-frame"><small>clean<br/>frame</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
      <p class="color-glare"><small>color<br/>glare</small><span><span>FILL</span> PAINT</span><span><span>NONE</span> PAINT</span></span> </p>
    </div>
    <footer>theme mode: <u>dark</u></footer>
  </div>
</div>
