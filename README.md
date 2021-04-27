# Dynamical_System_Project
Project on dynamical system
Title: The Dissemination of Misinformation and Truth in our Society

In our day to day lives, we get fed limitless information from all around the world. 
In this project, we would like to explore how misinformation can spread through a society,
and what factors can play into limiting the spread of misinformation,
or the spread of the truth within our society.We are still researching which factors we should most critically consider in our model,
but we aim to perform an analysis and visualization of the flow of misinformation.
Hopefully, we will discover critical thresholds at which our system exhibits a change of behaviour
(for example, perhaps, at which point misinformation will overtake the truth in a society).
This project will further explore how society interprets information and the likelihood of their change in viewpoints.
We plan to construct our model similar to the SIR model for disease transmission. Except, in our case,
it would be misinformation transmission. Although that could change as we research more.

Introduction
Hello everyone. Welcome to our presentation. Today we’re going to be talking about the spread of misinformation on social media. 

Questions
Misinformation is a big issue in our current society. Bad actors stand to benefit from the ad-based internet generating clicks based on shocking, angering, and entertaining headlines, even when they are false. We were interested in this topic, and analyzing how misinformation can spread throughout a population --especially online and through social media. 

These are some of our big questions we would like answered regarding misinformation by our SIR style model. Most relevant to our society, How can we eliminate fake news in a population?  

SIR Model
For those of you who don’t know what the SIR model is, it’s an epidemiological model that theoretically calculates the number of people infected with a contagious illness (like a virus) over time. Susceptible people may be Infected once, and then Infected people may become Recovered. In the base model these are the only population changes that may occur.

We chose to imagine misinformation as the Virus since, this misinformation can also spread rather quickly and from person-to-person contacts through sharing and engaging with posts on social media. 

However, in our model regarding misinformation, we took into consideration two additional relationships. 
People who were Recovered (believed in the Truth) can be Infected again (convinced into believing Misinformation)
And, people are able to skip the Infected phase of believing in Misinformation, so that an individual can go directly from Uninformed, or Ignorant on a subject to believing in the Truth

So to recap, our model is: 
S(t) = Uninformed (Susceptible) population
I(t) = Misinformed (Infected) population
R(t) = Truth (Recovered) population
And the sum of these three groups make up our total population

Graph - Equalization:
From this graph with the following parameters, we can see that we’ll reach a stable solution where 50% of the people believe in the truth and the other 50% believe in the misinformation.

Graph - Troubling News:
In this next plot, we can see that fake news spreads 6 times faster than the truth which is very troubling for society. 

Graph - Misinformed < Truth:
From those ideas people will be more likely to be convinced of the truth and less likely convinced of misinformation. Eventually there will be a point where the whole population will be convinced of the truth
