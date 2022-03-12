 Exploring Bayensian Neural Networks
By: Connor McCambridge


## Objective

Two of the topics that interest me the most is Markov Chain Monte Carlo sampling method and neural networks, so when looking at projects to do, combining these two topics together in exploring Bayensian neural networks for a deeper understanding seemed like a natural fit. Through this exploration of these topics I want to gain a better understand how Bayensians neural networks operate and function by building and testing multiple neural networks using various MCMC sampling methods for a tranditional classification problem.

## Method

I will creating a two dimension duel moon dataset, with a class of the data making up each moon, to train and test test various Bayensian nerual networks. The neural network to be created will have two hidden layers and will use Bernoulli likehood to make the classification decision. In order to create the various distributed weighting I will be using two different traditional Markov Chain Monte Carlo sampling algorithms of Metropolis and NUTS and a newer variational inference algorithm called ADVI. 
* **Metropolis:** Metropolis–Hastings algorithm - A sampling method which generates a random walk using a proposal density and a method for rejecting some of the proposed moves. 
* **NUTS:** No-U-Turn Sampler -  A recursive algorithm to build a set of likely candidate points that spans a wide swath of the target distribution, stopping automatically when it starts to double back and retrace its steps. 
* **ADVI:** Automatic Differentation Variational Inference - Insteads of drawing samples from the posterior it fits a distribution to the posterior turning a sampling problem into and optimization problem