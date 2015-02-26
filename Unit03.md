---
layout: default
title: "MA121: Introduction to Statistics"
course_description: "An examination of the properties behind the basic concepts of probability and statistics, designed to teach you ways to investigate the relationships between various characteristics of data."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Sampling Distributions** <span id="3"></span> 
*The concept of sampling distribution lies at the very foundation of
statistical inference. It is best to introduce sampling distribution
using an example here. Suppose you want to estimate a parameter of a
population, say the population mean. There are two natural estimators:
1. sample mean, which is the average value of the data set; and 2.
median, which is the middle number when the measurements are arranged in
ascending (or descending) order. In particular, for a sample of even
size n, the median is the mean of the middle two numbers. But which one
is better, and in what sense? This involves repeated sampling, and you
want to choose the estimator that would do better on average. It is
clear that different samples may give different sample means and
medians; some of them may be closer to the truth than the others.
Consequently, we cannot compare these two sample statistics or, in
general, any two sample statistics on the basis of their performance
with a single sample. Instead, you should recognize that sample
statistics are themselves random variables; therefore, sample statistics
should have frequency distributions by taking into account all possible
samples. In this unit, you will study the sampling distribution of
several sample statistics. This unit will show you how the central limit
theorem can help to approximate sampling distributions in general.  *

**Unit 3 Time Advisory**  
This unit should take you approximately 15 hours to complete.

☐   Subunit 3.1: 8.5 hours

☐   Subunit 3.1.1: 3.5 hours  
  
 ☐   Subunit 3.1.2: 1 hour  
  
 ☐   Subunit 3.1.3: 4 hours

☐   Subunit 3.2: 6.5 hours

☐   Subunit 3.2.1: 4.5 hours  
  
 ☐   Subunit 3.2.2: 1 hour  
  
 ☐   Subunit 3.2.3: 1 hour

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   apply the central limit theorem to approximate sampling
    distributions;  
      
-   describe the role of sampling distributions in inferential
    statistics;  
      
-   interpret and create graphs of a probability distribution for the
    mean of a discrete variable;  
      
-   describe a sampling distribution in terms of repeated sampling;  
      
-   define and compute the mean and standard deviation of the sampling
    distribution of population proportion p;  
      
-   identify or approximate a sampling distribution based on the
    properties of the population;  
      
-   compare and evaluate the sampling distributions of different sample
    sizes; and  
      
-   compare and evaluate the performance of different estimators based
    on their sampling distributions.

