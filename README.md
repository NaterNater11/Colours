An adventure game that involves multiple fights, each with different attack patterns, and results in multiple endings

    Libraries Used

1.) Random (built into Jupyter)

Generates random numbers that changes attack patterns slightly

2.) Time (built into Jupyter)

Delays code, so text stays longer.

3.) Pickle (built into Jupyter)

Stores endings found; allows information to be remembered and displayed in final area

4.) PyGame (pip install pygame or pip3 install pygame)

PyGame is a popular library for game creation, and a suggestion from my instructor. I used its UI systems and button features for a more engaging experience. Learn more at https://www.pygame.org/wiki/about


    Basic Description

Running cells opens a PyGame window, the user operates an indigo circle that navigates a world fighting other colours of the rainbow. You can obtain items (3 coins, stick, string, arrow, dagger, and create a bow) that can alter the outcome of the game. The opening screen posses a hidden, followed by the introductory grey square that can grant the player a stick. The first enemy level is Blue which attacks with a flooding attack, upon completion moving upwards reveals to another coin that can be obtained by platform jumping. Alternately, moving rightwards on the Blue level loads the next enemy, Orange, who gains increasing amounts of vertical beam attacks. Green follows Orange and can summons a wave, this enemy cannot be damaged until they are weakoned with a potion and if killed or poked with a stick, they will drop another coin. Next, Yellow is encounter and will intially offer a shop consisting of (String, Arrow, Dagger) each item increases in value of one coin, with the intial starting at one coin. Yellow's attack consists of a quick horizontal beam, once defeated, the player encounters the Red enemy that randomly generates three spikes, one of which slowly descends. Finally, the player encounters the violet enemy and they use Blue's flood attack paired with two bouncing sqaures that can spawn low or high. The fight can end multiple ways, if the player possesses a bow and arrow they can finish Violet off, if they possess the dagger they can spare violet, otherwise violet runs away, any of this allows the player to travel to trophey area. The trophey area displays all endings discovered, all squares all, all squares dead, a combination of those two, or finally the player died before finishing the final fight.


    Localized code

Orginally, I wanted to write universal function that could be called for each enemy; however, my skill level starting this project wasn't high enough. Instead I wrote several components of code repeatidly for each indivdual cell, with my enhanced skills from writing this program, I could write more efficient code utilizing a function that incorporates all repeated features


    Future Work

As mentioned before, I could write a function that absorbs most repeated lines from all cells

My hitboxes for attacks are functional; however, most are not alligned correctly and need to be altered for a more balanced experience


    References

My understanding of PyGame greatly aided in the production of my project, though I would refered to my previous PyGame project https://github.com/NaterNater11/TicTacToe and the tutorial on https://www.pygame.org/docs/index.html

I found instructions for pickle, a library I never used before, and built my knowledge of its capabilities https://www.askpython.com/python/examples/save-data-in-python
