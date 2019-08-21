---
title: 
layout: post
weight: 10
hidden: true

---

===

**Course**: DS  <br/>
**Mod**: Mod 3 V2              <br/>
**Topic**: Statistics   <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Laura Colon Melendez

------

#### Lesson Summary:

This lesson begins by asking students to describe the parameters that characterize a normal distribution and to discuss the empirical rule. Students use numpy, matplotlib and seaborn to create histograms of normal distributions. From there, the standardized normal distribution is discussed and students are asked to standardize normally distributed data. After discussing the standard normal distribution, students should discuss why the standard score is a useful statistic. Using a real world dataset, students compute z-scores from values and convert z-scores to values. The remainder of the lesson is spent discussing statistical testing with z-scores. Students are presented with conceptual questions relating to statistical testing with z-scores and p-values. Then, students are asked to compute the probability of observing values given some z-scores. Then they perform two-sided and one-sided z-tests for data provided to them (at significance level alpha = 0.05), after stating null and alternative hypotheses. 


#### Topic:

Statistics

#### Learn.co material:

[The Normal Distribution](https://github.com/learn-co-curriculum/dsc-normal-distribution)

[The Normal Distribution - Lab](https://github.com/learn-co-curriculum/dsc-normal-distribution-lab)

[The Standard Normal Distribution](https://github.com/learn-co-curriculum/dsc-standard-normal-distribution)

[The Standard Normal Distribution - Lab](https://github.com/learn-co-curriculum/dsc-standard-normal-distribution-lab)

[Statistical Testing with z-score and p-value](https://github.com/learn-co-curriculum/dsc-z-score-p-value)

[One-Sample z-test](https://github.com/learn-co-curriculum/dsc-one-sample-z-test)

[One-Sample z-test - Lab](https://github.com/learn-co-curriculum/dsc-one-sample-z-test-lab)

#### Prerequisite knowledge/ Prework:

- Probability Mass Function
- Probability Density Function
- Cumulative Distribution Function
- Matplotlib/Seaborn

#### Prerequisite Learn-Materials:

The Normal Distribution

The Standard Normal Distribution

Statistical Testing with z-score and p-value 

One-Sample z-test 

#### Learning goals for this lesson: 

* Students understand the parameters that characterize normal distributions.
* Students can create and visualize normal distributions using python packages. 
* Students can interpret the standard score of an observation from normally distributed data.
* Students know how to standardize normal distributions. 
* Students can define the significance threshold $\alpha$ and its relation to p-value. 
* Students can define null and alternative hypotheses, and when they're used. 
* Students can use scipy methods to compute the p value of a z-score and are able to interpet the significance of results. 
* Students understand and can perform 1-sample z-tests, and can grasp the difference between one-tailed and two-tailed tests.  

Relevant learning goals from Airtable: 

* STATS.1.reciYiC4vK7aKGRCT
* STATS.2.recORKK38my4swtmL
* STATS.2.recIzN5QlRt2r0zI0
* STATS.1.rectZoS9UoFw5ObOg
* STATS.2.rectRn2aXy6LI0pic
* STATS.2.rec8TcJZWGKnZgSrt
* STATS.2.recDJOzhZKK1CMOT8
* STATS.1.recweFFOl0Q5C25gR
* STATS.1.recjWs1mozKc8vk3n
* STATS.2.rec6NxRq6RuKsoRTa
* STATS.2.recfIY1ZWVlluxS3R
* STATS.2.recsuc3zv5m22wnyj
* STATS.2.recjK35EV0FbtLKqk

#### Misconceptions / Notes

* Computing two-tailed one-sample z-tests may cause confusion.  

#### Materials

- Ipython notebook

#### Vocab / Concepts 

standard score

#### Lesson Outline:

* Normal distribution (10 minutes) 
    * Students describe the characteristics of a normal distribution and the empirical rule  
    * Applied practice:
        * numpy, matplotlib, seaborn
        
* Standard normal distribution (5-10 minutes)
    * Students compare normal distribution and standard normal distribution  
    * Students explain how to transform a normal distribution to a standard normal distribution. 
    * Applied practice: 
        * Students standardize the normal distribution they created in the previous section and plot the `distplot` with seaborn.
        
* Standard score (5-10 minutes)
    * Motivate discussion about z-scores: they let you understand how extreme a measurement is compared to the rest  
    * Applied practice:
        * A real-world dataset is brought in using pandas. 
        * Students create and plot distribution using numpy and seaborn. 

* Statistical testing with z-scores and p-values (20-25 minutes)
    * A big chunk of this lesson should be spent discussing concepts around statistical testing:
        * Samples and populations
        * Computing probabilities of observations
            * A conceptual problem and applied problem are presented to test students' understanding. 
            * Cumulative distribution function: `scipy.stats.norm.cdf` 
        * Statistical hypotheses and hypothesis testing
        * One-sample z-test
            * z-statistic: denominator: _sample variance_
            * Spend some time explaining the statement of null and alternative hypotheses but do not dwell too much (more than 5 minutes) on this part. Hypothesis testing will be explained more in depth in Section 20. 
            * One-tailed vs two-tailed one-sample z-tests **
            * Discuss the importance of $\alpha$ (significance level) as a threshold.
    * Applied examples of computation of one-sample z-test results are presented before conceptual discussion of p-values and significance threshold. These are meant to motivate the discussion. 


* Summary (10 minutes)

0-5 minutes wiggle room.