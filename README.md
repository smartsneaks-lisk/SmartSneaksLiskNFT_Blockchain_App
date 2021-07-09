#SmartSneaks.Lisk

_SmartSneaks is a retail shoes shop startup which Leverages the power of AI to create sneakers design and non-fungible tokens (NFT) when releasing sneakers. It has this beautiful online marketplace which includes physical shoes that are matched with digital NFTs._

#Blockchain App Code

## Inspiration

**Sneakers and non-fungible tokens (NFTs) are, seemingly, made for each other.**

Cryptographic tokens, which represent a unique asset or utility, are becoming increasingly popular as many consumers begin to invest in completely digital collectibles in fashion, art, and music. As people look for creative ways to express themselves by dressing up their digital avatars, physical fashion satisfies the desire for uniqueness and exclusivity.

With this idea in mind I have shaped the idea for a retail shoe shop startup called **SmartSneaks.Lisk** which Leverages the power of AI to create sneakers design and non-fungible tokens (NFTs) when releasing sneakers. It has this beautiful online marketplace which includes physical shoes that are matched with digital NFTs.


## How it works? - The pipeline of the project

**Artificial Intelligence**  :  If you went on Amazon, how many shoes would you find? Probably a lot right? But is there a lot of variety in them? At least in terms of sneakers, a lot of them look pretty similar. It’s time for some fresh designs. We need to evolve — what if we could generate our own shoe designs with machines here is SmartSneaks.Lisk which is helping us find the solution.
**More about AI is in last part of documentation**

**Non-Fungible Tokens**  :  Using Lisk SDK we have developed a blockchain application which will generate non-fungible tokens matched with physical sneakers. Anyone who purchases the sneakers using LSK token will also get the NFT for the AI generated digital design transferred in their name and the matched physical Sneaker.

##Generating Shoe Designs with Machine Learning

**Data.** Big retailers have boatloads of shoes for sale — Zappos and Amazon both have thousands of pictures of their shoes on their websites. So I web-scraped those pictures and stored them onto my computer, mainly targeting Nike running shoes sold on Amazon. I wrote some code to scrape these images. Luckily they were already cropped to 224 pixels by 224 pixels (which is the size needed to feed them into the model). But what kind of machine learning architecture generates things instead of looking for patterns? The answer to your question is fascinating…

![Alt text](https://miro.medium.com/max/963/1*vMpOVUhGLxWRJ3Q1dzm5xg.png)

**Generative Adversarial Networks.**  A relatively new innovation in the field of deep learning is the Generative Adversarial Network (GAN). GANs use two different networks, one that generates images of what it thinks are shoes (this is called the generator), and another that tries to distinguish between the fake shoes and real shoes from the data set (this is called the discriminator). Think of it as a Cold War between these networks, except they’re trying to outsmart each other, not out-arm each other. Once the discriminator basically can’t tell the difference between the generated images and the real images, the model has converged.

![Alt text](https://miro.medium.com/max/963/1*1Fvj3jE6zGazbdHEO1UiSg.png)

**Results.** I had the model output its generated image for every epoch to see its progress throughout the training. It mostly started as noise, with random colored pixels filling the screen, but gradually took the shape of a shoe and gained different colors to better resemble a shoe. I found it interesting that some of the shoes had the Nike logo, probably reflecting how most of the training images in the dataset were Nike running shoes.

##BlockChain Application SmartSneaks.Lisk :

- a blockchain application with

        a custom module for handling NFTs.

        a custom plugin that adds additional features for the NFTs.

- a frontend application which allows you to use and test the applications in the browser.

##After The Hype: The Future For NFTs

_When it comes to things like cryptocurrencies and blockchain technology, it’s a crazy world and NFTs have become part of it. In May, people were buying and selling an estimated 85,787 NFTs—at a total value of $5.8 million—a day, according to application tracking firm DappRadar._

**What makes an NFT special**

An NFT is a digital object—some computer code and data—that conveys ownership of something. The property could be online, like virtual real estate in some digital world or a special outfit in a video game. It might be something real: actual real estate, a painting, or seat at a concert. Then again, an NFT might be some hybrid, like the right to decide who can lease a room in a cooperative living space (something a San Francisco entrepreneur tried, though with no takers as if late May 2012).

Like any technology, NFTs can provide more efficient ways of conducting business. For example, they work with the crypto technology called blockchain—a distributed digital records ledger that doesn’t necessarily need a central system to run. Transactions can potentially happen more quickly and easily.

Second, the blockchain also keeps a record of all the transactions connected to the NFT and the property it represents. In art sales, for example, that could represent the provenance of something going back to the creator.

Third, NFTs can include what are called smart contracts, or coded elements that can automatically take actions under certain conditions. The concept is of an automated and self-enforcing set of rules that can’t be ignored or skipped.
