---
layout: default
---

# [](#header-1) Introduction

Modern day software development is spread more and more across national and international boundaries. Global software development (GSD) is now the need of the hour more than ever. One of the important concepts evolved in the past decade or so is the "Follow the sun" (FTS) software development.

It is a model in which work from one site is handed over to another which is many time zones away (for Ex: U.S.A to India) in order for the work to be advanced while one team rests for the night. It is also known under different names such as 24 hour development or Round the clock development.   

The major benefit is the development duration or the potential in reducing the time-to-market. Theoretically speaking, if 'n' sites are working on this scheme, their development speed could be increased dramatically by systematically organizing the work tasks sequentially on a daily basis and optimizing the coordination costs \[1\].

Although this seems like such an intuitive idea to work with, it is not practised widely, misunderstood often and has had a few documented industry success cases.

# [](#header-1) Background
To get a proper picture of the background on FTS, there is a need to understand a development pace and its associated concept of time to market which are the main drivers to the development of FTS. Time to market is the amount of time it takes from the moment the product is conceived until the product is available for use or sale. This is very important mainly for industries especially for the ones whose products become outdated in a very short time, for example Mobile handsets, firmwares, e-commerce systems, innovative supply chain management, etc.

Many factors influence the need to develop the products quickly such as avoiding contract creep, schedule slippages, budget overruns and other managerial reasons. To fulfil this need, most firms try various strategies such as overtime work, skipping steps, setting aggressive deadlines, etc which are reactive in nature. But these steps will add to the increase in cost due to burnout and fatigue \[2\]. Adding more man power to the project is not of much interest in the software development because of the wisdom gained long ago from the seminal brooks’s law "adding manpower to a late software project makes it later” \[3\]. These difficulties prove that a systematic approach is needed in achieving a quick time-to-market strategy, which in turn leads to Follow The Sun software development scheme.

# [](#header-1) Principles of FTS
In order to understand and use FTS, some key principles on which FTS is based on is mentioned in this section.

*   FTS is a global software development strategy.
*   The main criteria to go for FTS is the reduction in the development time or time-to-market.
*   Production sites involved in the software development are many time zones apart.
*	There is only one site that owns the product at any point in time.
*	Project handoffs are done on a daily basis at the end of each shift.
*	The handoffs can be applied to any software development task.    

The above principles allow the FTS to be used in any knowledge work (not just software development). There are claims that FTS is being used at General Motors and at OfficeTiger \[4\] \[5\].  Some key assumptions in deriving the above principles are listed below:

1.	Each production site works during the day as "subteam" and it needs within-site coordination.
2.	A subteam can consist of one or more members.
3.	A handoff from one site to the other can be occasionally empty due to public holidays or emergencies.
4.	There is a common product repository which allows each site to be in sink with their work at the end of each workday.

Follow the sun approach involves daily handoff of the work which suggests that there will be some reduction in the project duration. The detailed analysis needs to be done in order to understand the advantages to be gained in time. One such analysis is done using the "calendar" time \[1\] available for production. The term calendar efficiency helps in understanding the analysis further. It is defined as the percentage of all of the calendar time (e.g., 24 * 7 = 168 hours available per week) that is used productively for work, so, a 40-hour workweek utilizes 23.8 percent of the calendar workweek, showing that there is a lot of room for calendar efficiency improvement.

Table in Fig. 1 gives the relevant facts regarding various working schemes. For example, a baseline work is 30 hrs after taking into account non-task activities. Calendar efficiency can be increased in a simple way by working overtime (overload mode), but only improves the efficiency by 6%. Heavy overload still improves the efficiency by just 12% but it is not an effective strategy for long time due to employee burnout. This is where FTS potential gains a lot of attention as is evident in the bottom rows of the table. An optimal FTS configuration could raise the calender efficiency as high as 71.4%.

![](/images/Table1.png)
__Figure 1: Calendar Efficiency in different Working Modes__

# [](#header-1) Traditional software development  vs FTS

There are several major differences between traditional globally distributed software development and FTS approach. In traditional software development, global teams have little dependency on one another and usually do not pass on the work (hand-off). Hand-off is the central idea of FTS approach. The efficiency of number of hours per day put into actual development is much higher in FTS model when compared with traditional software development \[1\]. This is because work happens almost round the clock, compared with just eight hour efforts in traditional software workflow. This efficiency further increases with the number of locations and shifts.

