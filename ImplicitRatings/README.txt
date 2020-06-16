Implicit Ratings and Machine Learning

When computing Implicit Ratings we may want to consider a maximum number of relevant event.

We can set a threshold 𝑟𝑒𝑙𝑒𝑣𝑎𝑛𝑡𝑚𝑎𝑥 where the additional events don’t add “meaning” to the value.

We can update the formula by replacing #𝑒𝑣𝑒𝑛𝑡 with 𝑚𝑖𝑛#𝑒𝑣𝑒𝑛𝑡,𝑟𝑒𝑙𝑒𝑣𝑎𝑛𝑡𝑚𝑎𝑥𝑒𝑣𝑒𝑛𝑡. Each event can have a different threshold.

Determining the Implicit Rating value can be seen as a prediction task.

This task that we are now solving with an“empirical”method can be solved also with Classification Data Mining techniques.

Using classifiers is also commonly used for IR evaluation. We try to classify if a specific sequence of events leads to a “buy” event.