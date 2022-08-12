---
authors:
  - Christopher Burr
tags:
  - fairness
  - explainability
  - argument-patterns
---
# Chapter 4: Argument Patterns

![A placeholder image](https://via.placeholder.com/800x400?text=Placeholder+Image)

The previous chapter have achieved several goals:

1) Setting a context that is receptive to the sociocultural and human-centred aspects of trustworthy digital mental health technology.
2) Introducing the trustworthy assurance methodology to assist communication, assessment, and documentation tasks for developers and regulators
3) Providing recommendations that have been co-developed through stakeholder and user participation

While the assurance methodology is a tool in its own right, there is a missing component that was highlighted in [Chapter 1]: argument patterns. You may recall that argument patterns are reusable structures that serve as *starting templates* for building assurance cases. They identify the *types* of claims (or, the sets of reasons) that need to be established to justify the associated top-level normative goal. And, in doing so, they set useful constraints on both the deliberative process and evidence-generating and evidence-gathering exercises.

In this chapter we present and explain two argument patterns. The first is for assurance cases that aim to justify the *fairness* of a digital mental health technology; the second is for cases that address the *explainability* of systems.

### Why ‘fairness’ and ‘explainability’?

Our decision to provide these two patterns is motivated by the desire to capture as many of the significant themes raised in the workshops, and to provide a more context-specific set of core attributes for two of the SAFE-D principles. That is, to demonstrate how the SAFE-D framework applies in the context of digital mental health.

The inclusion of a pattern for fairness was an obvious choice. However, the inclusion of one for the goal of explainability requires additional clarification.

As the previous chapters demonstrate, many participants in our workshops focused on ethical issues that could map onto multiple SAFE-D principles. For instance, considerations around `transparency` were sometimes raised in connection with mechanisms for holding organisations `accountable` and at other times raised in connection with a requirement to ensure users had access to information to support informed consent and decision-making—captured either by `sustainability` or `explainability`.

Our second argument pattern is framed in terms of `explainability` as an attempt to be maximally inclusive of these wide-ranging considerations. However, further work is clearly needed to develop additional patterns that may provide more specific guidance for use in different contexts. To recall, argument patterns in trustworthy assurance are always *starting points* for participatory forms of reflection and deliberation. They provide greater specificity than the top-level goal would on its own, and help operationalise ethical principles within the project lifecycle model. But they are no substitute for embedded processes of inclusive stakeholder engagement—in fact, they depend upon stakeholder engagement processes for their completion. Furthermore, they should not be used as a mere checklist for compliance. 

Finally, our focus on 'fairness' and 'explainability' should not suggest that other patterns are not desirable or important. Rather, the co-design and development of additional patterns, including those that go beyond the SAFE-D principles are left for future research (see Conclusion).

> **Note**
> We present the two cases here, but additional user guidance can be found online, including information on possible evidence, and processes for generating claims (e.g. stakeholder engagement).

### Fairness

In the context of data-driven technologies, a key attribute of fairness is the equal distribution of risk and benefit across all groups of affected users. For instance, a technology that was highly accurate for users aged between 18-30 but became decreasingly accurate for older individuals would be unfair to those from higher age brackets.

The differentiation between risk and benefit leads to a subsequent distinction between corresponding duties or obligations (e.g. legal duties). Where there is a duty to ensure that a particular group of users are not exposed to disproportionate risks of harm, this sets up a so-called “negative duty” (e.g. a duty to not discriminate). However, negative duties often set only the minimal ethical standards. In other words, one can build a non-discriminatory service that does not harm anyone, but similarly benefits no one. 

Therefore, corresponding “positive duties” also exist to promote beneficial outcomes, sometimes focusing on those who are most disadvantaged—a so-called “prioritarian” approach to ethics (i.e. prioritising those who need the most support). A good example of this duality is the Public Sector Equality Duty, which sets the following objectives for all public authorities:

- eliminate discrimination, harassment, victimisation and any other conduct that is prohibited by or under the Equality Act 2010;
- advance equality of opportunity between persons who share a relevant protected characteristic and persons who do not share it;
- foster good relations between persons who share a relevant protected characteristic and persons who do not share it.

Notice that these objectives have both negative and positive aspects to them (e.g. ‘eliminate discrimination’ as ‘opposed to advance equality’). 

