# 🔮🚀 New Prediction v1.0

The bot that uses martingale system.

## ⭐Please consider giving a **star**.



## 🐰⚡ Installation

Download and Install Node here:
https://nodejs.org/en/download/

Then run the following commands in terminal:

1. ``git clone https://github.com/CrytoA/PancakePredictionBot.git`` 


## ⚙️ Setup

1. Open the **.env** file with any code/text editor and add your private key like so:
```
PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
```
3. Open the **bot.js** file and setup the following variables:
```
INIT_BET: 0.005,    // initial bet amount after winning (In BNB)
START_BET: 0.005,   // bet amount when starting bot (In BNB)
TIME_TO_NEXT: 5,    // betting time before starting next round (seconds)
```
4. Start the bot using `npm start` or `yarn start`
5. 🔮 Enjoy!

### 🔓 How to convert seed phrase to Private Key
A lot of wallets don't provide you the private key, but just the **seed phrase** ( 12 words ). So here you will learn how to convert that to a private key:
1. Enter [Here](https://youtu.be/eAXdLEZFbiw) and follow the instructions. Website used is [this one](https://iancoleman.io/bip39/).

![Winning rate](/img/rate.jpg?raw=true)


## 🤖📈 Strategy
    This bot uses famouos Martingale betting system. If lose, bet 2x of past amount, If win, bet initial amount
    This does not mean blindly betting up or down. For example, if you keep betting only on up, the amount of bets increases tremendously because you don't know when it will go up in a situation where the bnb price continues to fall. So this bot bets on the next round as the result of the current round. In other words, if the current round ends on down, you bet on down assuming that there is a high probability of a down in the next round. In my experience, the number of up and down swaps never exceeded 10 at most. It was a worthwhile experience. So I decided to implement this as a bot.


💰You can check the history of rounds and claim rewards here: https://pancakeswap.finance/prediction

## 👁️ Tips
Of course, this bot's strategy isn't all-around, and it's not without risk.
    
Rather than running the bot all day, it was more advantageous to run the bot for 2-3 hours by increasing the initial bet amount by taking the time when the current bnb price fluctuates greatly.

🎯 Goal
In the future, I will continue to upgrade the bot to become more intelligent, stable and the best by adding the ability to automatically turn the bot on and off by predicting times when the bnb price fluctuates significantly.

If you have a better idea, share it and move forward.

wishing you luck