# DKBManualAP
A manual Archipelago implementation of Donkey Kong Bananza.

Locations are Banandium Gems, and Fossils, if enabled. Items are keys that unlock sublayers, skills, outfits, Record Fragments that unlock Bananzas and Banandium Gems that unlock the final boss.

This game expects you to have a savefile that has reached the Warp Gong in Planet Core without collecting any Banandium Gems or Fossils. Make sure to copy it before playing, so you don't have to do it again!

You start the game with access only to SL100, other sublayers must be unlocked by finding Layer Keys. Each Layer Key unlocks one sublayer in its respective layer, starting from the top. You may not enter inaccessible sublayers, except to use the Warp Gong. In addition, the following actions require their respective items:
 * Entering a Challlenge Course.
 * Entering a Battle Challenge.
 * Completing a Shifty Smash.
 * Interacting with a Growtone.
 * Interacting with a Quiztone.
 * Interacting with Cranky Kong.
 * Using any kind of shop.
 * Completing Fragmentone challenges.
 * Completing Seekertone challenges.
 * Helping a Bloomintone.
 * Paying Constructones.
 * Paying Architectones.
 * Paying Securitones (however, the logic expects you to have already paid for the main Forbidden Layer Securitones to reach the Planet Core).

You may not buy skills or outfits unless you have been sent the respective item.

Bananzas are unlocked by collecting Record Fragments. Every 10 Record Fragments, you will unlock a new Bananza, in a random order (this can be changed in the yaml settings).

To win the game, collect your required number of Banandium Gems and face K.Rool.