In the context of mental healthcare, where stigmatisation prevents many vulnerable individuals from accessing care and discrimination exacerbates symptoms for already marginalised groups, both types of duty are absolutely crucial. But acting upon positive duties is not without its challenges.  

In our workshops, for instance, a key concern that was emphasised was the degree to which the delineation of "good" or "desirable" mental health outcomes for the purpose of evaluating the impacts of a system could adequately take into account the subjective nature of these terms. For example, while there may be widespread agreement about what constitutes undesirable outcomes (e.g. chronic stress, suicide), the range of positive outcomes for mental health (or well-being) are varied and multitudinous (to echo back to Whitman’s quote that started this report). A failure to account for such issues can introduce a further source of bias into the design of a system (e.g. how the problem it seeks to address is formulated) which in turn could lead to unfair outcomes that only benefit a small group of users with aligned goals.

The pattern that has been developed, through participation of stakeholders and users, attempts to address both negative and positive duties, while also making room for core attributes such as user autonomy. In the context of mental healthcare, this inclusion of autonomy can be problematic in the most severe cases where it is simply not viable (e.g. severe forms of psychosis). However, recall that a pattern is a starting point. Therefore, if a particular type of claim is inappropriate due to contextual factors that are determined during project scoping or stakeholder engagement, it can be adjusted as necessary. 

#### Why does this pattern matter?

In the last few years, many public authorities across the UK have released statements and policies calling for greater health equity.

In October 2020, NHS England released their '[Advancing mental health equalities](https://www.england.nhs.uk/publication/advancing-mental-health-equalities-strategy/)' strategy. This strategy...

The strategy also fed into a recent consultation on the [Mental health and wellbeing plan](https://www.gov.uk/government/consultations/mental-health-and-wellbeing-plan-discussion-paper-and-call-for-evidence/mental-health-and-wellbeing-plan-discussion-paper) by the Department for Health and Social Care.

The second of these publications makes reference to the UK Government's Levelling Up Strategy, which opens with the following statement:

> "not everyone shares equally in the UK’s success. While talent is spread equally across our country, opportunity is not. Levelling up is a mission to challenge, and change, that unfairness. Levelling up means giving everyone the opportunity to flourish. It means people everywhere living longer and more fulflling lives, and beneftting from sustained rises in living standards and well-being."

Beyond equality and non-discrimination, e.g. human rights and protected characteristics, we must also consider

> Risks of mental ill-health are also higher for people who are unemployed, people in problem debt, people who have experienced displacement, including refugees and asylum seekers, people who have experienced trauma as the result of violence or abuse, children in care and care leavers, people in contact with the criminal justice system (both victims and offenders), people who sleep rough or are homeless, people with substance misuse or gambling problems, people who live alone, and unpaid carers.

- Example assurance cases could be used in longer-term participatory forms of engagement where there is time to dig into details.

#### A pattern for designing, developing, and deploying fair digital mental health technologies

![A pattern for designing, developing, and deploying fair digital mental health technologies](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/fairness-pattern.png)
Figure 4.1 shows the full pattern, which can also be accessed [here](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=fairness-pattern.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1Os11GqD_Zh_a7mNrdV1XSNiDupC_4pPp%26export%3Ddownload).

The goal claim addresses distributional concepts of fairness (e.g. whether harms and benefits are shared equally), but also acknowledges that there are wider impacts that can emerge from the deployment and use of technological services (e.g. representational harms to marginalised groups). 

Unlike traditional safety cases, which often include  `System Description` and `Context of Use` placeholders, this pattern also includes a `Stakeholder` component to emphasise the importance of engagement. Here, the term 'stakeholder' should be treated in as inclusive a manner as possible, and not only the direct users of the technology.

The goal is then broken into four higher-level property claims and their respective sub-claims, which we group according to the following core attributes of the Fairness principle as specified and operationalised in the context of digital mental health technology:

* Argument over `bias mitigation`
* Argument over `non-exclusion`
* Argument over `non-discrimination`
* Argument over `equitable impact`

##### Argument over *bias mitigation*

This argument emphasises identification, evaluation, and mitigation activities. As there are too many biases to incorporate into a single pattern, this argument instead draws attention to transparent and accountable methods that allow stakeholders to determine if the set of biases that have been addressed are sufficient to address their concerns. This argument is supported by additional tools, such as a bias self-assessment tool that outlines social, statistical, and cognitive biases that can affect the lifecycle of a machine learning or AI system project.

##### Argument over *non-exclusion*

This argument sets out another negative duty to consider wider social impacts of digital technologies, and prompts developers to ensure they are not contributing to growing socioeconomic inequalities (i.e. the digital divide). In some instances, this may require nothing more than ensuring that UI/UX design choices do not exclude those who have additional accessibility requirements. However, the argument also sets up a duty to consider how a system being developed for use within a public healthcare syste, for example, does not create an unsustainbale multi-tiered approach, where some users are excluded from accessing a better performing technological service and forced to use comparatively inferior options.

##### Argument over *non-discrimination*

This argument addresses the better known obligations, such as ensuring that members of protected groups are not discriminated against. Much of the FairML literature, which has provided useful categorisations of formal criteria (i.e. independence, sufficiency, and separation) and the respective (statistical) notions of individual and group level fairness (e.g. demographic parity, equalised opportunities, counterfactual fairness) are relevant here. And, indeed, a requirement to explain the choice of any statistical measures used during the development of a predictive model (e.g. classifier) is included. Again, there are useful tools and taxonomies that offer further guidance on these decisions. However, our pattern also urges project teams to reflect upon other patterns of discrimination, marginalisation, and minoritisation, which can exacerbate mental health issues, but which fall beyond protected characteristics that lie outside the scope of the Equality Act (e.g. poverty, housing, employment). 

##### Argument over *equitable impact*

Finally, this argument references positive duties that matter in the context of digital mental health specifically. Key to this is the consideration of ethical values such as autonomy and self-determination, and the prioritarian weighting that was mentioned previously. However, there is also an aspect of our Sustainability principle that trickles into this argument. This is important in the context of digital mental healthcare because of associated risks that a) positive effects diminish over time (e.g. behavioural nudges that become ineffective over time)[^nudge] and b) negative impacts worsen and compound (e.g. prolonged use of social media worsening anxiety or depression)[^socialmedia]. Studies have already criticised the evidence base of mental health apps and services[^apps], so drawing attention to sustainable impacts and setting up requirements for continuos monitoring is important to maintain trust and also ensure that specific users are not locked in to services or technologies that degrade in quality or efficiacy over time (e.g. apps that start by offering free services to leverage network effects only to force subscriptions at a later date).

