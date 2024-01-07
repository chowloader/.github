<p align="center">
  <img src="https://raw.githubusercontent.com/chowloader/.github/main/profile/assets/logo_transparency.png" />
  <br>
  <br>
  A Mod Loader for the ChowJS (Chowdren) version of the game OMORI.
  <br>
</p>

---

## State of the project

- [x] Take control of the game startup
- [x] Custom assets loading
  - [x] Image (png)
  - [x] Audio (ogg)
  - [x] Video (webm)
  - [x] Fonts (ttf)
- [ ] Adding worker support
  - [x] Ability to create thread
  - [ ] Ability to distinct the global object from the thread
  - [ ] Functional Worker class
- [ ] Decompilation of the [QuickJS](https://github.com/bellard/quickjs/tree/b5e62895c619d4ffc75c9d822c8d85f1ece77e5b) bytecode file
  - [x] Reading bytecode properly
  - [ ] Interpreting bytecode to [AST](https://github.com/estree/estree)
  - [ ] Rearranging the full chunk to their proper file
  - [ ] Converting [AST to JS](https://www.npmjs.com/package/astring)
- [ ] Mod loading support
  - [ ] [OneLoader](https://github.com/rphsoftware/OneLoader) compatibility
    - [ ] Implement ImageDiff2
    - [ ] Same mod structure
    - [ ] Delta patching (JSON, YAML, ~~JS~~)
    - [ ] Implement all stages
  - [ ] QoL improvement
    - [x] Builtin Console
    - [ ] Easy patching of the AOT Functions and the Native Variables
    - [ ] Auto assets loading

## Support compatibility

- [x] [Switch](https://github.com/chowloader/nswitch-binary) (v1.0.3 only)
- [ ] PS4
- [ ] PC Gamepass/Steam (maybe in the future?)
