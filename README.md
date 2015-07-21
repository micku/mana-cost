# mana-cost
A simple CSS based on [Goblin Hero's vecor mana symbols](http://www.slightlymagic.net/forum/viewtopic.php?f=15&t=4430) for Magic: The Gathering.

This is usefull for web applications.

## Usage
Simply grab the SVG found in `images/` and the CSS found in `css/`, then start using the `.mana` class.

Classes are named to reflect the mana costs of [mtgjson](http://mtgjson.com/), with only alphanumeric chars.

For example:

    {1}{W/U}{W/U}

Can be translated in:

    <span class="mana medium s1"></span>
    <span class="mana medium swu"></span>
    <span class="mana medium swu"></span>

## Notes
This can not be considered as tested, I wrote this in a hour of free time and plan to use in a future project. Any comment, issue report or pull request will be appreciated!

I have not yet included large styles for not square icons.