[^nudge]: See Maier et al. (2022) No evidence for nudging after adjusting for publication bias. PNAS. https://doi.org/10.1073/pnas.2200300119

[^socialmedia]: For a review published prior to the onset of the COVID-19 pandemic see Keles (2019) A systematic review: the influence of social media on depression, anxiety and psychological distress in adolescents. Adolescence and Youth. https://doi.org/10.1080/02673843.2019.1590851. For a range of studies that focus on the impacts of COVID-19 on mental health, including several that explore social media, see the [COVID-MINDS repository](https://www.covidminds.org/longitudinal-studies).

[^apps]: For example, see Torous et al. (2018). Clinical review of user engagement with mental health smartphone apps: Evidence, theory and improvements. Evidence Based Mental Health, 21(3), 116–119. https://doi.org/10.1136/eb-2018-102891; and the consensus statement that followed: Torous et al. (2019). Towards a consensus around standards for smartphone apps and digital mental health: Towards a consensus around standards for smartphone apps and digital mental health. World Psychiatry, 18(1), 97–98. https://doi.org/10.1002/wps.20592

### Explainability

Like fairness and equity, explainable AI has received a lot of attention over the last several years.[^explainableAI] Computer scientists have developed new tools and methods to improve the interpretability of otherwise opaque algorithms, such as neural networks.[^XAIreview] Researchers in psychology and human-computer interaction have explored how different components of the user experience can help support more intentional interactions with intelligent software agents.[^hci] And, regulators, auditors, and journalists have investigated how to make systems more transparent to support objectives related to accountability and informed decision-making.[^accountability]

