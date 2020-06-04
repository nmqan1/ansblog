When I was working at a Training Center during my pre-MBA career, I came across several raised eyebrows questioning the Training Center's effectiveness. In the face of skepticism, the Head of the Training Center remained calmed and showed the statistics of employee satisfaction on the course. It was always higher than 4.9/5 for each and every course offered by the center. At that moment, it was my eyebrow's turn to raise.

**So is there a way to tell if training activities are effective, besides the course satisfaction survey?**

*Answer: Yes, and here are my 2 cents in form of a long and boring blog post. *

### 1. Why course satisfaction can be misleading metrics to follow?
First, what companies look for in a training program is its ability to increase employee's capability in terms of revenue and costs. Looking into how training satisfies employees are unrelated and irrelevant in business contexts. Even when the questionnaires ask about how effective the employees *feel* about the course, these metrics are still very unreliable as people's attitude is way different from their behavior. They can find the information useful; however, they may not retrieve what they have learned and used it immediately.

Secondly, the pressure to *please* the facilitators/trainers are always present. However, not everyone ais re people-pleaser. Some survey takers are hard-to-please customers and never give a 5-star for anything. Thus, in survey analysis, differences between respondents should also be taken into accounts when using them as a basis for further recommendations.

These are the several reasons why I would recommend the different metrics to evaluate training programs: work output.

### 2. Methods

In this session, I would provide a few statistical and econometrics that can help us to evaluate the training more effectively. To better illustrate the method, throughout this part, I will use the example of a salesperson in a retail bank setting. Their outputs are usually the NPV of all customers they acquired from the beginning of the evaluating period. A secondary output is the percentage of their customer's overdue debt. For the purpose of simplicity, I will only mention the first one.

#### 2.1 T-test
**My lazy definition:** Speaking in econometrics terms, the T-test is used to test if the 2 samples drawn randomly from 2 populations have significantly different means. My lizard-brain translation: the T-test is to test if there is a difference between the two groups. This is so convenient that we can use it to see if there has been a significant improvement in salespeople who got training and who did not.

**How to run the test** Coming up next

**How to interpret the test:** Coming up next

#### 2.2 Random assignment
There is a cost to the t-test. Take this scenario as an example. The bank now have the new virtual interactive training initiative to develop salespeople softskills. The Training Center in this bank is well-known for their training methods and well-respected by all employees in the company. As we expect, too many people signed up for the course. How we are going to choose who to attend?

Some suggest choosing the best and the brightest as their superior ability to learn is the best reflection of the quality of training. Some suggest that we choosing the average performance ones because they are the best representative of the sales population. Others go with the low performers. They said that the training must elevate even the worst's performance to earn the title "effective training." Each of the reasoning has its own ground. However, none of them are scalable for a diverse salesforce. Moreover, as some logic my suggested, different groups of salespeople may respond differently to the training. How can we study all of those effect just by one wave of training trial? The answer would be *randomization.*

The nice thing about randomization is that the experiment can point out the causal relation link between the subjects under study - here it is the `training` and `performance`. One cannot simply say that the training is effective only on a population of sales (good performers who are blessed with their positive attitude at work, trainers in the cities who are blessed with the great pool of customers they are cultivating on, etc.). By randomly assigned people to the training program, Training Center can create a small sample of their diverse salesforce, investigating which population the training has most effect on and thus pivoting their program.

**How to run randomized experiment** Link to RPubs

**How to intepret the results** Link to Rpubs

#### 2.3 Adding control variables
Randomization seems to be the golden standard to study in these experiment; however, what if the organization cannot control for such thing. Take this scenario as an example. The bank now have the new in-person training initiative to develop salespeople softskills. The Training Center in this bank is well-known for their training methods and well-respected by all employees in the company. However, the course is not mandatory and only people who find it convenient take the course at the Head Quarters. Some people are willing to take a few days off work to participate, but most of the participants are from the HQ's city area. There have always been a big gap between performance in the HQ area and the performance elsewhere due to the company reuputation at its home city.

In these case, we may want to categorize the groups of participants, separate the ones who are from one city to others. At this time, you may wonder what if you think other factors like education may have different effects on the effectiveness, too. That's a great question at this point. I'll explain how to add them into what you already have in in the Rpubs.

**How to add categorical varibales in regression** Link to RPubs

**How to intepret the results** Link to Rpubs


#### 2.4 Random Encouragement Design
For the last 3 examples, we have been in a training-enthusiastic organization. How about evaluating training initiative in en organization that is less keen on these training sessions.