At any given time only one team owns the product unlike other global configurations in which multiple locations can own different parts of the product. As illustrated in Fig. 2  traditional software development stresses on minimal job hand-offs, whereas FTS focusses on day-to day job hand-offs \[1\]. Because of its uncommon nature, FTS is also least practiced in the industry and has very few documented examples of success. When compared to traditional global software development FTS workflow is more difficult to achieve.

![](/images/fts1.jpeg)
__Figure 2: Comparing FTS with other global workflows \[1\]__

## [](#header-2) All global workflows are not FTS
Several workflows seem to be using the FTS model, but in reality this is not always the case. Based on the discussions in the _Principles of FTS_ section which explains the minimum criteria for a work flow to be considered as a FTS approach, the following do not fit in this category \[1\]:

*	Software development involving multiple global locations in different time zones is not always FTS if it does not satisfy all the criteria mentioned in the _Principles of FTS_ section.
*	Global business processes such as call centres or help desks are not counted under the FTS umbrella.
*	Collocated multishift – locations where labour is cheap and software development happens round the clock in eight hour shifts does not fit in this category.

# [](#header-1) Agile and FTS
Agile software development practice consists of a set of principles which advocate continuous improvement, adaptive planning, early delivery and flexibility in responding to change. The various Agile methodologies such as Scrum, Lean, Kanban, Extreme Programming (XP), DSDM etc. share much of the same characteristics and practices and are widely practiced in Globally Distributed Software Development (GSD). Follow the Sun (FTS) is a special case of GSD which aims to achieve a 100% workday in software projects. As described by Carmel et al \[1\] the Agile methodology is best suited for FTS.

## [](#header-2) Traditional software development models and FTS
Linear sequential approaches such as the Waterfall model seem to be inefficient for the FTS approach. Carmel \[6\] argues that only some phases of the development cycle such as testing are well suited for FTS because of their nature. As a result, the benefits of FTS tend to be concentrated around isolated phases rather than having an overall impact on the development cycle. Hence it is important to select a software development methodology which extends over the entire software development cycle and satisfies the special needs of daily hand-offs.

## [](#header-2) Agile - perfect match for FTS
Agile has several characteristics which support FTS adoption \[6\]. In an Agile based methodology, all major development activities (design, code, test and integrate) are carried out in every iteration cycle. The iteration period lasts for a short time period (between two to four weeks). Agile places a lot of emphasis on continuous integration (using automation) encouraging every team to maintain an updated and testable version of the code which can be used by the next production site. This facilitates easy job hand-offs and fits nicely within the FTS model. Agile also provides an opportunity for every team to maintain a sustainable pace of development i.e. working only during daylight hours. Agile stresses on the importance of automated testing to reduce time. Collaboration between teams is very important in Agile, a trait which is also a characteristic of FTS model. Because of these reasons FTS is best suited for Agile. However, one slight difference is that Agile stresses on face to face communication, in FTS inter-site communication between production sites is maintained at the bare minimum by using automated tools.

Others such as Gupta et al \[5\] also make similar observations  and propose that FTS is very well suited to support core Agile practices. In a research carried out by Yap \[7\] a globally distributed software project team (UK, USA, and Singapore) followed the FTS approach under the Extreme Programming (XP) model - a form of Agile practice. Initial handoffs mainly consisted of daily work summaries, which were later augmented by knowledge transfer activities. Though the teams faced initial setbacks due to cultural differences and technical glitches, by re-orienting their thinking they could successfully implement Agile practices across all locations on a single working codebase.

# [](#header-1) Technology tools and infrastructure to support FTS
FTS approach has only a handful of documented cases of industrial success because of its nature. A part of this may be attributed to the availability of efficient tools and enabling technologies for implementing the FTS model. Software tools used for actual FTS implementation must include both managerial and technical aspects, to adapt to the changing requirements of the software development process.

Tools for estimating and planning schedules, allocation of project tasks, sprint management, progress tracking are essential utilities for front line managers. Mechanisms for transferring work in progress to the next site is the core idea of FTS. The process of hand off must be smooth and conflict free. It must also ensure that all the required information and reports to continue the work is visible and easily accessible. The focus is on using automated tools which simplify the repetitive tasks.
Some other day to day tasks enabled by software include – logging time spent by developers, issue tracking, real time reporting, code reviews, and documentation.

The effective utilization of code repositories and version control management systems is crucial to the success of FTS approach. It is quite possible that hundreds of software developers and testers can be working on a project in cycles. Most of the current code repositories are cloud based and accessible across geographies. In this distributed model, the CIA \[8\] triad of Confidentiality, Integrity and Availability of service and data assumes paramount importance. This infrastructure must always be available on demand and accessible. Tools to support data security and encryption such as VPN’s are also important. The ability of project management tools to integrate with development tools can help reduce the duration of project cycles in FTS.

