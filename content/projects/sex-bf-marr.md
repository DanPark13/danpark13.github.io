---
title: "America's Views on Pre-Marital Sex"
date: 2022-04-12T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
tags: ["project", "class", "python","data-science","data-vis","gss","pandas","matplotlib"]
author: "Daniel Park"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "How Opinions on Pre-Martial Sex have changed over time across different religious backgrounds"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: true
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/DanPark13/danpark13.github.io"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

## Sex Education in America Now

In an age of unlimited information from the internet, we often find a whole barrage of information, especially that related to sex, exposed to today's children and teenagers. And some, primarily people from conservative backgrounds, are increasingly concerned about their children being exposed to this information prematurely. Most of their concerns are that premarital, especially underage sex, is not justified.

As seen in **Figure 1** from Statista, a large part of America still don't require sex and HIV education in their public school education while some states even advocating abstinence in sex education.

{{< figure src="/images/projects/sex-bf-marr/stateofsexed.jpeg" caption="**Figure 1**: The state policy on sex ed in schools by US State as of July 2019." >}}

And to combat this today, many schools offer comprehensive sexuality education curricula regarding the treatment of sexuality, reproduction, and HIV/AIDS in favor of teaching abstinence so kids can explore themselves responsibly to avoid any unexpected pregnancies and sexually transmitted diseases. However, the debate comes in whether that knowledge should be provided by public schools or left up to parents. Many local and nationwide conservative groups such as the America Family Association, the National Coalition of Abstinence Education, and the Christian Coalition argue that public schools should not have the power to give this kind of education to children, as it may encourage sexual promiscuity within them, and it should be up to families to educate their children on sexual behavior.

Given the public resistance and protests against sexual education in public schools, I sought out to analyze whether or not banning public school sex education was popular among the American public. Are more people in support of sex education in public schools or do these groups represent the majority that believe parents or guardians, the role models in their children???s lives, should be responsible for guiding their children???s sexual lives and behavior?

## America's Views on Public School Sex Education

To gain more insight on the topic, I ran an analysis on the General Social Survey (GSS), a survey given to the American public to give politicians, policymakers, and scholars a clear and unbiased perspective on what Americans think and feel about issues such as national spending, crime and punishment, and intergroup relations. The survey provides a question about whether or not respondents believe that sexual education should be in public schools or not. Figure 2 shows the relationship between the years from 1975 to 2021 and the percentage of those in favor of sex education in schools. As seen in the figure, those in favor of  sex education have always represented approximately 80% of the survey respondents during the 1970s. And since then, the respondent rates in the GSS favoring sex education in public schools has risen to about 92% of respondents in 2020.

{{< figure src="/images/projects/sex-bf-marr/sexopinionovertime.png" caption="**Figure 2**: General U.S Population Opinion in Public School School Sex Education." >}}

## Religion's Impact on American Perception on Sex Education

Seeing from the GSS data that this stance is unpopular and noticing that a lot of opposition to sex education is particularly from religious organizations, I also analyzed data to determine the relationship between religious background and view on public school sex education.

{{< figure src="/images/projects/sex-bf-marr/religvsnonreligsex.png" caption="**Figure 3**: Overall U.S Opinion on Sex Education in Public Schools by Religion." >}}

I grouped people's responses by whether or not they were religious, as seen in Figure 3. I found that religious people don't support sex education as much as non-religious people. However, the difference between the two is slight, with about 86% of religious people and 94% of secular people favouring sex education. But disregarding the difference, both groups have an overwhelming supportive opinion of public school sex education.

{{< figure src="/images/projects/sex-bf-marr/sexedreligovertime.png" caption="**Figure 4**: U.S Opinion on Sex Education to see the public perception of sex education over time categorized by religion." >}}

Even though we see that non-religious people are more supportive of public school sex education than religious people, it is entirely possible that the change favouring sex education from religious people happened recently than in the past. In Figure 3, I graphed the U.S. population's view on comprehensive sexual education by religion. The distinction between religious and non-religious people is clear; Religious people, on average, favour sex education in America about 6-7 percentage points less than secular people. However, the rate of sex education acceptance has been rising in both demographics since the 1970s, with about 95% of the non-religious U.S. population favouring sex education and about 90% of the religious population favouring sex education in the late 2010s.

As seen in Figure 3, those in favour of sex education have been in the majority overall for a while now, with a staggering amount of Americans believing that sex education should be taught in public schools, overshadowing those who are opposed to public school sex education.

## Closing Remarks

So what should be America's plan from here on out about comprehensive sexual education? Should we go ahead with what the majority believe is correct and require all students to receive public school sexual education, even if it undermines parents' responsibility to do so and brings matters that should be private into the public view? Or should we ban it in public schools in favour of parents being responsible for giving this kind of guidance? 

The results show that people greatly support public sex education, even those who consider themselves religious, where most of the outcry comes from. So is embracing public school sex education commonplace in our schools?

## Sources

- ???Public Opinion in Georgia on Premarital Sex for Women.??? SOCIAL SCIENCE IN THE CAUCASUS, crrc-caucasus.blogspot.com/2019/10/public-opinion-in-georgia-on-premarital.html. Accessed 26 April 2022.
- ???GSS Data Explorer NORC at the University of Chicago.??? The General Social Survey, gssdataexplorer.norc.org/variables/626/vshow. Accessed 26 April 2022.
- ???Ten Good Reasons Oppose Public School Sex Education.??? Catholic Parents Online, 2017, catholicparents.org/ten-good-reasons-oppose-public-school-sex-education.
- People For the American Way. ???Teaching Fear: The Religious Right???s Campaign Against Sexuality Education.??? People For the American Way, 16 Jan. 2017, www.pfaw.org/report/teaching-fear-the-religious-rights-campaign-against-sexuality-education.
- Buchholz, Katharina. ???Sex Education Mandatory in Half of U.S. States.??? Statista Infographics, 26 July 2019, www.statista.com/chart/18825/state-laws-sex-ed-in-the-us.

<br>

View the Google Collab Notebook used to research and visualize the data [here](https://colab.research.google.com/drive/1pe_dbONHOZi3Ho8U8uHjoF779LJm_EDy?usp=sharing).

<br>
