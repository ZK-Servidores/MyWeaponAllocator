# [Retake] My Weapon Allocator

**My Weapon Allocator for splewis retakes -** https://forums.alliedmods.net/showthread.php?t=262658

This weapon allocator simulates different kinds of rounds - **FULLBUY, FORCEBUY, PISTOL, DEAGLE**.

These rounds will be set through two different modes:
- **Ascending rounds (`mywa_rounds_chance 1`) -** First x rounds will be **PISTOL**, then **x FORCEBUY rounds** after that **x FULLBUY rounds**;
- **Random rounds by chance (`mywa_rounds_chance 0`) -** It's a random chance to play **FULLBUY, FORCEBUY, PISTOL & DEAGLE rounds** in no special order;
	- **DEAGLE** rounds are only available on random rounds **(`mywa_rounds_chance 0`)** & don't give grenades.

Take a look at the configuration for a better understanding.

Player can choose their preferred weapons for these rounds through **`!guns`** menu.

The plugin will give equipments **(grenades, armor & kit)** in these rounds based of the configured money, mode & max amount of grenades.

## Credits
- [LemonPAKA](https://github.com/LemonPAKA/) - Added Simplified Chinese Translation and Zeus x27, Nova and XM1014 with the lastest version price;
- [b3none](https://github.com/b3none) - Added AWP priority system for VIP players;
- [splewis](https://github.com/splewis) - Fix minors in message when plant c4;
- [crashzk](https://github.com/crashzk) - Fix minors and update translations;