Modes of communication in FTS approach may be asynchronous or synchronous. The geographically dispersed nature requires the use of software applications which facilitate tele-conferencing, VoIP calling, instant messaging etc. Knowledge transfer and sharing of project critical information with concerned parties is essential for smooth operation of the project. Formal systems such as discussion forums or internal Wiki sites may prove to be useful. If communication issues are not addressed they might create significant challenges in FTS adoption.

# [](#header-1) Applying the FTS Model in Practice

FTS approach is based on the principle of handing-off unfinished work to the next location at the end of work day. To manage the workflow efficiently the following principles are applied in practice.

1. Speed improvement is the primary focus<br/> Achieving reduction in overall development cycle by achieving high calendar efficiency is the primary motive of FTS approach. This is to be achieved by round-the-clock development using efficient daily hand-off coordination.  

2. Well defined product architectures<br/>
As explained in \]6\] Carmel et al stress on defining product architectures which can be developed as relatively small and independent components. FTS approach is the most suitable when product definitions are well defined and clear.

3. Vertical division of tasks<br/>
Traditional approach to software development emphasis horizontal division of tasks – each location working on a specific sub module. FTS approach stresses on the vertical division of tasks across geographies. Every location contributes to the continuous development of the entire project by taking up tasks left unfinished by the previous team. Tasks must be delegated efficiently without creating a sort of ‘Master-Slave’ relation between teams \[5\].

4. Project management and coordination – use of automated tools <br/>
FTS philosophy raises several important questions regarding overall project management, determining code quality, conflict resolution and avoiding infrastructure duplication. Efficiency in task handoff is of paramount importance to the success of FTS approach. This requires the application of innovative management tools and techniques such as MultiMind outlined in \[5\]. The idea is to use automated tools for generating scrum reports, code review documents and manage task handoffs so that workflow is continuous and free from conflicts. Key to reducing delays in FTS lies in efficiency with which two developers can work – working in parallel or sequentially in shifts, integrating and handing off the work to each other at the end of each shift.

5. Knowledge transfer <br/>
Continuous sharing and dissemination of knowledge is one of the deciding factors for the success of FTS approach. Use of knowledge management tools to capture crucial information ensures that information is shared and available to all the stakeholders irrespective of physical location.

# [](#header-1) FTS examples in the industry
In 2004 a study conducted within the company of WDSGlobal reported the following list of what worked in FTS software development (when doing Extreme Programming) \[7\]:

* Daily handovers
* Face-to-face communication (video calls for handovers)
* Shared common configuration
* Remote pairing, for "collaborating on ideas and sharing experiences, removing misunderstandings, and fostering shared memory between the pair and through them the teams"
* Round-the-World Program, which means that each member of the team works at each region for four to six weeks (if possible), which means that a team member gains "a certain level of knowledge of the background and shared cultural values, and building trust with members in other regions"
* Work together on features and issues
* Coaches had one-on-one meetings after daily handovers, all coaches had weekly meetings to discuss issues and once in a quarter all coaches physically met for two weeks to deal with more complicated issues and discuss long term planning
* Regular discussions about Extreme Programming

The study reported the following lessons that were learned:

* Balance teams, so that one team does not dominates the project
* Introduce "a set of rules and pre-defined processes" so that "all of the team members ... know exactly what to expect from each other"
* The problem of introducing innovation. Ideal would be a consensus among the whole team, but this is very time consuming, due to different locations and time zones.
* Allow some flexibility in different locations with respect to shared processes

The study involved teams from the USA, UK and Singapore. Although these regions share the English language, there were cultural differences, for example, "one culture has more emphasis on self sufficiency; therefore they tend not to ask for help when problems come up. Another culture would not offer their help unless they were asked while the third considered that presenting the problem was a sufficient invitation for willing team members to jump in and help".

In 2013 there was a feasibility study of FTS in industry \[18\]. The work involved a software project developed by teams in Mexico, India and Australia, which followed Scrum. There was a 30 and 60 minutes overlap between locations "to enable the daily handover of tasks". The three teams consist of 2 micro-teams (composite persona \[17\]), with at least one person from each location. The result was that the project was completed in 5.5 weeks, while it was estimated to be completed in 6 weeks in non-FtS mode, so it reduced time.