**3.1 The Concept of Sampling Distributions** <span id="3.1"></span> 
**3.1.1 Continuous Random Variables** <span id="3.1.1"></span> 
-   **Reading: *Introductory Statistics*: “Chapter 5, Section 1:
    Continuous Random Variables, Section 3: Probability Computations for
    General Normal Random Variables, and Section 4: Areas of Tails of
    Distributions”**
    Link: *Introductory Statistics*: [“Chapter 5, Section 1: Continuous
    Random Variables, Section 3: Probability Computations for General
    Normal Random Variables, and Section 4: Areas of Tails of
    Distributions”](http://www.saylor.org/site/textbooks/Introductory%20Statistics.pdf)
    (PDF)  
        
     Instructions: From chapter 5, read section 1 on pages 204–214 and
    sections 3 and 4 on pages 225–251. Section 1 talks about how to
    describe continuous distributions and compute related probabilities,
    including some basic facts about the normal distribution. Section 3
    talks about how to compute probabilities related to any normal
    random variable. This section has many examples illustrating the
    usage of z-score transformations. Section 4 defines tail
    probabilities and illustrates how to find them. Complete the
    odd-numbered exercises at the end of each section before checking
    the answers.  
        
     Reading these sections and completing the exercises should take
    approximately 3 hours and 30 minutes.  
        
     Terms of Use: This text was adapted by The Saylor Foundation under
    a [Creative Commons Attribution-NonCommercial-Share-Alike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/) without
    attribution as requested by the work’s original creator or licensee.

**3.1.2 Definition and Interpretation** <span id="3.1.2"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 9, Section 2: Introduction”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 9,
    Section 2:
    Introduction”](http://onlinestatbook.com/2/sampling_distributions/intro_samp_dist.html)
    (HTML)  
        
     Instructions: Read section 2 from chapter 9. Also, complete the
    questions at the end. Section 2 introduces sampling distribution by
    using a concrete, discrete example, followed by a continuous
    example. This section also discusses sampling distributions’
    relationship to inferential statistics.  
        
     Reading this section and answering the questions should take
    approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.1.3 Sampling Distributions Properties** <span id="3.1.3"></span> 
-   **Interactive Lab: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 9, Section 3: Basic Demo,” “Section 4: Sample Size Demo,”
    and “Section 5: CLT Demo”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 9,
    Section 3: Basic
    Demo”](http://onlinestatbook.com/2/sampling_distributions/SampDist_v1.html)
    (HTML), [“Section 4: Sample Size
    Demo”](http://onlinestatbook.com/2/sampling_distributions/SampDist_v2.html)
    (HTML), and [“Section 5: CLT
    Demo”](http://onlinestatbook.com/2/sampling_distributions/clt_demo.html)
    (HTML)  
        
     Instructions: Watch the videos for sections 3–5 from chapter 9, and
    follow the instructions to run the simulations for each section.
    Section 3 further illustrates the concept of sampling distribution
    by using video demos. Section 4 demonstrates how the sampling
    distributions may depend on the sample sizes and the properties of
    populations. Section 5 discusses the central limit behavior when the
    sample size increases.  
        
     Completing this interactive lab should take approximately 4
    hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2 Sampling Distributions for Common Statistics** <span
id="3.2"></span> 
**3.2.1 The Sampling Distribution of Sample Mean** <span
id="3.2.1"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 9, Section 6: Sampling Distribution of the Mean” and
    “Section 7: Differences between Means”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 9,
    Section 6: Sampling Distribution of the
    Mean”](http://onlinestatbook.com/2/sampling_distributions/samp_dist_mean.html)
    (HTML) and [“Section 7: Differences between
    Means”](http://onlinestatbook.com/2/sampling_distributions/samplingdist_diff_means.html)
    (HTML)  
        
     Instructions: Read sections 6 and 7 from chapter 9. Also, complete
    the questions at the end of each section. Section 6 discusses the
    mean and variance of the sampling distribution of the mean. This
    section also shows how central limit theorem can help to approximate
    the corresponding sampling distributions. Section 7 talks about the
    properties of the sampling distribution for differences between
    means by giving the formulas of both mean and variance for the
    sampling distribution. Using the central limit theorem, it also
    talks about how to compute the probability of a difference between
    means being beyond a specified value.  
        
     Reading these sections and answering the questions should take
    approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: *Introductory Statistics*: “Chapter 6, Section 1: The
    Mean and Standard Deviation of the Sample Mean and Section 2: The
    Sampling Distribution of the Sample Mean”**
    Link: *Introductory Statistics*: [“Chapter 6, Section 1: The Mean
    and Standard Deviation of the Sample Mean and Section 2: The
    Sampling Distribution of the Sample
    Mean”](http://www.saylor.org/site/textbooks/Introductory%20Statistics.pdf) (PDF)  
        
     Instructions: Read sections 1 and 2 from chapter 6 on pages
    252–270. Section 1 presents several concrete examples to calculate
    the exact distributions of the sample mean. Based on these
    distributions, the corresponding means and standard deviations are
    computed for demonstrations. Section 2 concerns the sampling
    distributions of the sample means when the sample size is large. The
    case when the population is normal is also considered. The central
    limit theorem is used for large sample approximations. Complete the
    odd-numbered exercises at the end of each section before checking
    the answers.  
        
     Reading these sections and completing the exercises should take
    approximately 2 hours.  
        
     Terms of Use: This text was adapted by The Saylor Foundation under
    a [Creative Commons Attribution-NonCommercial-Share-Alike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/) without
    attribution as requested by the work’s original creator or licensee.

-   **Web Media: Khan Academy’s “Central Limit Theorem”**
    Link: Khan Academy’s [“Central Limit
    Theorem”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/central-limit-theorem)
    (YouTube)  
        
     Instructions: Watch this video, which explains how the central
    limit theorem can help to approximate the sampling distributions of
    sample means.  
        
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to Khan Academy, and the original version can be found
    [here](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/central-limit-theorem).

-   **Web Media: Khan Academy’s “Sampling Distribution of the Mean”**
    Link: Khan Academy’s [“Sampling Distribution of the
    Mean”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/sampling-distribution-of-the-sample-mean)
    (YouTube)  
        
     Instructions: Watch this video on the sampling distribution of
    sample means.  
        
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to Khan Academy, and the original version can be found
    [here](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/sampling-distribution-of-the-sample-mean).

-   **Web Media: Khan Academy’s “Standard Error of the Mean”**
    Link: Khan Academy’s [“Standard Error of the
    Mean”](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/standard-error-of-the-mean)
    (YouTube)  
        
     Instructions: Watch this video, which explains the standard errors
    of the sampling distribution.  
        
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to Khan Academy, and the original version can be found
    [here](https://www.khanacademy.org/math/probability/statistics-inferential/sampling_distribution/v/standard-error-of-the-mean).

**3.2.2 The Sampling Distribution of Pearson’s r** <span
id="3.2.2"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 9, Section 8: Sampling Distribution of r”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 9,
    Section 8: Sampling Distribution of
    r”](http://onlinestatbook.com/2/sampling_distributions/samp_dist_r.html)
    (HTML)  
        
     Instructions: Read section 8 from chapter 9. Also, complete the
    questions at the end. Section 8 talks about how the shape of the
    sampling distribution of Pearson correlation deviates from normality
    and then discusses how to transform r to a normally distributed
    quantity. Furthermore, this section talks about how to calculate the
    probability of obtaining an r above a specified value.  
        
     Reading this section and answering the questions should take
    approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**3.2.3 The Sampling Distribution of the Sample Proportion** <span
id="3.2.3"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 9, Section 9: Sampling Distribution of *p*”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 9,
    Section 9: Sampling Distribution of
    p”](http://onlinestatbook.com/2/sampling_distributions/samp_dist_p.html)
    (HTML)  
        
     Instructions: Read section 9 from chapter 9. Also, complete the
    questions at the end. Section 9 introduces the mean and standard
    deviation of the sampling distribution of p, and this section
    discusses the relationship between the sampling distribution of p
    and the normal distribution.  
        
     Reading this section and answering the questions should take
    approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Sophia: Tracy P’s “Determining Standard Deviation”**
    Link: Sophia: Tracy P’s [“Determining Standard
    Deviation”](http://www.sophia.org/determining-standard-deviation/determining-standard-deviation--2-tutorial)
    (Flash)  
        
     Instructions: To enhance your understanding, watch this video on
    determining standard deviation.  
        
     Watching the video several times as needed and pausing to take
    notes should take approximately 15 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


