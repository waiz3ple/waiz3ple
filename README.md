<!--
  ┌──────────────────────────── Design tokens ────────────────────────────┐
  │ coral    #FF6F61  primary accent on dark surfaces                      │
  │ coral-d  #D8483B  primary accent on light surfaces (passes AA)         │
  │ amber    #FF9F1C  secondary accent                                     │
  │ lime     #88CE02  highlight on dark surfaces                           │
  │ lime-d   #4F7A00  highlight on light surfaces (passes AA)              │
  │ navy     #1F2A44  surface / label background                           │
  │ ink      #0F1626  deep surface for gradients                           │
  └────────────────────────────────────────────────────────────────────────┘
  Rules: every badge uses labelColor=1F2A44; every card ships a dark + light
  variant via <picture>; no motion (animated SVGs ignore reduced-motion);
  no emoji in headings (screen readers announce them).
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0F1626,55:1F2A44,100:FF6F61&height=260&section=header&text=Wasiu%20Ramoni&fontSize=64&fontColor=FFFFFF&fontAlignY=36&desc=Accessible%20interfaces.%20Scalable%20design%20systems.%20Fast%20by%20default.&descSize=18&descAlignY=58">
  <img alt="Wasiu Ramoni. Accessible interfaces. Scalable design systems. Fast by default." src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6F61,60:FF9F1C,100:FFC56B&height=260&section=header&text=Wasiu%20Ramoni&fontSize=64&fontColor=FFFFFF&fontAlignY=36&desc=Accessible%20interfaces.%20Scalable%20design%20systems.%20Fast%20by%20default.&descSize=18&descAlignY=58">
</picture>

<div align="center">

<a href="https://ramoni.pro"><img src="https://img.shields.io/badge/Portfolio-ramoni.pro-FF6F61?style=for-the-badge&labelColor=1F2A44" alt="Portfolio: ramoni.pro"></a>
<a href="https://linkedin.com/in/ramoni"><img src="https://img.shields.io/badge/LinkedIn-in%2Framoni-FF9F1C?style=for-the-badge&labelColor=1F2A44" alt="LinkedIn: in/ramoni"></a>
<a href="mailto:wasiu@ramoni.pro"><img src="https://img.shields.io/badge/Email-wasiu%40ramoni.pro-88CE02?style=for-the-badge&labelColor=1F2A44" alt="Email: wasiu@ramoni.pro"></a>

**Frontend Engineer** &nbsp;·&nbsp; Hartford, CT &nbsp;·&nbsp; *Code with purpose, design with empathy.*

</div>

<br>

## Hello, I'm Wasiu

I build interfaces that work for **everyone**: keyboard users, screen reader users, people on slow phones, and the engineers who maintain the code after me. My work sits where three disciplines meet: **accessibility**, **design systems**, and **web performance**. I write almost everything in **TypeScript**.

```ts
type Principle = `${string} by default`;

export const wasiu = {
  role: "Frontend Engineer",
  based: "Hartford, CT",
  craft: ["Accessibility", "Design Systems", "Web Performance"],
  principles: [
    "Accessible by default",
    "Consistent by default",
    "Fast by default",
  ] satisfies Principle[],
  learning: ["Python", "PyTorch", "TensorFlow"],
} as const;
```

## How I build

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/01-Accessible_by_default-FF6F61?style=flat-square&labelColor=1F2A44" alt="Principle 01: Accessible by default"><br><br>
      Accessibility is a requirement, not a phase at the end. I build to <strong>WCAG 2.2 AA</strong> using semantic HTML first and ARIA only where it is needed. Every flow gets tested with a keyboard and a screen reader, not only with automated audits.
    </td>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/02-Systems_over_screens-FF9F1C?style=flat-square&labelColor=1F2A44" alt="Principle 02: Systems over screens"><br><br>
      Tokens, typed component APIs, and documented patterns in <strong>Storybook</strong> make the correct choice the easiest one. When the system is good, a team can ship quickly without losing consistency.
    </td>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/03-Fast_is_a_feature-88CE02?style=flat-square&labelColor=1F2A44" alt="Principle 03: Fast is a feature"><br><br>
      Performance is part of the user experience. I use code splitting and dependency audits, measure the results, and make rendering cheaper. I also treat the bundle size as a budget with a limit.
    </td>
  </tr>
</table>

## Impact

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <img src="https://img.shields.io/badge/UI_performance-%2B40%25-FF6F61?style=for-the-badge&labelColor=1F2A44" alt="UI performance improved by 40 percent"><br>
      <sub>Rendering and data-fetching optimizations at <strong>JPMorgan</strong></sub>
    </td>
    <td width="33%" align="center" valign="top">
      <img src="https://img.shields.io/badge/Bundle_size-%E2%88%9235%25-FF9F1C?style=for-the-badge&labelColor=1F2A44" alt="Bundle size reduced by 35 percent"><br>
      <sub>Code splitting, tree-shaking, and dependency audits</sub>
    </td>
    <td width="33%" align="center" valign="top">
      <img src="https://img.shields.io/badge/WCAG-AA-88CE02?style=for-the-badge&labelColor=1F2A44" alt="WCAG AA compliance"><br>
      <sub>Consistently shipped, verified manually and automatically</sub>
    </td>
  </tr>
</table>

## Open source

<table>
  <tr>
    <td valign="top">

### [Fractionability](https://github.com/waiz3ple/fractionability)

