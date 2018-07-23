# HearthstoneTextGenerator

This purpose of this project was just for me to have some fun and learn how to use Recurrent Neural Networks effectively with Keras and Tensorflow.

I based my code on this tutorial (https://machinelearningmastery.com/develop-character-based-neural-language-model-keras/) on text generation using LSTMs, but wanted to apply the same concepts on Hearthstone card descriptions. 

Even though the corpus of Hearthstone cards is relatively small, I was able to get some interesting results with a relatively small model.

Although I didn't know before starting this project, someone else has tried this in the past when there were fewer Hearthstone cards and also got interesting results (https://www.reddit.com/r/hearthstone/comments/3cyi15/hearthstone_cards_as_created_by_a_neural_network/). I hope to improve this project in the future so I card generate all features of the card, rather than just text, just as the other project did in the past. With more data to work with now, I may be able to generate even more interesting cards.

Here are some of the results. The text is generated by the RNN, but the rest is what I've filled in based on the card description.

![Alt text](cards/ravenous_crab.png?raw=true "Ravenous Crab")
![Alt text](cards/armor_upgrade.png?raw=true "Armor Upgrade")
![Alt text](cards/scourge_intern.png?raw=true "The Scourge's Intern")



