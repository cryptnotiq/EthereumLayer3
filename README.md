# EthereumLayer3
<strong>A proposal for giving tokens real value by solving underlying issues with current dapps</strong>

Note to readers
This paper is just my ideation. Please comment, critique, contribute, and explore. 

<strong>Background</strong>

While many people are skeptical of the value proposition of tokens, there is an interesting paper published by Edward de Bono from the early 1990s, called “The IBM Dollar.” This paper suggests that all companies (he uses IBM as the prime example in his paper) should issue their own currency instead of stock. He goes on to explain the immense value and benefits it provides companies with over issuing equity. 

There are two things that technologists always do: 1)They overestimate how quickly adoption will happen.
2)They underestimate the impact a new technology will have on society.

De Bono’s paper is a very interesting case because he seems to be forecasting what is happening with ICOs, but in his paper uses only old world examples of how a company specific currency could be implemented and offer value which he was accustomed to at the time he wrote this paper several decades ago. Going off of his ideology and what is happening with token-based companies in today’s blockchain ecosystem, I believe we have been approaching the usage and the process of deriving value from tokens in the incorrect manner. This paper suggests an alternate solution to how we utilise tokens to operate open source projects.

<strong>Abstract</strong>

Decentralised applications (layer 3) do not need tokens to function. Tokens can be engineered into their business model or application logic; but they are not a necessity unlike in Layer 1 technologies such as Ethereum and Bitcoin where validators need to be incentivised to maintain an actual blockchain network. Even layer 2 technologies have an argument that tokens may be needed because they are in themselves another form of chain, one that requires less security and in exchange offers more transactional, computational, or communicative capacity.

Tokens are an incentive structure. Many have said that they provide immense value because they have been the most effective method of monetising open source projects thus far in history. However, the ICO boom, which monetised primarily layer 3 applications, is not sustainable with the current implementations of token usage across decentralised applications.

In this paper I suggest that we are looking at token models for layer 3 (dapps) all wrong. Tokens should not be designed to integrate into the application itself. Instead they should be used to govern and control the product ecosystem and reduce reliance on core, centralised teams; leadership; and decision making which can be generalised and labelled as Governance.

<strong>Introduction</strong>

Currently, altcoins for dapps (layer 3) do not have <strong>necessary</strong> utility, they are purely speculative. Instead of finding a true utility, it is engineered via token economics in an attempt to sustain an argument that a specific altcoin derives its value from utility (which is also a legal argument for not being classified as a security).

Dapps should be focused on providing value based on offering a service that people want to use, and attracting users. Not by engineering value via creative token economics.

To move forward constructively we need to agree that tokens <i>can</i> be used in dapps, but they are completely unnecessary, except possibly in edge case scenarios, for the dapp to function. In fact, integrating a token just adds unnecessary complexity which even further overcomplicates an already difficult dapp user experience where users need a web3 plug in, such as metamask, and Ether to pay gas costs. Having a second token required to use the dapp is not the way we should be approaching this.

Now this is not to say that common methods to increase value, such as token burning, are bad, but at their core they are really just a modern version of a share buyback. This can be completed without integrating a token into an application. Excess fees or a portion of fees (in ETH) can be used to purchase tokens via a decentralised exchange such as Kyber and burnt. This can all be automated with a smart contract set-up where anyone can call the functions to execute the contracts. 

In summation, tokens do not have a solid market fit within the layer 3 applications and cannot be expected to sustainably increase in value or even hold their value if their only use is within a dapp.

Next I want to briefly touch on the shortcomings of current dapps.

1. Dapps are actually highly centralised. Just like the saying in encryption, your security is only as strong as your weakest link, the same holds true with dapps. Regardless of how trustless, permissionless, and decentralised the infrastructure is, nearly every decentralised project relies on a centralised team, decision making, leaders (who take ownership aka responsibility for the project), financial control, and governance model.

2a. DAOs are a step towards decentralising the governance model and decision making. However, they have poor engagement and voter turnout. This is due to a poor incentive structure. It is human nature to strive for instant gratification. In DAOs, the incentive is indirect. A user holds tokens for a project or is otherwise a stakeholder that will benefit from its success. They make decisions, hoping that their engagement affects the future value of what they stand to benefit from. This doesn’t encourage people to participate. So instead of trying to change human nature, let’s focus on changing the incentive structure to something more direct. 

2b. Additionally when you migrate away from a core team via a DAO or other decentralised mechanism, leadership and ownership becomes a large issue. Even if people do not necessarily need to look up to a leader for guidance to move a project forward, there needs to be an easy way to take ownership in a project and for stakeholders to have a level of responsibility. This is mainly an organisational issue that may be easily resolved via ERC721 positions - which I will expand more on later in this paper.

