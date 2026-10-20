# iWhatty · WATT3D

I build browser extensions, interactive simulations, and JavaScript libraries.
**WATT3D** is my independent workshop: useful tools, experiments you can play
with, and reusable code behind them.

[Explore watt3d.dev](https://watt3d.dev/) · [Packages on npm](https://www.npmjs.com/~whatty)

## SpellBolt

I'm the developer behind **SpellBolt**, an English spelling and grammar
extension for Chrome and Firefox. Its core language checks run on your device,
powered by [Harper](https://github.com/Automattic/harper).

My current work focuses on correction quality, keyboard interaction, and
reliable behavior across web editors.

[Chrome Web Store](https://chromewebstore.google.com/detail/spellbolt/gffpodlbapkbkdhlpcifjlefefiaccim) · [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/spellbolt/)

## JavaScript libraries

I publish small libraries for browser and application development. Several are
used in SpellBolt; each is available separately on npm.

| Package | What it does | Source |
| --- | --- | --- |
| [hotkey-router](https://www.npmjs.com/package/hotkey-router) | Keyboard shortcut routing and conflict checks | [GitHub](https://github.com/iWhatty/hotkey-router) |
| [hermes-handler](https://www.npmjs.com/package/hermes-handler) | Message routing with consistent responses, timeouts, and cancellation | [GitHub](https://github.com/iWhatty/hermes-handler) |
| [on-events](https://www.npmjs.com/package/on-events) | DOM events, delegation, and listener cleanup | [GitHub](https://github.com/iWhatty/on-events) |
| [timeout-flow](https://www.npmjs.com/package/timeout-flow) | Timers, scheduled flows, and animation-frame utilities | [GitHub](https://github.com/iWhatty/timeout-flow) |
| [nanotypes](https://www.npmjs.com/package/nanotypes) | Runtime type checks for JavaScript and TypeScript | [GitHub](https://github.com/iWhatty/nanotypes) |
| [id-dom](https://www.npmjs.com/package/id-dom) | DOM element lookup by ID | [GitHub](https://github.com/iWhatty/id-dom) |
| [text-sanctifier](https://www.npmjs.com/package/text-sanctifier) | Text normalization and cleanup of invisible characters | [GitHub](https://github.com/iWhatty/text-sanctifier) |
| [lightning-levenshtein](https://www.npmjs.com/package/lightning-levenshtein) | Edit-distance calculations for comparing strings | [GitHub](https://github.com/iWhatty/lightning-levenshtein) |

Package documentation, examples, and license terms live in the linked repositories.

## Browser experiments

[watt3d.dev](https://watt3d.dev/) brings together my physics simulations,
visual experiments, browser extensions, and npm packages.

A few places to start:

- [Prism](https://watt3d.dev/prism/) — explore light and optics.
- [Doppler Simulator](https://watt3d.dev/doppler-simulator/) — experiment with sound and motion.
- [Photon Lab](https://watt3d.dev/photon-lab/) — work with images in the browser.

## Building on shared work

Harper is an important part of SpellBolt. I'm preparing focused grammar
improvements to contribute upstream, with tests for both missed mistakes and
correct sentences that should be left alone.

I want the work on SpellBolt to improve the engine it depends on, too.