[^explainableAI]: See the following notable publications: Phillips et al. (2021). Four Principles of Explainable Artificial Intelligence. National Institute of Standards and Technology. https://doi.org/10.6028/NIST.IR.8312;  Miller, T. (2019). Explanation in artificial intelligence: Insights from the social sciences. Artificial Intelligence, 267, 1–38. https://doi.org/10.1016/j.artint.2018.07.007; Diakopoulos, N. (2015).

[^XAIreview]: For a recent review of methods, see Linardatos, P., Papastefanopoulos, V., & Kotsiantis, S. (2020). Explainable AI: A Review of Machine Learning Interpretability Methods. Entropy, 23(1), 18. https://doi.org/10.3390/e23010018

[^hci]: Ferreira, J. J., & Monteiro, M. S. (2020). What Are People Doing About XAI User Experience? A Survey on AI Explainability Research and Practice. In A. Marcus & E. Rosenzweig (Eds.), Design, User Experience, and Usability. Design for Contemporary Interactive Environments (Vol. 12201, pp. 56–73). Springer International Publishing. https://doi.org/10.1007/978-3-030-49760-6_4

[^accountability]: Information Commisioner's Office & Alan Turing Institute. (2020). Explaining decisions made with AI. https://ico.org.uk/media/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisions-made-with-artificial-intelligence-1-0.pdf; Algorithmic Accountability: Journalistic investigation of computational power structures. Digital Journalism, 3(3), 398–415. https://doi.org/10.1080/21670811.2014.976411.

Therefore, much like fairness, explainability as a top-level goal encompasses a range of significant concerns and salient ethical values. Let's explore some of the these values in more detail, and see how they relate to digital mental health technologies.

#### Why does this pattern matter?

Data-driven technologies have the potential to automate decision-making to varying degrees. On the one hand, *decision support systems* can offer recommendations to users but are not responsible for enacting a decision directly. And, on the other hand, you have *fully automated-decision making systems*, which once set up require no human involvement. 

This distinction is admittedly coarse grained, but it will suffice for our purposes because it helps identify two illustrative cases where explainability matters. In the former case, although a human user is responsible for the decision, their judgement may be influenced and biased by the decision support system, potentially in ways that are problematic (e.g. leading to differential treatment for certain groups of users). In the latter case, no human is involved, but because the automated systems cannot be held morally or legally accountable for their decisions, if something goes wrong, a human will need to be able to identify the reason why the problem occurred and perhaps communicate this to other affected stakeholders.

In both of the above cases, extracting a valid and accurate explanation is necessary to enable post hoc forms of *accountability* or *transparency*. But prioritising ‘explainability’ from the start of a project also allows project teams to have better oversight of what their systems do and why, leading to more *responsible forms of project governance*. And, at the other end of the lifecycle, clear and accessible explanations can help ensure users and affected stakeholders are better *informed* and empowered to make *autonomous decisions* regarding their interactions with digital mental health technologies. Therefore, having an argument pattern for ‘explainability’ helps capture many of the key considerations that were raised during our workshops.

While the themes and values expressed in the following pattern are based primarily on the engagement with stakeholders, we have also drawn upon two other documents. First, we have drawn from prior guidance that we co-designed with the Information Commissioner’s Office.[^ico2020] This guide, titled 'Explaining Decisions Made with AI', details best practices for explainable AI in domain-general settings, and was also informed by stakeholder engagement. Second, we have incorporated some elements of an existing pattern for *interpretable* machine learning, which is motivated by a similar need for addressing a range of questions and concerns, such as the following:

> “who needs to understand the system, what they need to understand, what types of interpretations are appropriate, and when do these interpretations need to be provided”. [^ward2020]

[^ico2020]: Information Commisioner's Office & Alan Turing Institute. (2020). Explaining decisions made with AI. https://ico.org.uk/media/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisions-made-with-artificial-intelligence-1-0.pdf

[^ward2020]: Ward, F. R., & Habli, I. (2020). An Assurance Case Pattern for the Interpretability of Machine Learning in Safety-Critical Systems. In A. Casimiro, F. Ortmeier, E. Schoitsch, F. Bitsch, & P. Ferreira (Eds.), Computer Safety, Reliability, and Security. SAFECOMP 2020 Workshops (Vol. 12235, pp. 395–407). Springer International Publishing. https://doi.org/10.1007/978-3-030-55583-2_30

