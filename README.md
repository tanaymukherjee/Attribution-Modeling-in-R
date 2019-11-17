# Attribution-Modeling-in-R
Application on Markov Chain and Removal Effect (Attribution Modeling)

As marketing moves more and more towards the consumer driven side of things, identifying the right channels to target customers has become critical for companies. This helps companies optimise their marketing spend and target the right customers in the right places.

More often than not, companies usually invest in the last channel which customers encounter before making the final purchase. However, this may not always be the right approach. There are multiple channels preceding that channel which eventually drive the customer conversion. The underlying concept to study this behavior is known as ‘multi-channel attribution modeling.’

What is Channel Attribution?
Google Analytics offers a standard set of rules for attribution modeling. As per Google, “An attribution model is the rule, or set of rules, that determines how credit for sales and conversions is assigned to touchpoints in conversion paths. For example, the Last Interaction model in Analytics assigns 100% credit to the final touchpoints (i.e., clicks) that immediately precede sales or conversions. In contrast, the First Interaction model assigns 100% credit to touchpoints that initiate conversion paths.”

Markov Chains
Markov chains is a process which maps the movement and gives a probability distribution, for moving from one state to another state. A Markov Chain is defined by three properties:

State space – set of all the states in which process could potentially exist
Transition operator –the probability of moving from one state to other state
Current state probability distribution – probability distribution of being in any one of the states at the start of the process
We know the stages through which we can pass, the probability of moving from each of the paths and we know the current state. This looks similar to Markov chains, doesn’t it?

Removal Effect
This is, in fact, an application of a Markov chains. We will come back to this later; let’s stick to our example for now. If we were to figure out what is the contribution of channel 1 in our customer’s journey from start to end conversion, we will use the principle of removal effect. Removal effect principle says that if we want to find the contribution of each channel in the customer journey, we can do so by removing each channel and see how many conversions are happening without that channel being in place.

For example, let’s assume we have to calculate the contribution of channel C1. We will remove the channel C1 from the model and see how many conversions are happening without C1 in the picture, viz-a-viz total conversion when all the channels are intact.

Reference:
https://www.analyticsvidhya.com/blog/2018/01/channel-attribution-modeling-using-markov-chains-in-r/
