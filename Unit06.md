**Unit 6: Linear Regression** <span id="6"></span> 
*In this unit, we will discuss situations in which the mean of a
population, treated as a variable, depends on the value of another
variable. One of the main reasons why we conduct such analyses is to
understand how two variables are related to each other. The most common
type of relationship is a linear relationship. For example, you may want
to know what happens to one variable when you increase or decrease the
other variable. You want to answer questions such as, “Does one variable
increase as the other increases, or does the variable decrease?” For
example, you may want to determine how the mean reaction time of rats
depends on the amount of drug in bloodstream. *  
    
 *In this unit, you will also learn to measure the degree of a
relationship between two or more variables. Both correlation and
regression are measures for comparing variables. Correlation quantifies
the strength of a relationship between two variables and is a measure of
existing data. On the other hand, regression is the study of the
strength of a linear relationship between an independent and dependent
variable and can be used to predict the value of the dependent variable
when the value of the independent variable is known.*

**Unit 6 Time Advisory**  
This unit should take you approximately 12 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.1: 7.75 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.1.1: 4 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.1.2: 2.25 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.1.3: 1.5 hours

<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.2: 4.75 hours
<span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.2.1: 0.75 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.2.2: 2.25 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 6.2.3: 1.75 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:
-   discuss and apply basic ideas of linear regression and
    correlation;  
      
-   identify the assumptions that inferential statistics in regression
    are based on;  
      
-   compute the standard error of a slope;  
      
-   test a slope for significance;  
      
-   construct a confidence interval on a slope; and  
      
-   calculate and interpret the coefficient of determination and the
    correlation coefficient. 

