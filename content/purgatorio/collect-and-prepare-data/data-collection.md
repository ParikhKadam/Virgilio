---
title: Data Collection
author: neomatrix369
description: The purpose of this guide is to talk about data collection and the different steps you need to do to prepare your dataset even before we can think of Machine Learning models and the works.
---

# What you will learn 
The real world data is full of data, there are many types of data and collecting them is an art.

Also this is one of the preliminary steps when you are about to do Machine Learning or Deep Learning or any of the AI things. The cascading steps or processes depend quite a bit on this task but at the same time, this is a task that can be iterated a number of times.

And revisited depending on what we conclude or find in the subsequent steps and processes (you can look at the index to see what these steps are). 

We will also introduce a flow diagram eventually to show you where in the flow this task/step sits.

The purpose of this guide is to show you the importance of these steps, but also how important data collection can be in the whole cycle.

# Index
- [How to use this guide?](#How-to-use-this-guide)
- [The process](#The-process)
- [Research or business questions](#Research-or-business-questions)
- [Start Small](#Start-small)
- [Small steps](#Small-steps)
- [The Toolkit and sources](#The-Toolkit-and-sources)
- [Datasets](#Datasets)
- [Data Generation](#Data-Generation)
- [Visualisation](#Visualisation)
- [Sanity Check](#Sanity-Check)
- [Automate These Boring Stuffs!](#Automate-these-boring-stuffs)
- [Resources](#Resources)
- [Conclusions](#Conclusions)

**Let's Start!**

### How to use this guide?

We'll give you some general tips to learn effectively and develop rock-solid foundations, that you can rely on to address and solve Data Science problems in the complexity of the real world (which is messy by definition).

In this guide, you'll find a ton of different tips, sub-topics answer these questions:
- why? (see [Research or business questions](#Research-or-business-questions))
- how?
- what?

The last two "how?" and "what?" overlap a bit and expand into these:
- [Start Small](#Start-small)
- [Small steps](#Small-steps)
- [The Toolkit and sources](#The-Toolkit-and-sources)
- [Datasets](#Datasets)
- [Data Generation](#Data-Generation)
- [Visualisation](#Visualisation)
- [Sanity Check](#Sanity-Check)

Any other section not mentioned are supporting sections to this guide.

As stated in the Virgilio's Teaching Strategy Guide, read more about it [here](https://github.com/virgili0/Virgilio/blob/708bd547c0bd04b05ac76b25c42b0158ea632b21/content/paradiso/virgilio-teaching-strategy.md).

[Back to the index](#index)

### The process

Here's a snapshot of the end-to-end flow (high-level perspective):

![Screen Shot 2020-07-19 at 15 53 42](https://user-images.githubusercontent.com/1570917/87877786-2d660100-c9d8-11ea-9aa9-cb5eb076b6f2.png)

Details are omitted and focus is drawn to the current subject (Data Collection) we are talking about.

[Back to the index](#index)

### Research or business questions

Asking the [right business questions](https://www.datapine.com/blog/data-analysis-questions/) is hard, but it has the [biggest impact](https://towardsdatascience.com/start-your-data-exploration-with-questions-2f1d42cff29e) on your performance of solving a particular problem. Remember, you want to [solve a problem](http://www.informit.com/articles/article.aspx?p=2271188&seqNum=2), not to create new ones! 

And same goes for asking the right research question. If you intend to establish something based on a hunch or curiosity or other research then there has to be some good base to start with.

You data collection process or step is entirely dependent on the research or the business problem you are trying to solve.

At this point it's also important to understand that the end-model you are on a quest to create, which is a direct reflection of two factors:

- Data (or datasets used)
- Method (algorith(s) used)

Although the second part i.e. Method will come a bit later, the first part is the primary or core component of the end-model. Methods can be swapped and at times the end-results may not differ by much but data is the key to getting a good model, otherwise you immediately can see the effects of GIGO (Garbage in, garbage out).

When coming up with the question or problem statement, it's also necessary to know the definition of "done" and use examples if possible to establish what the end-results should/could be comparable to once we reach the end point of the process (each iteration or the last iteration).

[Back to the index](#index)

### Start Small

It's not efficient to try to handle Gigabytes or Petabytes of data each time you want to create a dataset as part of the Data Collection process. Just use [small subsets](https://sdtimes.com/bi/data-gets-big-best-practices-data-preparation-scale/) of the data (but take care that the data is representative and you catch all the problems). Once you are certain about your process and the end-to-end flow has matured and stabilised you can consider using bigger chunks of data for the new iterations.

[Back to the index](#index)

### Small steps

Just like the previous section [Start Small](#Start-small), starting small and staying small or growing slowly (or incrementally) is the most optimum way to proceed with Machine Learning or Deep Learning problem solving - given there are so many variables and moving parts. It's best to minimise the moving targets and pin them or fix them to a minimum or a fixed constant when working on any part of the end-to-end flow.

And so knowing clearly whether to increase the quantity of data to collect (or not collect at all) at the beginning (or end) of the end-to-end flow is a good way to go about. You will be able to determine this once you have gained enough intuition about the specific subject and your end-to-end process to hand.

[Back to the index](#index)

### The Toolkit and sources

Here is a list of things you could be doing to gather fresh data or existing data (and repurpose it for your needs):

- Web Scrapping
- Look for pre-existing datasets
  - Kaggle Datasets
  - Kaggle Kernels using custom datasets
  - Other competition sites
- Maintaining data in excel sheets
- Collecting log files of program or application executions from live systems
- Running surveys via automatic services: Google Forms, SurveyMonkey, etc..,
- Convert non-digitalised data using modern technology
- Data generation services and tools

Many of the above can be done in a "live" manner or through cron (scheduled) jobs and others through manual intervention.

[Back to the index](#index)

### Datasets 

So the important question is what should the dataset look like? This will quite depend upon on your [Research or business questions](#Research-or-business-questions) to hand.

Having a look at how others have created their datasets for the various industries or topics or research subjects, can also help in the process. See this [Datasets resource](https://github.com/neomatrix369/awesome-ai-ml-dl/blob/master/data/datasets.md) which is a mix of both clean and unclean datasets. This can also answer the more specific question, what format? CSV? JSON? or anything else.

They can throw light on things to collect and not to collect, and in what form should they be collected such that it's useful for the next steps in the process.

[Back to the index](#index)

### Data Generation

This topic may need a section on it's own but there are many resources and facilities propping up these days that do exactly this, see this resource on [Data Generation](https://github.com/neomatrix369/awesome-ai-ml-dl/blob/master/data/data-generation.md#data-generation).

Data generation is also a good MVP step/process, and also could be incorporated as one of your steps during the first few iterations - if you discover or know from observation that the data to hand is not sufficient or correct or even not usable for the end-purpose (see [Research or business questions](#Research-or-business-questions)).

[Back to the index](#index)


### Visualisation

"A picture speaks a thousand words" or "A picture is worth a thousand words" or other variants - they all mean the same thing!

There is a misconception that Data Visualisation takes place towards the end or during some other process in the end-to-end process. But the fact is, whenever you have data, no matter what state it is in, we can partially (if not fully) visualise it. And gain an insight into what it is representing and what state it is in. It is an art and not just a science to be able to do this, the science part of drawing pictures from it is more or less solved, but evaluating them is another skill and depending on how well you know your domain, you will be able to determine this, which again goes back to the [Research or business questions](#Research-or-business-questions).

### Sanity Check

You always want to be sure that your data are _exactly_ how you want them to be, and because of this is a good rule of thumb to apply a sanity check after the completion of this step.

Although we won't know "what sanity checks to apply?" till we have run through the rest of the steps in the process and then come back the next iteration(s) and fine-tune this step so that it catches the important low-hanging fruits that do not hinder the rest of the processes. Sometimes you might just have to proceed with the data and the steps to follow i.e. Data Preparation, Data Cleaning, Data Visualisation will help reveal much about your collected data and decisions to take.

As we talk about Data Visualisation, your Visualisation step itelf is  a good enough sanity check about your data - provided you have drawn those charts and have the skills to evaluate them well enough. If not, hopefully the rest of the steps will help you capture those insights.

[Back to the index](#index)

### Automate These Boring Stuffs!

Data collection can be a tedius process but you could also [automate](https://www.youtube.com/watch?v=UZUoH7_mYx4) the most you can. Also, **automation is married with iteration**, so this is the way you need to plan your data collection pipelines. It's not easy to recommend automation tips but here are some of the things you could consider doing (depending on your needs and the [Research or business questions](#Research-or-business-questions) you are trying to answer), see [The Toolkit and sources](#The-Toolkit-and-sources).

Beware that not in every case you may be able to automate the process, it will all depend on the domain your problem statement is created from and how digitalised it is. But sometimes some data may need to be extracted manually or through human-intervention or through traditional methods. Sometimes it's easier to not digitalise or automate something till the need for it arises, a few manual steps at rate or slightly occassional times is acceptable, if Data Collection isn't performed on a regular-basis.

[Back to the index](#index)

### Resources

These two resources are quite extensive and have been rated by experienced professionals in the industry:

- [👉 Effective Data Collection 👈](https://www.linkedin.com/posts/asif-bhat_data-collection-activity-6625312371869089793-4LrM)
- [The Ultimate Guide to Effective Data Collection](https://www.linkedin.com/posts/iamsivab_the-ultimate-guide-to-effective-data-collection-activity-6656175779732381697-lv6X)

It would be good to have a glance of them to see if you have not considered something. Such resources can also help validate the things we already know and how we are using them in the context of the problem in hand (and how others have been using them).

Also look at this talk on ["Do we know our data, as good as we know our tools?"](https://github.com/neomatrix369/awesome-ai-ml-dl/blob/master/presentations/data/02-devoxx-uk-2019/README.md), it starts of with an introduction to "Data Collection" and then into the next steps in the end-to-end process.

But don't just stick to these build your own accumen and also look for other resources.

[Back to the index](#index)

### Conclusions

So now that you have an idea of what to do when you want to start solving a business problem using techniques like Machine Learning and Deep Learning. You can also start thinking about how to do this in a simple manner and keep building on top of it, otherwise you maybe forever busy collecting data but not proceed further from there. And not know the impact or use of the data collected. And thereby not gain the insight needed to answer your query or solve the problem statement.

[Back to the index](#index)