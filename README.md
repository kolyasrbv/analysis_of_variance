# analysis_of_variance

**Tasks**
- Choose the method that you think will fit in the first question.
- Check if the variances within the groups are homogeneous.
- Test for normal distribution.
- Compare the averages in the presented groups.
- Use Tukey's test and determine which groups have statistically significant differences.
- Make a decision: what pictures will we end up using?
- Choose a method for the second test.
- Visualize the distribution of events for the control and test groups.
- Look at the descriptive statistics of events by group and by user segment.
- Choose a formula for the model, run a test.

**Data description**

*test_1*
- id - id of the client in the experiment
- group - in what resolution images were shown (A - rectangular 16:9, B - square, C - rectangular 12:4)
- events - how many dishes were ordered in total for the period

*test_2*
- id - id of the client in the experiment
- segment - segment (high/low)
- group - button type (control - old version, test - new version)
- events - how many dishes were ordered in total for the period
