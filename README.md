# Infinite Outlast Battle
--------------------------------------------------------------------------

## Description:

Background:

* Infinity Outlast Battle is a game innovatively created for 4 players, where they use dice to escape, fight the zombies that are hunting them, and revive themselves until they reach the refuge at the summit of the "Lourduff Mountain"

* This project is aiming at building the "Infinity Outlast Battle" game (IOB) with Object-Oriented Design in Python, and constructing Markov Chain model in Python on the Jupyter Notebook to analyze the data of gameplay (over the gameboard with 40 cells for now), obtaining the associated <b>dominant eigenvectors</b> and <b>discovering the steady state in the long run (Markov Chains)</b> in this mechanism

![Image of Zombies Chasing Human]
(https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwie8Le10ozhAhVvUN8KHW0aBq4QjRx6BAgBEAU&url=http%3A%2F%2Fwww.melaniekarsak.com%2F2015%2F05%2Fthe-zombie-papers-hollow-men-rebooted_27.html&psig=AOvVaw3K_UiuHp3De3Bg3U1MuaiG&ust=1553031251545613)


## Gameplay

For more details and rules about the gameplay, checkout the Excel file~

Current Gameboard (ver.1.0):

![IOBgameboard](/assests/IOBgameboard.jpg?raw=true "IOBgameboard")


## Results

Distribution of the normalized dominant eigenvector:

![Normalized Dominant Eigenvector](IOB_markovchain/assests/NormDomEigv.jpg.jpg?raw=true "Normalized Dominant Eigenvector")

Probability distribution of the bite count:

* indicating the trend of how and where zombies would catch up with the players and bite

![Probability Distribution of Bite Count](/assests/ProbDistBitten.jpg?raw=true "Probability Distribution of Bite Count")

Probability distribution of death count:

* Indicating that players die geological-scatterly and rarely in the game

![Probability Distribution of Death Count](/assests/ProbDistDeath.jpg?raw=true "Probability Distribution of Death Count")


## Conclusions

If we pay more attention to the distribution of death, it is obvious that the occurrence of death is really random because we can not determine that in which round the player is dead. But More importantly, it is also interesting that players rarely die during the game (```death rate = 14/450 = 3%```, player ONLY died 14 times over playing 450 rounds, observed from the output of running the game by ```.playIOB()```). Human(players) are just too dominant in IOB. Given that this is a PVE game, players being too powerful and the game becoming more leisure and easy is just boring. That is exactly why we may need to strengthen the zombies to create more challenges for players.


## Notes

This IOB game still has lots of room to improve, gameplays, rulls, UI, associated factors contributing to the Markov Chains analysis, etc.


-------------------- Originally created by Zhe Xu --------------------
