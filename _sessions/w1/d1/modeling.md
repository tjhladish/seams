---
title: Modeling in Code
---

##Choosing the Right Model - General Questions
1.	What specific problem should be solved by the model?
2.	What specific questions should the model answer?  (How do we want to visualize the results?)
3.	What data set(s) will be used by the model?

- Characteristics of the Model
4.	Is it linear?
5.	Static or dynamic?
6.	Discrete or continuous?
7.	Deterministic or stochastic?

- Evaluation of the Model
8.	How stable is the model? (Is the result reproducible)
9.	How does uncertainty in input affect the output?  
10.	How do we validate the model?
11.	Is the mathematics used to model clear, concise, and understandable?

##Part A – Review the 4 simple problems below, and use the questions we discussed to recommend a mathematical model. (for similary examples, see mathmodels.org)

- Problem 1:

Programs for Computer Aided Geometric Design (CAGD) enable engineers to view a plane section of the object that they design, for example, an aircraft jet engine, an automobile suspension, or a medical device. Moreover, engineers may also display on the plane section such quantities as air flow, stress, or temperature, coded by colors or level curves. Furthermore, engineers may rapidly sweep such plane sections through the entire object to gain a three-dimensional visualization of the object and its reactions to motion, forces, or heat. To achieve such results, the computer programs must locate all the intersections of the viewed plane and every part of the designed object with sufficient speed and accuracy. General "equation solvers" may in principle compute such intersections; but for specific problems, special methods may prove faster and more accurate than general methods. In particular, general software for Computer Aided Geometrical Design may prove too slow to complete computation in real time, or too large to fit in the finished medical devices being developed by the company to the following problem.

Design a method to compute and display all the intersections of a plane and a helix in general positions (at any locations and with any orientations) in space.

(A segment of the helix may represent, for example, a helicoidal suspension spring or a piece of tubing in a chemical or medical apparatus. The need for some theoretical justification of the proposed algorithm arises from the necessity of verifying the solution from several points of view. This can be done through mathematical proofs of parts of the algorithm and through tests of the final program with known examples. Such documentation and tests will be required by government agencies for medical use.)


- Problem 2:

AIMS's cafeteria is recycling customers' uneaten food into compost (to better grow crops) by means of microorganisms. Each day, the cafeteria blends the leftover food into a slurry, mixes the slurry with crisp salad wastes from the kitchen and a small amount of shredded newspaper, and feeds the resulting mixture to a culture of fungi and soil bacteria, which digest slurry, greens, and paper into usable compost. The crisp greens provide pockets of oxygen for the fungi culture, and the paper absorbs excess humidity. At times, however, the fungi culture appears unable to digest as much of the leftovers as customers leave. The cafeteria is investigating ways to increase its production of compost. Specifically, it seeks methods to accelerate the fungi culture's activity, for instance, by optimizing the fungi culture's environment (currently held at about 120 degrees F and 100% humidity), or by optimizing the composition of the mixture fed to the fungi culture, or both.

Determine whether any relation exists between the proportions of slurry, greens, and paper in the mixture fed to the fungi culture, and the rate at which the fungi culture composts the mixture. If no relation exists, state so. Otherwise, determine what proportions would accelerate the fungi culture's activity. (A table included shows the composition of various mixtures in pounds of each ingredient kept in separate bins, and the time that it took the fungi culture to compost the mixtures, from the date fed to the date completely composted.)


- Problem 3

Most of the water flowing into the Orange River in South Africa is from Vaal River. Suppose that pollution of the rivers ceased, except for pollution from a coal mine using the Orange River for transport. How long would it take for the pollution level in each lake to be reduced to 10 percent of its present level?

Assume that 100 percent of the water in the Orange River comes from the Vaal River. It has also been determined that, each year, the percentage of water replaced in the Vaal and Orange Rivers is approximately 38 and 13 percent, respectively. Additionally, suppose that the mining company on the Orange River spills 25 units of pollutant into the river each year. Initially, there are 2500 units of pollutant in Orange River, and 3150 units of pollution in the river after 1 year.

Model this process in order to determine the Total amount of pollution in the Orange River. Does this model also predict the long-term behavior of this system?  Can you recommend pollutant policy changes based on this model?


- Problem 4:

The solid lines of the (included) map represent paved two-lane county roads in a mosquito-repellant district. The broken lines are highways. After the wet season, two trucks are dispatched from the garage on the map. Find an efficient way to use two trucks to spray repellant from the county roads. The trucks may use the highways to access the county roads.

Assume that the trucks neither break down nor get stuck and that the road intersections require no special spraying techniques. Can you generalize this to any map?

##Part B: Important Examples

(a) Agent Based Models

(Required reading in advance: (http://www.palgrave-journals.com/jos/journal/v4/n3/full/jos20103a.html))

Go through example of ABM here: (https://www.binpress.com/tutorial/introduction-to-agentbased-models-an-implementation-of-schelling-model-in-python/144)


- Problem

Two companies provided electricity to consumers and businesses until 1997 when lawmakers de-regulated the electricity market, breaking up the monopolies and opening the market to many independent suppliers.  One such supplier asks you to model the change with an Agent Based Model in order to develop a strategy to optimize his company’s profits.  Answer these questions about your model from the reading. (From: https://www.iaee.org/documents/washington/Gale_Boyd.pdf)


1.	What specific problem should be solved by the model? What specific questions should the model answer? What value-added would agent-based modeling bring to the problem that other modeling approaches cannot bring?
2.	What should the agents be in the model? Who are the decision makers in the system? What are the entities that have behaviors? What data on agents are simply descriptive (static attributes)? What agent attributes would be calculated endogenously by the model and updated in the agents (dynamic attributes)?
3.	What is the agents’ environment? How do the agents interact with the environment? Is an agent's mobility through space an important consideration?
4.	What agent behaviors are of interest? What decisions do the agents make? What behaviors are being acted upon? What actions are being taken by the agents?
5.	How do the agents interact with each other? With the environment? How expansive or focused are agent interactions?
6.	Where might the data come from, especially on agent behaviors, for such a model?
7.	How might you validate the model, especially the agent behaviors?
Review: What software/programming language is best for Agent Based Models?  What are the advantages/disadvantages of your choice?

##Part C: More Problems

(a) Consider the effects on land from the melting of the north polar ice cap due to the predicted increase in global temperatures. How would you model the effects on the coast of Ghana every ten years for the next 50 years due to the melting?

(b) What model(s) would you consider to study each of the following?  What data would you require?  Several require more than one mathematical model.  How would you integrate more than one such model?
1. transmission, spread and control of infection
2. epidemiological networks
3. spatial (geographic) epidemiology
4. persistence of pathogens within hosts
5. virulence
6. Strain (biology) structure and interactions
7. antigenic shift (different strains/viruses combine)
8. evolution and spread of resistance
9. role of host genetic factors
10. role and identification of infection reservoirs