Major lessons learned in the study that could improve FTS from their experience include:

* Templates and standard documents in the project
* Coding standards
* Screen sharing
* A communication protocol
* Tasks for the day for individuals
* Handover template
* Assign tasks to a composite persona owner \[17\]

It was also observed that hand-offs between different sites was especially difficult in the weekends, since there is no overlap during the hand-off and the hand off happens, for example, via e-mail, instead of via the phone or other communication tool.

# [](#header-1) Advantages of FTS approach

The FTS approach utilizes distributed team members spread across time-zones to achieve a single project outcome with the main objective of gaining speed and reducing the time-to-market of a project \[13\]. This in turn increases productivity. Assuming each site has a work day of 6 hours, the project can be done with 4 sites, spread out over different time zones. Hence, assuming a work day consists of 6 hours, the project duration can be reduced by four times. Apart from this advantage, it also provides the following additional advantages:

* Access to global resources at lower costs, which only becomes a valid cost saving in the case where the operating and labour costs are much lower, such as in locations like India or China. But the additional cost of communicating requirements and changes on a daily basis erodes the labour cost savings to some extent.
* It facilitates and enhances international partnerships.
* Helps in leveraging skills and experience across all sites. The potential to leverage a broader and/or deeper skill base is a valid benefit and can offer a business unique skills otherwise unavailable and therefore provide an important competitive advantage.
* It helps in reducing software licensing costs. When software licensing permits, there is a potential opportunity to share the license costs over more than one time zone thereby reducing the total number of licenses required.

# [](#header-1) Limitations of FTS

FTS has many challenges associated with it and it also faces same challenges of GSD as it is a part of GSD.  The success cases in the
industry using FTS are insufficient \[9\]. The implementation of FTS, if not correct, may result in failures and over budget projects \[10\]. According to Carmel \[1\], FTS has challenges such as coordination barriers, cultural differences, and communication difficulties.

* Coordination challenge: When more than one site is added to the project, this increases the difficulties to coordinate aspects that involve team management, and cultural and geographical differences \[6\]. For example, daily handoffs are difficult to coordinate due to the difficulty of resolving task issues across sites/shifts, and the cross-site coordination cost will most likely be positive and nontrivial. If a team hands off a work to other team, the problem can get worse if the other team doesn't understand correctly about the problem or introduce a new problem.
* Communication challenge:  This difficulty occurs due to the increasing of the number of teams allocated to the project and consequently loss of communication richness. Solving a problem that need intense communication across teams is hard to do since each team’s working time is not on the same time or if there is intersection time, it will be used to handing off the work. The communication challenges in FTS are associated mainly to the lack of synchronous communication between distributed teams \[11\].
* Cultural challenge: Culture differences challenges are associated to the socio-cultural diversity present in FTS development environments. It is determined mainly by social, ethnic and cultural aspects [12\]. For example, the usual problems of supporting collaboration are compounded by language and diversity \[13\]. In addition, if one culture has more emphasis on self sufficiency, therefore they tend not to ask for help when problems come up. Another culture would not offer their help unless they were asked while the third considered that presenting the problem was a sufficient invitation for a willing team members to jump in and help.

# [](#header-1) Research themes

## [](#header-2) Best practices
Research in Follow-the-Sun software development has been done since 1990. Results are generally best practices to improve the methodology and challenges. This literature survey \[14\] listed 36 best practices and 17 challenges for Follow-the-Sun software development from research between 1990 and 2012.

## [](#header-2) Location selection
This research \[15\] introduced a routing model, which supports the selection of geographical locations for Follow-the-Sun software development. The research focussed on two aspects: "the optimal time zone difference" and "the natural ease of communication" (i.e. culture and language). The model makes use of a database of locations that contain demographic data about these locations. The result of the study was a website on which a possible optimal route of geograhpical locations for Follow-the-Sun software development could be calculated.

Another research \[9\] looked at the impact of the number of sites on working speed and accuracy in Follow-the-Sun software development. In this case accuracy is "the degree in which the produced work represents the expected work". Overall it was found that increasing the number of sites in a daily cycle increased the working speed. The number of sites had only a small impact on the accuracy.

## [](#header-2) Hand-offs management
Since hand-offs are such an important aspect of Follow-the-Sun software development, recent research studied hand-offs management \[16\]. It was concluded that nine aspects of management are important for improving hand-offs efficiency (directly taken from \[16\]):

