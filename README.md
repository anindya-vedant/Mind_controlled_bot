# Mind_controlled_bot
As a sem project made a bot which can be directed using EEG signals from a NeuroSky Mindwave Mobile device.

I used NeuroSky Mindwave Mobile device to read the EEG signals of a user.
![Neurosky Mindwave Mobile](https://images-na.ssl-images-amazon.com/images/I/71zoF122ogL._SL1500_.jpg)

To get the data run the <code>Program.cs</code> file in the rawdata folder.

Detailed description on how to connect the bot is given in the <code>Instructions</code> word file

So the way this works is it uses the c# script to read the EEG signal values into the laptop, then the values are fed into a pre-trained [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) so that the LSTM network could classify it into 4 categories namely, forward, backward, left and right.
