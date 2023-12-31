[**Fork this repl**][https://replit.com/@arvoids/private]So you can edit if further ***[This repl was privated on 12/10/2023]***

# Installation Guide 🔥
## ✅ Hosting Requirements
<details>
  <summary>Click to expand</summary>
  
  * [NODEjs](https://nodejs.org) version - current.
  * **VPS** would be adviced, so you don't need to keep your pc/laptop/raspi 24/7 online!
  * **replit.com** is okay-ish 
  * **Localhost** is highly recommended
  * **Github Workspaces** - can be used but they are not that reliable
  * **Google Cloud Shell** - also has the same issue
  * **Vercel** - is also okay-ish
  * **Glitch** - kill yourself
  * Or check out my friend's Host: [TRESTHOST](https://tresthost.me/). [Click here for a Direct Login Link](https://dash.tresthost.me/login)
</details>

## ENV setup
<details>
  <summary>Click to expand</summary>

  1. Save ENV in secret as -
     * `password` your permanent authtoken for PIPE
  2. Save key=value pairs in `server/server_utils/envfile.md` 
     * `key`  your key
     * `TOKEN_1` your developer token for the game
</details>

## Requirements
<details>
  <summary>Click to expand</summary>
  
 1. Run `npm i` or add missing deps manually :
 ```json
 {
   "name": "arvoids",
   "version": "2.8.0",
   "main": "utils/arvoids",
   "scripts": {
    "arvoids": "node utils/arvoids"
   },
   "dependencies": {
     "cli-table3": "^0.6.3",
     "ejs": "^3.1.9",
     "express": "^4.18.2",
     "gradient-string": "^2.0.2",
     "ws": "^8.13.0"
   },
   "engines": {
     "node": "16.x"
   },
   "license": "DBAD-License"
 }
 ```
</details>

## Configuration and Starting
<details>
  <summary>Click to expand</summary>

 > *Everything is preset so click the **RUN** button*
 ```js
 The tool menu contains everything , if you need to use some tools while the server is running , run this command -
 ./secondaryProcess.sh
 ```
</details>

# Important notes and thank ❤️
First of all, thanks for using this Source Code!
That's why I'm asking everyone to [**Join My Community!**](https://discord.gg/3TpSSkccAH)

# ✌️ Credits
> Original source code - by Taureon `https://github.com/Taureon/aps-plus-plus/`
> Other Contributors - 
<details>
<summary>

Click to view!
 
</summary>

1. Discord Server Boosting:
- 1.1 `nikitapos`
- 1.2 `omegagravitas`
- 1.3 `aekiss`

2. `MaxNest`:
- Coding help

3. `KronosEternal`:
- Bosses from their siege template

4. `pollution#7786`:
- Original code for Crowbar

5. `Raxor.io`:
- `makeOver` and `makeCross` functions (albeit slightly edited)

6. Jekyll (`zp`):
- Performance improvements

7. `Ahmetcan`:
- Code for dynamically changing tank colors and teams

8. `A23&6"#6434`:
- Helping crop several tank emojis

9. `_bagoflays`:
- Helping with bosses

10. `denisc`:
- Assembler

11. `z46`:
- The base for this template (which was made better)

12. `Woomy man`:
- Code for Rocketeer and Blunderbuss

13. `Penta0101` & `FrozenEarth`:
- The original base for aps-template

14. `Zenphia`, `Taureon`, `TOOTHLESS_SPECIAL`, `frostbvte`, `trplnr`:
- Main developers of Open Source Arras

15. `Dogeiscut`:
- Former developer of Open Source Arras

16. `CX` and `damocles`:
- Main devs of Arras.io

17. `nepphhh`:
- Inspiration for the second circle of hell

18. `M28`:
- Creator of Diep.io, without which Arras.io would never exist

</details>

> This Fork - by VOID
[![Add Me On Discord!](https://cdn.discordapp.com/avatars/820308158459019334/0b85f7b91a6b7b0e66f1751233be68c5.webp)](https://discord.gg/3TpSSkccAH)