A TypeScript library for rendering **accessible fractions with MathML**, so learners using assistive technology hear math correctly instead of a sequence of symbols. It is used across **150+ educational websites**.

```bash
npm install fractionability
```

<a href="https://www.npmjs.com/package/fractionability"><img src="https://img.shields.io/npm/v/fractionability?style=flat-square&color=FF6F61&labelColor=1F2A44&label=npm" alt="npm version"></a>
<a href="https://www.npmjs.com/package/fractionability"><img src="https://img.shields.io/npm/dm/fractionability?style=flat-square&color=FF9F1C&labelColor=1F2A44" alt="npm monthly downloads"></a>
<a href="https://bundlephobia.com/package/fractionability"><img src="https://img.shields.io/bundlephobia/minzip/fractionability?style=flat-square&color=88CE02&labelColor=1F2A44&label=min%2Bgzip" alt="Minified and gzipped bundle size"></a>
<a href="https://github.com/waiz3ple/fractionability"><img src="https://img.shields.io/github/stars/waiz3ple/fractionability?style=flat-square&color=FF6F61&labelColor=1F2A44" alt="GitHub stars"></a>
<a href="https://github.com/waiz3ple/fractionability/blob/main/LICENSE"><img src="https://img.shields.io/github/license/waiz3ple/fractionability?style=flat-square&color=FF9F1C&labelColor=1F2A44" alt="License"></a>

  </td>
  </tr>
</table>

## Toolkit

<table>
  <tr>
    <td width="170"><strong>Language &amp; UI</strong></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,html,css&perline=10" alt="TypeScript, JavaScript, React, Next.js, HTML, CSS"></td>
  </tr>
  <tr>
    <td><strong>State &amp; data</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=redux" alt="Redux">&nbsp;
      <img src="https://img.shields.io/badge/Redux_Toolkit-1F2A44?style=flat-square&logo=redux&logoColor=white" alt="Redux Toolkit">
      <img src="https://img.shields.io/badge/TanStack_Query-1F2A44?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query">
      <img src="https://img.shields.io/badge/React_Hook_Form-1F2A44?style=flat-square&logo=reacthookform&logoColor=EC5990" alt="React Hook Form">
    </td>
  </tr>
  <tr>
    <td><strong>Styling &amp; motion</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=tailwind,sass,bootstrap" alt="Tailwind CSS, Sass, Bootstrap">&nbsp;
      <img src="https://img.shields.io/badge/GSAP-1F2A44?style=flat-square&logo=greensock&logoColor=88CE02" alt="GSAP">
    </td>
  </tr>
  <tr>
    <td><strong>Quality &amp; delivery</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=jest,git,github,jenkins" alt="Jest, Git, GitHub, Jenkins">&nbsp;
      <img src="https://img.shields.io/badge/Storybook-1F2A44?style=flat-square&logo=storybook&logoColor=FF4785" alt="Storybook">
    </td>
  </tr>
  <tr>
    <td><strong>Design</strong></td>
    <td><img src="https://skillicons.dev/icons?i=figma,ps,ai" alt="Figma, Photoshop, Illustrator"></td>
  </tr>
  <tr>
    <td><strong>Accessibility</strong></td>
    <td>
      <img src="https://img.shields.io/badge/WCAG_2.2_AA-1F2A44?style=flat-square&logo=w3c&logoColor=white" alt="WCAG 2.2 AA">
      <img src="https://img.shields.io/badge/WAI--ARIA-1F2A44?style=flat-square" alt="WAI-ARIA">
      <img src="https://img.shields.io/badge/ADA_%2F_Section_508-1F2A44?style=flat-square" alt="ADA and Section 508">
      <img src="https://img.shields.io/badge/Screen_reader_testing-1F2A44?style=flat-square" alt="Screen reader testing">
    </td>
  </tr>
  <tr>
    <td><strong>Currently learning</strong></td>
    <td><img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow" alt="Python, PyTorch, TensorFlow"></td>
  </tr>
</table>

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=waiz3ple&hide_border=true&border_radius=12&background=1F2A44&stroke=FF6F61&ring=88CE02&fire=FF9F1C&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FF9F1C&sideLabels=E6EDF3&dates=C9D1D9">
  <img alt="Wasiu's GitHub contribution streak" src="https://streak-stats.demolab.com/?user=waiz3ple&hide_border=true&border_radius=12&background=FFF7F5&stroke=D8483B&ring=4F7A00&fire=D8483B&currStreakNum=1F2A44&sideNums=1F2A44&currStreakLabel=D8483B&sideLabels=1F2A44&dates=57606A">
</picture>

</div>

## Let's build something inclusive

I'm open to work on accessible products, design systems, and frontend architecture. If your team wants an interface that is fast, consistent, and usable by everyone, let's talk.

<div align="center">

<a href="mailto:wasiu@ramoni.pro"><img src="https://img.shields.io/badge/Start_a_conversation-wasiu%40ramoni.pro-FF6F61?style=for-the-badge&labelColor=1F2A44" alt="Start a conversation: wasiu@ramoni.pro"></a>
<a href="https://github.com/waiz3ple?tab=followers"><img src="https://img.shields.io/github/followers/waiz3ple?style=for-the-badge&label=Follow&color=FF9F1C&labelColor=1F2A44" alt="Follow waiz3ple on GitHub"></a>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:FF6F61,45:1F2A44,100:0F1626&height=120&section=footer">
  <img alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFC56B,40:FF9F1C,100:FF6F61&height=120&section=footer">
</picture>
