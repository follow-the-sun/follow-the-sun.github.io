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

# [](#header-1) Limitations of FTS

FTS has many challenges associated with it and it also faces same challenges of GSD as it is a part of GSD.  The success cases in the
industry using FTS are insufficient \[9\]. The implementation of FTS, if not correct, may result in failures and over budget projects \[10\]. According to Carmel \[1\], FTS has challenges such as coordination barriers, cultural differences, and communication difficulties.

* Coordination challenge: When more than one site is added to the project, this increases the difficulties to coordinate aspects that involve team management, and cultural and geographical differences \[6\]. For example, daily handoffs are difficult to coordinate due to the difficulty of resolving task issues across sites/shifts, and the cross-site coordination cost will most likely be positive and nontrivial. If a team hands off a work to other team, the problem can get worse if the other team doesn't understand correctly about the problem or introduce a new problem.
* Communication challenge:  This difficulty occurs due to the increasing of the number of teams allocated to the project and consequently loss of communication richness. Solving a problem that need intense communication across teams is hard to do since each team’s working time is not on the same time or if there is intersection time, it will be used to handing off the work. The communication challenges in FTS are associated mainly to the lack of synchronous communication between distributed teams \[11\].
* Cultural challenge: Culture differences challenges are associated to the socio-cultural diversity present in FTS development environments. It is determined mainly by social, ethnic and cultural aspects [12\]. For example, the usual problems of supporting collaboration are compounded by language and diversity \[13\]. In addition, if one culture has more emphasis on self sufficiency, therefore they tend not to ask for help when problems come up. Another culture would not offer their help unless they were asked while the third considered that presenting the problem was a sufficient invitation for a willing team members to jump in and help.

# [](#header-1) References
\[1\] Carmel, E., Espinosa, J. A., & Dubinsky, Y. (2010). " Follow the Sun" Workflow in Global Software Development. Journal of Management Information Systems, 27(1), 17-38. <!---carmel2010follow-->

\[2\] Millson, M. R., Raj, S. P., & Wilemon, D. (1992). A survey of major approaches for accelerating new product development. Journal of Product Innovation Management, 9(1), 53-69. <!---millson1992survey--->

\[3\] Brooks Jr, F. P. (1995). The Mythical Man-Month: Essays on Software Engineering, Anniversary Edition, 2/E. Pearson Education India. <!---brooks1995mythical--->

\[4\] Gupta, A. (2007). Deriving Mutual Benefits from Offshore Outsourcing: The 24-Hour Knowledge Factory Scenario. <!---gupta2007deriving--->

\[5\] Gupta, A. (2009). The 24-hour knowledge factory: can IT replace the graveyard shift?. Computer, 42(1), 66-73. <!---gupta200924--->

\[6\] Carmel, E., Dubinsky, Y., & Espinosa, A. (2009, January). Follow the sun software development: New perspectives, conceptual foundation, and exploratory field study. In System Sciences, 2009. HICSS'09. 42nd Hawaii International Conference on (pp. 1-9). IEEE. <!--carmel2009follow-->

\[7\] Yap, M. (2005, July). Follow the sun: distributed extreme programming development. In Agile Conference, 2005. Proceedings (pp. 218-224). IEEE. <!---yap2005follow--->

\[8\] Doerr, C. (2017). Network Security in Theory and Practice. <!---NetworkSecurity--->

\[9\] Rini van Solingen and Menno Valkema. The impact of number of sites in a follow the sun setting on the actual and perceived working speed and accuracy:  A controlled experiment. In Global Software Engineering (ICGSE), 2010 5th IEEE International Conference on, pages 165–174. IEEE, 2010. <!---van2010impact--->

\[10\] Eoin Ó Conchúir, Helena Holmstrom Olsson, Par J Agerfalk, and Brian Fitzgerald. Global software development: never mind the problems – are there really any benefits? 2006. <!---o2006global--->

\[11\] Siri-on Setamanit, Wayne Wakeland, and David Raffo. Improving global software development project performance using simulation. In Management of Engineering and Technology, Portland International Center for, pages 2458–2466. IEEE, 2007. <!---setamanit2007improving--->

\[12\] Miguel Jiménez, Mario Piattini, and Aurora Vizcaíno. Challenges and improvements in distributed software development: A systematic review.
Advances in Software Engineering, 2009:3, 2009. <!---jimenez2009challenges--->

\[13\] Alex Cameron. A novel approach to distributed concurrent software development using a follow-the-sun technique. Unpublished EDS working paper, 2004. <!---cameron2004novel--->