#### A pattern for designing, developing, and deploying explainable digital mental health technologies

![A pattern for designing, developing, and deploying explainable digital mental health technologies](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/explainability-pattern.png)

Figure 4.2 shows the full pattern, which can also be accessed [here](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=explainability-pattern.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1FgXz6DjJ8_eTPtIFfqojb40HwgJOxqjk%26export%3Ddownload).

In previous guidance, we have distinguished between two sub-categories of explanations:

1. *Process-based explanations* of AI systems are about demonstrating that you have followed good governance processes and best practices throughout your design and use.
2. *Outcome-based explanations* of AI systems are about clarifying the results of a specific decision. They involve explaining the reasoning behind a particular algorithmically-generated outcome in plain, easily understandable, and everyday language.

Both of these sub-categories inform our pattern, as well as the six associated explanation types and principles that the guidance recommends. However, to address the specific context of digital mental healthcare, we diverge from the framework presented in the guide while remaining consistent with its recommendations.

The goal claim addresses both sub-categories of explanation directly while also drawing attention to the different stages of the project lifecycle. The inclusion of this latter component sets an important foundation for where different explanation types and core attributes of explainability may be extracted and developed.

As with the fairness pattern, placeholders for `System Description` and `Context of Use` and `Stakeholder` are included.

The goal is then broken into four higher-level property claims and their respective sub-claims, which we group according to the following core attributes of the Explainability principle as specified and operationalised in the context of digital mental health technology:

* Argument over `transparency and accountability`
* Argument over `responsible project governance`
* Argument over `informed and autonomous decision-making`
* Argument over `sustainable impact`

##### Argument over *transparency and accountability*

This argument addresses the processes and mechanisms that have been undertaken throughout the project lifecycle to ensure adequate and meaningful forms of transparency and accountability. This includes explanations about the choices made during the collection, analysis, and use of data (e.g. why certain data types were included or excluded). Importantly, this argument also recommend the inclusion of a statement about sources of funding and conflicts of interest, as this was an important concern that arose during our engagement.

##### Argument over *responsible project governance*

This argument may appear more comprehensive than the others, but this is because it addresses the three over-arching stages of the project lifecycle model: (project) design, (model) development, (system) deployment. The second-level claims align with these stages, but refer directly to 'meaningful forms of participatory design and engagement', a 'responsible method of interpretability', and 'accessible forms of communication'. 

While engagement is emphasised for the first stage, this does not rule out the need for engagement or other forms of participation at later stages. For instance, the claim about sufficient levels of accuracy and the potential trade-off with interpretability could be informed by evidence from stakeholder engagement about what an acceptable threshold would be for such a trade-off. Similarly, what constitutes 'accessible' forms of communication will likely be informed by consultation with intended users and knowledge about any time-constraints presented by the context of use.

##### Argument over *informed and autonomous decision-making*

The core attribute motivating this argument is shared with our fairness pattern. Here, the argument emphasises the importance of explanations that refer to the observed behaviours or outcomes of the system. For instance, one of the claims is intended to ensure that explanations are sufficiently expressive, without overwhelming the user with unnecessary or overly-complex information. This will depend on the intended user and context of use. However, to supplement this claim, emphasis is also placed on the ability for user to challenge outcomes, rather than just having them explained.

##### Argument over *sustainable impact*

The final argument also follows the theme of the fairness pattern, but rather than addressing *equitable impact*, it focuses on *sustainable impact*. This is important because explanations are sometimes used as a means to justify why a specific norm was transgressed (e.g. why you were late). However, over time, if the same explanation is provided without a change to the offending behaviour, the explanation loses its validity. A similar risk is present in the automated delivery of explanations by algorithmic systems. For example, if an AI chatbot continues to offer the same inaccurate and irrelevant explanations, it is likely to lose the trust of a user. Therefore, assessments about the impact of explainable AI need to account for longer-term dynamics to ensure that the relevant systems are sustainable over time.

The inclusion of clinical safety and efficacy should not suggest that these goals are not significant in their own right. In fact, we would advocate for a separate assurance case (and corresponding pattern) on these goals specifically. Instead, reference is simply made to the need to ensure that some form of explanation is provided to stakeholders.