The rest of this paper is my proposal for how tokens can be actually be used to address these shortcomings.


<strong>Real Token Utility</strong>

Layer 3 tokens should be converted into Governance Tokens with a staking type mechanism that rewards users based on participation and penalises them for inactivity and foul behavior. Instead of users holding their tokens for speculative purposes to convert into more Bitcoin, ETH, or fiat, this model encourages them to participate. This solves both the token problem of not having a utility and solves the DAO problem of lack of user engagement and as a result enables projects to truly become decentralised. 

The proposed model would function as follows:

a. Users stake their tokens within the governance mechanism (let’s call it a DAO).

b. There is an annual inflation of tokens (say 10% for this example) which is allocated proportionately to participants who have their tokens staked in the DAO.

c. If a participant of the DAO is inactive for a period of time (say 30 days), where they failed to vote on any proposal, issue a proposal of their own, or any other function of the respective DAO, all of their staked tokens are burnt.

d. Users can unstake their tokens at any time, but there is an unlocking time (say 14-21 days) before they have access to their tokens and during this unstaking time they do not receive staking rewards.

This model is designed to incentivise engagement by both offering a reward for participating in the DAO via staking rewards, and a penalty for not being active with burning or slashing of token balances. The staking reward is also only distributed to participants of the DAO so it encourages every token holder to join the DAO or their holdings will be losing value because of the inflation and not receiving any staking rewards from it.

<strong>Decentralised Ownership and Responsibility</strong>

Relying on a centralised team is one of the largest flaws of current decentralised applications. However, it is nearly impossible to keep a project progressing in a positive direction without having accountability. If a core team is removed from the equation, and a project solely relies on contributions from open source contributors or bounty hunters, there is a lack of responsibility which ultimately leaves the project vulnerable to hitting severe roadblocks in development or not solving critical issues because no one individual feels that it is there responsibility, unlike if someone is employed by the centralised company for the dapp and knows what their responsibilities are. Therefore, I am not proposing that positions be eliminated, but rather that the positions are governed in a decentralised manner and not from a centralised parent company. 

The model could look something like this.

a. Key positions are identified and approved via a DAO proposal.
I.e community manager, moderators, social media manager, security lead, bounty manager, development lead/support, code curator for reviewing bounties, etc.

b. Each position is given a compensation amount - specific % of the staking rewards
In addition to receiving staking rewards from participating in the governance model (DAO from previous example), ecosystem positions could also be integrated to receive a portion of the staking profits. For example, if the staking yield was 10% per annum, 5% could be allocated towards DAO participants and 5% could be distributed to ecosystem positions, or any combination.

c. Positions are voted on via the DAO, and can also be removed via a vote.
Note (open for suggestions): Need to analyse the security of this and come up with a model to secure this process.

What this process is designed to do is keep the key positions and level of responsibility and accountability consistent with that of a centralised team, but without relying on a centralised company. 

<strong>Approaches and Limitations (Please Comment and Discuss any and all of the below points)</strong>

1. There needs to be an economic model where the demand for the token is greater than the Rate of inflation or the token will only decrease in price. If demand is purely from token buybacks from application usage then the formula is simple. Tokens burned from application fees need to exceed tokens issued fir staking rewards.

2. For this model to truly take off there needs to be a plug and play solution where any project can plug in their tokens and use the governance, if a token swap is required for each project that is very messy and risky and does not seem like the right approach. 
However, if a token swap is not completed and a plug n play solution is used, staking rewards will need to be a secondary token because most projects will be unable to mint additional tokens or have the right contracts in place for this to function appropriately. While having a universal reward token seems like the best solution, there needs to be a demand for this token or it will be worthless because the market will be one-sided with only sellers.

3. Voting Models, Voting Power, Delegations: Not limiting votes to identity and instead 1 token 1 vote can lead to hostile takeovers and unfair votes, gaming the system, etc. But also limiting votes can reduce incentive for purchasing more tokens. Money shouldn’t buy votes, but more votes earned from participating in a beneficial way should be hugely prioritised. Delegation of votes should also be a potential option because it handles scale. If there thousands of stakeholders it cannot be expected that they all will vote, but if there are 100 delegates who are chosen in a form of liquid democracy (where they can also be removed very quickly) and votes can be allocated to them then it may handle scale and keep operations efficient, while still keeping a reasonable level of decentralisation.


Please share your thoughts and join https://t.me/OpenDeFi to discuss any ideas :)