* Improving communication quality
* Ensure knowledge transfer between team members and production sites
* Management of hand-off's information
* Developing team's trust before and along the project
* Ensure compliance of deadlines
* Establishing time rules
* Providing proper technology and tools
* Delegating responsibility
* Coordination of task allocation

Since these aspects above are reported to increase efficiency, it was also concluded that when these aspects are taken into account the duration of the project is reduced.

# [](#header-1) References
\[1\] Erran Carmel, J Alberto Espinosa, and Yael Dubinsky. "follow the sun" workflow in global software development. Journal of Management Information Systems, 27(1):17-38, 2010. <!--carmel2010follow-->

\[2\] Murray R Millson, SP Raj, and David Wilemon. A survey of major approaches for accelerating new product development. Journal of Product Innovation Management, 9(1):53-69, 1992. <!--millson1992survey-->

\[3\] Frederick P Brooks Jr. The Mythical Man-Month: Essays on Software Engineering, Anniversary Edition, 2/E. Pearson Education India, 1995. <!--brooks1995mythical-->

\[4\] Amar Gupta. Deriving mutual benefits from offshore outsourcing: The 24-hour knowledge factory scenario. 2007. <!--gupta2007deriving-->

\[5\] Amar Gupta. The 24-hour knowledge factory: can it replace the graveyard shift? Computer, 42(1):66-73, 2009. <!--gupta200924-->

\[6\] Erran Carmel, Espinosa, Yael Dubinsky, and Alberto Espinosa. Follow the sun software development: New perspectives, conceptual foundation, and exploratory eld study. Proceedings of the 42nd Hawaii International Conference on System Sciences, 2009. <!--carmel2009follow-->

\[7\] Monica Yap. Follow the sun: distributed extreme programming development. In Agile Conference, 2005. Proceedings, pages 218{224. IEEE, 2005. <!--yap2005follow-->

\[8\] Christian Doerr. Network Security in Theory and Practice. Christian Doerr,
Federal Republic of Germany, 2017. <!--NetworkSecurity-->

\[9\] Rini van Solingen and Menno Valkema. The impact of number of sites in a follow the sun setting on the actual and perceived working speed and accuracy:  A controlled experiment. In Global Software Engineering (ICGSE), 2010 5th IEEE International Conference on, pages 165–174. IEEE, 2010. <!--van2010impact-->

\[10\] Eoin Ó Conchúir, Helena Holmstrom Olsson, Par J Agerfalk, and Brian Fitzgerald. Global software development: never mind the problems – are there really any benefits? 2006. <!--o2006global-->

\[11\] Siri-on Setamanit, Wayne Wakeland, and David Raffo. Improving global software development project performance using simulation. In Management of Engineering and Technology, Portland International Center for, pages 2458–2466. IEEE, 2007. <!--setamanit2007improving-->

\[12\] Miguel Jiménez, Mario Piattini, and Aurora Vizcaíno. Challenges and improvements in distributed software development: A systematic review.
Advances in Software Engineering, 2009:3, 2009. <!--jimenez2009challenges-->

\[13\] Alex Cameron. A novel approach to distributed concurrent software development using a follow-the-sun technique. Unpublished EDS working paper, 2004. <!--cameron2004novel-->

\[14\] Josiane Kroll, Sajid Ibrahim Hashmi, Ita Richardson, and Jorge LN Audy. A systematic literature review of best practices and challenges in follow-the-sun software development. In Global Software Engineering Workshops (ICGSEW), 2013 IEEE 8th International Conference on, pages 18–23. IEEE, 2013. <!--kroll2013systematic-->

\[15\] Christian Visser and Rini van Solingen. Selecting locations for follow-the-sun software development: Towards a routing model. In Global Software Engineering, 2009. ICGSE 2009. Fourth IEEE International Conference
on, pages 185–194. IEEE, 2009. <!--visser2009selecting-->

\[16\] Josiane Kroll, Ita Richardson, Jorge LN Audy, and Jude Fernandez. Handoffs management in follow-the-sun software projects: a case study. In
System Sciences (HICSS), 2014 47th Hawaii International Conference on, pages 331–339. IEEE, 2014. <!--kroll2014handoffs-->

\[17\] Amar Gupta, Rajdeep Bondade, and Nathan Denny. Software developmentusing the 24-hour knowledge factory paradigm.  2008. <!--gupta2008software-->

\[18\] Josiane Kroll, Rafael Prikladnicki, Jorge LN Audy, Erran Carmel, and JudeFernandez.  A feasibility study of follow-the-sun software development for gsd projects.  2013. <!--kroll2013feasibility-->