**6.1 The Regression Model** <span id="6.1"></span> 
**6.1.1 Scatter Plot of Two Variables and Regression Line** <span
id="6.1.1"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 2: Introduction to Linear Regression”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 2: Introduction to Linear
    Regression”](http://onlinestatbook.com/2/regression/intro.html)
    (HTML)  
        
     Instructions: Read section 2 from Chapter 14. Also, answer the
    questions at the end. Section 2 defines *simple linear regression*,
    introduces scatter plot to reveal linear patterns, and then talks
    about prediction error. This section also talks about how to compute
    regression line by minimizing squared errors.  
        
     Reading this section and answering the questions should take
    approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: David W. Stockburger’s Introductory Statistics: Concepts,
    Models, and Applications: “Regression Models”**
    Link: David W. Stockburger’s *Introductory Statistics*: *Concepts,
    Models, and Applications*: [“Regression
    Models”](http://faculty.cbu.ca/~erudiuk/IntroBook/sbk16.htm)
    (HTML)  
        
     Instructions: Read this section on regression models. This section
    elaborates more on regression models by discussing least squares
    criterion and confidence intervals.  
        
     Reading this section should take approximately 1.5 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Interactive Lab: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 3: Linear Fit Demo”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 3: Linear Fit
    Demo”](http://onlinestatbook.com/2/regression/linear_fit_demo.html)
    (HTML)  
        
     Instructions: Watch the video demo, and follow the instructions to
    launch the simulation. Section 3 is devoted to linear fit
    demonstration; this simulation allows you to change the regression
    line and examine the effects on the errors of prediction.  
        
     Completing this interactive lab should take approximately 1.5
    hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1.2 Correlation Coefficient** <span id="6.1.2"></span> 
-   **Reading: David W. Stockburger’s Introductory Statistics: Concepts,
    Models, and Applications: “Correlation”**
    Link: David W. Stockburger’s *Introductory Statistics*: *Concepts,
    Models, and Applications*:
    [“Correlation”](http://faculty.cbu.ca/~erudiuk/IntroBook/sbk17.htm) (HTML)  
        
     Instructions: Read this section on correlation. You will learn the
    interpretation and calculation of correlation coefficient,
    correlation matrix, and the relation between correlation and
    causation.    
        
     Reading this section should take approximately 1 hour.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: *Introductory Statistics*: “Chapter 10, Section 2: The
    Linear Correlation Coefficient”**
    Link: *Introductory Statistics*: [“Chapter 10, Section 2: The Linear
    Correlation
    Coefficient”](http://www.saylor.org/site/textbooks/Introductory%20Statistics.pdf)
    (PDF)  
        
     Instructions: Read section 2 of Chapter 10 on pages 485–499 for a
    discussion on linear correlation. You will learn what the linear
    correlation coefficient is, how to compute it, and what it tells us
    about the relationship between two variables x and y.     
        
     Reading this section and completing the exercises should take
    approximately 1.25 hours.  
        
     Terms of Use: This text was adapted by The Saylor Foundation under
    a [Creative Commons Attribution-NonCommercial-Share-Alike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/) without
    attribution as requested by the work’s original creator or licensee.

**6.1.3 Sums of Squares** <span id="6.1.3"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 4: Partitioning Sums of Squares”**

    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 4: Partitioning Sums of
    Squares”](http://onlinestatbook.com/2/regression/partitioning.html)
    (HTML)

     

    Instructions: Read section 4 from Chapter 14. Also, answer the
    questions at the end of the section. Section 4 further discusses the
    sums of squares, including partitioning sum of squares into sums of
    squares predicted and sum of squares error. 

     

    Reading this section and answering the questions should take
    approximately 45 minutes.

     

    Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Khan Academy’s “Squared Error of Regression Line”**
    Link: Khan Academy’s [“Squared Error of Regression
    Line”](https://www.khanacademy.org/math/probability/regression/regression-correlation/v/squared-error-of-regression-line)
    (YouTube)  
        
     Instruction: Watch this video, which talks about the squared error
    of regression line.  
        
     Watching this video and pausing to take notes should take 15
    minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to Khan Academy, and the original version can be found
    [here](https://www.khanacademy.org/math/probability/regression/regression-correlation/v/squared-error-of-regression-line).

-   **Web Media: Khan Academy’s “Regression Line Example”**
    Link: Khan Academy’s [“Regression Line
    Example”](https://www.khanacademy.org/math/probability/regression/regression-correlation/v/regression-line-example)
    (YouTube)  
        
     Instructions: Watch this video, which talks about the least squares
    estimates of both the intercept and the slope. This video also shows
    how to compute them by using examples.   
        
     Watching this video and pausing to take notes should take
    approximately 30 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to Khan Academy, and the original version can be found
    [here](https://www.khanacademy.org/math/probability/regression/regression-correlation/v/regression-line-example).

**6.2 Fitting the Model** <span id="6.2"></span> 
**6.2.1 Standard Errors of the Least Squares Estimates** <span
id="6.2.1"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 5: Standard Error of the Estimate”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 5: Standard Error of the
    Estimate”](http://onlinestatbook.com/2/regression/accuracy.html)
    (HTML)  
        
     Instructions: Read section 5 from Chapter 14. Also, answer the
    questions at the end. Section 5 discusses how to compute the
    standard error of the estimate based on errors of prediction as well
    as how to compute the standard error of the estimate based on a
    sample.  
        
     Reading this section and answering the questions should take
    approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.2.2 Statistical Inference for the Slope and Correlation** <span
id="6.2.2"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 7: Inferential Statistics for b and r”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 7: Inferential Statistics for b and
    r”](http://onlinestatbook.com/2/regression/inferential.html)
    (HTML)  
        
     Instructions: Read section 7 from Chapter 14. Also, answer the
    questions at the end. Section 7 starts with assumptions on the
    errors that are necessary for statistical inference. Then, this
    reading shows an example of a significance test for the slope. This
    section also talks about constructing confidence intervals for the
    slope. Then, it closes with a significance test for the
    correlation.  
        
     Reading this section and answering the questions should take
    approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: *Introductory Statistics*: “Chapter 10, Section 5:
    Statistical Inference about Slope”**
    Link: *Introductory Statistics*: [“Chapter 10, Section 5:
    Statistical Inference about
    Slope”](http://www.saylor.org/site/textbooks/Introductory%20Statistics.pdf)
    (PDF)  
        
     Instructions: Read section 5 from Chapter 10 on pages 520–532. This
    section further details two types of inferences on the slope
    parameter, considering both confidence intervals and hypothesis
    testing. Complete the odd-numbered exercises at the end of the
    section before checking your answers.  
        
     Reading this section and answering the questions should take
    approximately 1.5 hours.  
        
     Terms of Use: This text was adapted by The Saylor Foundation under
    a [Creative Commons Attribution-NonCommercial-Share-Alike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/) without
    attribution as requested by the work’s original creator or licensee.

**6.2.3 Influential Observations** <span id="6.2.3"></span> 
-   **Reading: Rice University: David M. Lane et al.’s *Online
    Statistics Education: An Interactive Multimedia Course of Study*:
    “Chapter 14, Section 8: Influential Observations”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 14,
    Section 8: Influential
    Observations”](http://onlinestatbook.com/2/regression/influential.html)
    (HTML)  
        
     Instructions: Read section 8 from Chapter 14. Also, answer the
    questions at the end. Section 8 discusses the notion of influence
    and describes what makes a point influential. It further introduces
    the concepts of leverage and distance, which are useful to detect
    influential observations.     
        
     Reading this section and answering the questions should take
    approximately 45 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: *Introductory Statistics* “Chapter 10, Section 8: A
    Complete Example”**
    Link: *Introductory Statistics*: [“Chapter 10, Section 8: A Complete
    Example”](http://www.saylor.org/site/textbooks/Introductory%20Statistics.pdf)
    (PDF)  
        
     Instructions: Read section 8 from Chapter 10 on pages 551–560. This
    section presents a complete example on linear regression, starting
    from presenting the data, then proceeds to a scatter plot to
    identify the linear pattern, and fits a linear model using least
    squares estimation. This reading also addresses some statistical
    inferences on both correlation coefficient and slope parameter.
    Complete the odd-numbered exercises at the end of the section before
    checking the answers.  
        
     Reading this section and completing the exercises should take
    approximately 1 hour.  
        
     Terms of Use: This text was adapted by The Saylor Foundation under
    a [Creative Commons Attribution-NonCommercial-Share-Alike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/) without
    attribution as requested by the work’s original creator or licensee.

**6.3 ANOVA (Optional)** <span id="6.3"></span> 
*This optional subunit will teach you about “Analysis of Variance"
(abbreviated ANOVA), which is used for hypothesis tests involving more
than two averages. ANOVA is about examining the amount of variability in
the* y *variable and trying to see where that variability is coming
from. You will study the simplest form of ANOVA, called single factor or
one-way ANOVA. Finally, you will briefly study the* F *distribution,
used for ANOVA, and the test of two variances.*

-   **Reading: Rice University: David M. Lane et al.’s Online Statistics
    Education: An Interactive Multimedia Course of Study: “Chapter 15:
    ANOVA”**
    Link: Rice University: David M. Lane et al.’s *Online Statistics
    Education: An Interactive Multimedia Course of Study*: [“Chapter 15:
    ANOVA”](http://onlinestatbook.com/2/analysis_of_variance/ANOVA.html)
    (HTML)  
        
     Instructions: Read this chapter and complete the questions at the
    end of each section. While these sections are optional, studying
    ANOVA may help you if you are interested in taking the
    credit-aligned exam that is linked with this course.  
        
     Reading these sections and answering the questions should take
    approximately 3 hours.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Khan Academy’s “ANOVA 1: Calculating SST (total sum of
    squares)”, “ANOVA 2: Calculating SSW and SSB (total sum of squares
    within and between)”, and “ANOVA 3: Hypothesis test with
    F-statistic”**
    Link: Khan Academy’s [“ANOVA 1: Calculating SST (total sum of
    squares)”](https://www.khanacademy.org/math/probability/statistics-inferential/anova/v/anova-1---calculating-sst--total-sum-of-squares),
    [“ANOVA 2: Calculating SSW and SSB (total sum of squares within and
    between)”](https://www.khanacademy.org/math/probability/statistics-inferential/anova/v/anova-2---calculating-ssw-and-ssb--total-sum-of-squares-within-and-between--avi),
    and [“ANOVA 3: Hypothesis test with
    F-statistic”](https://www.khanacademy.org/math/probability/statistics-inferential/anova/v/anova-3--hypothesis-test-with-f-statistic)
    (YouTube)  
      
     Instructions: Watch these videos, which discuss each of the steps
    in ANOVA. While these videos are optional, studying ANOVA may help
    you if you are interested in taking the credit-aligned exam that is
    linked with this course.  
        
     Watching these videos and pausing to take notes should take
    approximately 45 minutes.  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0 United States
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/). It
    is attributed to the Khan Academy.

**Final Exam** <span id="7"></span> 
-   **Final Exam: The Saylor Foundation’s “MA121 Final Exam”**
    Link: The Saylor Foundation’s [“MA121 Final
    Exam”](http://school.saylor.org/mod/quiz/view.php?id=1735)  
        
     Instructions: You must be logged into your Saylor Foundation School
    account in order to access this exam.  If you do not yet have an
    account, you will be able to create one, free of charge, after
    clicking the link.  
      
     **Note**: This exam has been designed as a *practice exam* for both
    the credit bearing StraighterLine **Introduction to
    Statistics** **MAT202** exam, and the Thomas Edison State
    College **Principles of Statistics (STA-201-TE)** TECEP exam.  
      
     You can register for the StraighterLine
    exam [here](http://Straighterline.7eer.net/c/84609/110805/1322).
    Please note that unlike The Saylor Foundation practice exam for this
    course, which is free, the StraighterLine version will cost
    **$25.00**, plus a **$99.00** montly subscription fee. Passing this
    exam will make students eligible for **3 hours** of college credit,
    transferrable to numerous colleges and universities.  
      
     You can register for the
    TECEP exam [here](http://www2.tesc.edu/tecep.php?CourseCode=STA-201).
    Please note that the TECEP exam will cost **$102.00** for in-state
    New Jersey residents, or **$108.00** for out-of-state/international
    students. Passing this exam will earn students **3 hours** of
    college credit, which can be applied to a Thomas Edison State
    College degree program, or potentially transfered to another
    college.  
      
     To read more about the partnerships with StraighterLine and Thomas
    Edison State College, and to learn more about credit transfer
    opportunities and procedures for this course,
    go [here](http://www.saylor.org/student-credit-pathways).


