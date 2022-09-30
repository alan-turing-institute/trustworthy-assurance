---
authors:
  - Christopher Burr
tags:
  - fairness
  - explainability
  - argument-patterns
---
# Developing Trustworthy Assurance—Argument Patterns for fairness and Explainability

![Conceptual header image of people building an assurance case](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/ch5-header.png){ .off-glb }

> **Chapter Overview**
>
> In this chapter we present two argument patterns (i.e. starting templates for building assurance cases) that identify the types of claims, or the sets of reasons that need to be established to justify the associated top-level normative goal.
>
> The first pattern is for assurance cases that aim to justify the *fairness* of a DMHT. The second is for cases that address the *explainability* of systems.
>
> We also discuss relevant legislation, regulation, and best practice guidance that support and motivate the development of these patterns.

## Co-designing argument patterns

While the assurance methodology is a tool in its own right, there is a missing component that was highlighted in [Chapter 2](chapter-2.md): argument patterns.

You may recall that argument patterns are reusable structures that serve as *starting templates* for building assurance cases. They identify the *types* of claims (or, the sets of reasons) that need to be established to justify the associated top-level normative goal. And, in doing so, they set useful constraints on both the deliberative process and evidence-generating and evidence-gathering exercises. We say more about the evidential generation and selection process towards the end of this section.[^evidence]

[^evidence]: In a previous article we als explore several considerations about the evidence generation and selection process, including whether evidential artefacts are permissible, sufficient, and relevant. See Burr, C., & Leslie, D. (2022). Ethical assurance: A practical approach to the responsible design, development, and deployment of data-driven technologies. AI and Ethics. [https://doi.org/10.1007/s43681-022-00178-0](Burr, C., & Leslie, D. (2022). Ethical assurance: A practical approach to the responsible design, development, and deployment of data-driven technologies. AI and Ethics. https://doi.org/10.1007/s43681-022-00178-0)

Before this, we present and explain two argument patterns for use in the assurance of DMHTs. The first is for assurance cases that address and justify the *fairness* of a DMHT; the second is for cases that address and justify the *explainability* of systems.

!!! info "Why ‘fairness’ and ‘explainability’?"

    Our decision to focus on these two patterns is motivated primarily by the desire to capture the *significant* themes raised in the workshops. As such, the inclusion of a pattern for fairness is an obvious choice based on the discussions in the [previous chapter](chapter-4.md). However, the inclusion of one for the goal of explainability requires additional clarification.

    Many participants in our workshops focused on ethical issues that could map onto multiple SAFE-D principles. For instance, considerations around `transparency` were sometimes raised in connection with mechanisms for holding organisations `accountable` and at other times raised in connection with a requirement to ensure users had access to information to support informed consent and decision-making—captured either by `sustainability` or `explainability`. Our second argument pattern is framed in terms of `explainability` as an attempt to be maximally inclusive of these wide-ranging considerations. 

    To recall, argument patterns in trustworthy assurance are always *starting points* for participatory forms of reflection and deliberation. They provide greater specificity than the top-level goal would on its own, and help operationalise ethical principles within the project lifecycle model. But they are no substitute for embedded processes of inclusive stakeholder engagement—in fact, they depend upon stakeholder engagement processes for their completion. Furthermore, they should not be used as a mere checklist for compliance. 

    Finally, our focus on 'fairness' and 'explainability' should not suggest that other patterns are not desirable or important. Rather, the co-design and development of additional patterns, including those that go beyond the SAFE-D principles are left for future research (see Conclusion).

### Fairness

![An illustration showing varying performance and fidelity of a model's representation of people](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/representation-background.png){ .off-glb }

In the context of data-driven technologies, a core attribute of fairness is the equal distribution of risk and benefit across all groups of affected users. For instance, a technology that was highly accurate for users aged between 18-30 but became decreasingly accurate for older individuals would be unfair to those from higher age brackets.

The differentiation between risk and benefit leads to a subsequent distinction between corresponding duties or obligations (e.g. legal duties). Where there is a duty to ensure that a particular group of users are not exposed to disproportionate risks of harm, this can set up a so-called “negative duty” (e.g. a duty for a developer to not discriminate). However, negative duties often set only the minimal ethical standards. In other words, one can build a non-discriminatory service that does not harm anyone, but similarly benefits no one or benefits only a small portion of users.

Therefore, corresponding “positive duties” also exist to promote beneficial outcomes, sometimes focusing on those who are most disadvantaged—a so-called “prioritarian” approach to ethics (i.e. prioritising those who need the most support). A good example of this duality is the Public Sector Equality Duty, which sets the following objectives for all public authorities:

- eliminate discrimination, harassment, victimisation and any other conduct that is prohibited by or under the Equality Act 2010;
- advance equality of opportunity between persons who share a relevant protected characteristic and persons who do not share it;
- foster good relations between persons who share a relevant protected characteristic and persons who do not share it.

Notice that these objectives can be seen as having both negative and positive aspects to them (e.g. ‘eliminate discrimination’ as ‘opposed to advance equality’).[^posneg]

[^posneg]: We are not suggesting that this is the sole correct way of interpreting the public sector equality duty. Others may view the associated duties as entirely positive if they are viewed from a human rights lens that treats actively protecting people from risks of harm that are known about, or should have been known about, as a positive duty. The status of this duty will likely depend on which party it falls on, and how they are expected to discharge the duty.

In the context of mental healthcare, where stigmatisation prevents many vulnerable individuals from accessing care and discrimination exacerbates symptoms for already marginalised or minoritised groups, both types of duty are absolutely crucial. However, acting upon positive duties is not without its challenges.  

In our workshops, for instance, a key concern that was emphasised was the degree to which the delineation of "good" or "desirable" mental health outcomes, for the purpose of evaluating the impacts of a system, could adequately take into account the subjective nature of mental health and well-being. For instance, while there may be widespread agreement about what constitutes undesirable outcomes (e.g. chronic stress, suicide), the range of positive outcomes for mental health (or well-being) are varied and multitudinous (to echo back to Whitman’s quote that started this report), and the experience and process of recovery can also mean many different things to people[^recovery]. A failure to account for such issues can introduce a further source of bias into the design of a system (e.g. how the problem it seeks to address is formulated) which in turn could lead to unfair outcomes that only benefit a small group of users with aligned goals.

[^recovery]: For instance, a patient experiencing depression may be fully informed by their psychiatrist about their mental health and the options available to them in terms of recovery, but nevertheless, autonomously decide to forego any treatment because their condition may be an important part of their self-identity. This acknowledgment is part of the recovery approach, which views recovery as “a deeply personal, unique process of changing one’s attitudes, values, feelings, goals, skills, and/or roles. It is a way of living a satisfying, hopeful, and contributing life even with limitations caused by illness. Recovery involves the development of new meaning and purpose in one’s life as one grows beyond the catastrophic effects of mental illness.” W. A. Anthony, “Recovery from mental illness: The guiding vision of the mental health service system in the 1990s,” Psychosoc. Rehabil. J., vol. 16, no. 4, p. 527, 1993, doi: 10.1037/h0095655.

The pattern that has been developed, through participation of stakeholders and users, attempts to address both negative and positive duties, while also making room for core attributes such as user autonomy. In the context of mental healthcare, this inclusion of autonomy can be problematic in the most severe cases where it is simply not viable (e.g. severe forms of psychosis). However, recall that a pattern is a starting point or scaffold; it is not a checklist of *jointly sufficient claims and supporting evidence*. Therefore, if a particular type of claim is inappropriate due to contextual factors that are determined during project scoping or stakeholder engagement, it can be adjusted as necessary.

!!! info "Why does this pattern matter?"

    In recent years, many tools for improving and supporting the trustworthy and responsible development of DMHTs have been proposed. One key advancement is the [Digital Technology Assessment Criteria for Health and Social Care](https://transform.england.nhs.uk/key-tools-and-info/digital-technology-assessment-criteria-dtac/) (DTAC). This form provides guidance on assessing four technical components (in addition to a contextual component):

    1. Clinical safety
    2. Data protection
    3. Technical security
    4. Interoperability criteria

    While the DTAC is intended to supplement existing regulatory guidance, as well as sitting alongside current and developing legislation or compliance duties (e.g. [MHRA medical device registration](https://www.gov.uk/guidance/regulating-medical-devices-in-the-uk), [Equality Act 2010](https://www.legislation.gov.uk/ukpga/2010/15/contents), NICE's [Evidential Standards Framework](https://www.nice.org.uk/about/what-we-do/our-programmes/evidence-standards-framework-for-digital-health-technologies)), there is (at present) nothing in the DTAC about broader ethical issues such as the fair distribution of risk and benefits, or the requirement of explainable outcomes to support informed decision-making. As such, tools such as the DTAC serve a valuable but limited role in the assessment of fair DMHTs.

    In the last few years, however, many public authorities across the UK have released statements and policies calling for greater health equity. For instance, in October 2020, NHS England released their '[Advancing mental health equalities](https://www.england.nhs.uk/publication/advancing-mental-health-equalities-strategy/)' strategy, which also fed into a recent consultation on the [Mental health and wellbeing plan](https://www.gov.uk/government/consultations/mental-health-and-wellbeing-plan-discussion-paper-and-call-for-evidence/mental-health-and-wellbeing-plan-discussion-paper) by the Department for Health and Social Care.

    The second of these publications makes reference to the UK Government's Levelling Up Strategy, which opens with the following statement:

    > "not everyone shares equally in the UK’s success. While talent is spread equally across our country, opportunity is not. Levelling up is a mission to challenge, and change, that unfairness. Levelling up means giving everyone the opportunity to flourish. It means people everywhere living longer and more fulflling lives, and beneftting from sustained rises in living standards and well-being."

    Beyond people who share protected characteristics as set out in the Equality Act 2010, there are other groups who require specific consideration[^wachter]:

    > Risks of mental ill-health are also higher for people who are unemployed, people in problem debt, people who have experienced displacement, including refugees and asylum seekers, people who have experienced trauma as the result of violence or abuse, children in care and care leavers, people in contact with the criminal justice system (both victims and offenders), people who sleep rough or are homeless, people with substance misuse or gambling problems, people who live alone, and unpaid carers.
    
    [^wachter]: This is further problematised in the context of ML and AI, where novel forms of discrimination, perhaps as a result of so-called "affinity profiling". See Wachter, S. (2021). Affinity Profiling and Discrimination by Association in Online Behavioural Advertising. Berkeley Technology Law Journal, 35(2).

    And, finally, a recent publication by the UK's Office for AI has also called for regulators to "embed considerations of fairness into AI", but have further specified this principle as follows:

    > - interpret and articulate ‘fairness’ as relevant to their sector or domain,
    > - decide in which contexts and specific instances fairness is important and relevant (which it may not always be), and
    > - design, implement and enforce appropriate governance requirements for ‘fairness’ as applicable to the entities that they regulate.
 
    Therefore, there is clear regulatory appetite and industry need for both domain-specific and cross-cutting guidance on how to embed considerations of fairness and equality into the design, development, and deployment of digital technologies.

#### Fairness Pattern

![A pattern for designing, developing, and deploying fair digital mental health technologies](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/patterns/fairness-pattern-final.png)

*Figure 4.1: A pattern for designing, developing, and deploying fair digital mental health technologies* (:material-magnify-plus: click image to expand; :material-download: download [here](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/patterns/fairness-pattern-final.png))

The goal claim in this argument pattern addresses distributional concepts of fairness (e.g. whether harms and benefits are shared equally), while also acknowledging broader conceptions of social justice (e.g. representational harms to marginalised groups). 

Unlike traditional safety cases, which often include  `System Description` and `Context of Use` placeholders, this pattern also includes a `Stakeholder` component to emphasise the importance of engagement. Here, the term 'stakeholder' should be treated in as inclusive a manner as possible, and not only the direct users of the technology.

The goal is broken into four higher-level property claims and their respective sub-claims, which we group according to the following core attributes of the Fairness principle as specified and operationalised in the context of digital mental healthcare:

- Argument over `bias mitigation`
- Argument over `non-exclusion`
- Argument over `non-discrimination`
- Argument over `equitable impact`

##### Argument over *bias mitigation*

This argument emphasises identification, evaluation, and mitigation activities. As there are too many biases to incorporate into a single pattern, this argument instead draws attention to transparent and accountable methods that allow stakeholders to determine if the set of biases that have been addressed are sufficient to address their concerns. This argument is supported by additional tools, such as a bias self-assessment tool that outlines social, statistical, and cognitive biases that can affect the lifecycle of a machine learning or AI system project.[^bias-assessment]

[^bias-assessment]: See our course on responsible research and innovation for more details about social, statistical, and cognitive biases: [https://alan-turing-institute.github.io/turing-commons/rri/](https://alan-turing-institute.github.io/turing-commons/rri/)

##### Argument over *non-exclusion*

This argument sets out another negative duty to consider wider social impacts of digital technologies, and prompts developers to ensure they are not contributing to growing socioeconomic inequalities (i.e. the digital divide) by overlooking important social determinants (e.g. education, poverty). In some instances, this may require nothing more than ensuring that UI/UX design choices do not exclude those who have additional accessibility requirements. However, the argument also sets up a duty to consider how a system being developed for use within a public healthcare system, for example, does not create an unsustainable multi-tiered approach, where some users are excluded from accessing a better performing technological service and forced to use comparatively inferior options.

##### Argument over *non-discrimination*

This argument addresses the better known obligations, such as ensuring that members of protected groups are not discriminated against. Much of the FairML literature, which has provided useful categorisations of formal criteria (i.e. independence, sufficiency, and separation) and the respective (statistical) notions of individual and group level fairness (e.g. demographic parity, equalised opportunities, counterfactual fairness) are relevant here. And, indeed, a requirement to explain the choice of any statistical measures used during the development of a predictive model (e.g. classifier) is included. Again, there are useful tools and taxonomies that offer further guidance on these decisions. However, our pattern also urges project teams to reflect upon other patterns of discrimination, marginalisation, and minoritisation, which can exacerbate mental health issues, but which fall beyond protected characteristics that lie outside the scope of the Equality Act 2010 (e.g. housing, employment, social support). Doing so will typically require engagement of domain experts where such expertise does not exist within teams.

##### Argument over *equitable impact*

Finally, this argument references positive duties that matter in the context of digital mental healthcare specifically. Key to this is the consideration of ethical values such as autonomy and self-determination, and the prioritarian weighting that was mentioned previously. However, there is also an aspect of our Sustainability principle that trickles into this argument. This is important in the context of digital mental healthcare because of associated risks that a) positive effects diminish over time (e.g. behavioural nudges or habit forming techniques that become ineffective over time)[^nudge] and b) negative impacts worsen and compound (e.g. prolonged use of social media worsening anxiety or depression)[^socialmedia]. Studies have already criticised the evidence base of mental health apps and services[^apps], especially for a lack of reliable longitudinal evidence, so drawing attention to sustainable impacts and setting up requirements for continuous monitoring is vital to maintain trust and also ensure that specific users are not locked in to services or technologies that degrade in quality or efficacy over time (e.g. apps that start by offering free services to leverage network effects only to force subscriptions at a later date).

[^nudge]: See Maier et al. (2022) No evidence for nudging after adjusting for publication bias. PNAS. https://doi.org/10.1073/pnas.2200300119

[^socialmedia]: For a review published prior to the onset of the COVID-19 pandemic see Keles (2019) A systematic review: the influence of social media on depression, anxiety and psychological distress in adolescents. Adolescence and Youth. https://doi.org/10.1080/02673843.2019.1590851. For a range of studies that focus on the impacts of COVID-19 on mental health, including several that explore social media, see the [COVID-MINDS repository](https://www.covidminds.org/longitudinal-studies).

[^apps]: For example, see Torous et al. (2018). Clinical review of user engagement with mental health smartphone apps: Evidence, theory and improvements. Evidence Based Mental Health, 21(3), 116–119. https://doi.org/10.1136/eb-2018-102891; and the consensus statement that followed: Torous et al. (2019). Towards a consensus around standards for smartphone apps and digital mental healthcare: Towards a consensus around standards for smartphone apps and digital mental healthcare. World Psychiatry, 18(1), 97–98. https://doi.org/10.1002/wps.20592

### Explainability

![An illustration of a healthcare professional explaining an automated decision to patients](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/public-trust.png){ .off-glb }

Much like fairness, explainability has become a popular and thriving area of research (e.g. so-called XAI). And, also like fairness, it is a normative goal that encompasses a range of significant concerns and salient ethical values.

The most obvious conceptual distinction is between `interpretability` as a core component of `explainability`. Whereas the former is to often treated as the ability for developers or users to understand the inner workings of algorithms (or inability in the case of complex, non-linear techniques), the latter refers to an interpersonal ability to communicate knowledge in a manner that is accessible to those who may be asking questions about a system (e.g. patients asking for explanations from a clinician). Although statistical techniques help significantly in the case of the former, they are more limited in their ability to support the latter where a more diverse range of users are likely.

!!! info "Why does this pattern matter?"

    Explainable AI has received a lot of attention over the last several years.[^explainableAI] Computer scientists have developed new tools and methods to improve the interpretability of otherwise opaque algorithms, such as neural networks.[^XAIreview] Researchers in psychology and human-computer interaction have explored how different components of the user experience can help support more intentional interactions with intelligent software agents.[^hci] And, regulators, auditors, and journalists have investigated how to make systems more transparent to support objectives related to accountability and informed decision-making.[^accountability]
    
    Much of this attention arises from the recognition that data-driven technologies have the potential to automate decision-making to varying degrees and, therefore, affect key ethical values and principles such as autonomy, accountability, responsibility, and informed consent. On the one hand, *decision support systems* can offer recommendations to users but are not responsible for enacting a decision directly. And, on the other hand, you have *fully automated-decision making systems*, which once set up require no human involvement.
    
    This distinction is admittedly coarse grained, but it will suffice for our purposes because it helps identify two illustrative cases where explainability matters. In the former case, although a human user is responsible for the decision, their judgement may be influenced and biased by the decision support system, potentially in ways that are problematic (e.g. leading to differential treatment for certain groups of users). In the latter case, no human is involved, but because the automated systems cannot be held morally or legally accountable for their decisions, if something goes wrong, a human will need to be able to identify the reason why the problem occurred and perhaps communicate this to other affected stakeholders.

    In both of the above cases, extracting a valid and accurate explanation is necessary to enable post hoc forms of *accountability* or *transparency*. But prioritising ‘explainability’ from the start of a project also allows project teams to have better oversight of what their systems do and why, leading to more *responsible forms of project governance*. And, at the other end of the lifecycle, clear and accessible explanations can help ensure users and affected stakeholders are better *informed* and empowered to make *autonomous decisions* regarding their interactions with DMHTs. Therefore, having an argument pattern for ‘explainability’ helps capture many of the key considerations that were raised during our workshops.

    While the themes and values expressed in the following pattern are based primarily on the engagement with stakeholders, we have also drawn upon two other documents. First, we have drawn from prior regulatory guidance that we co-designed with the Information Commissioner’s Office. This guide, titled 'Explaining Decisions Made with AI', details best practices for explainable AI in domain-general settings, and was also informed by stakeholder engagement. The regulatory ecosystem around explainability is less developer than fairness and equality, but as this report acknowledges there are still legislative and regulatory considerations that organisations need to consider, such as the wide-range of rights established by the General Data Protection Regulation and implemented in the UK's Data Protection Act 2018, such as the need to uphold individuals rights to be informed or to object to automated decisions.[^ico2020]
    
    Second, we have incorporated some elements of an existing pattern for *interpretable* machine learning[^ward2020], which is motivated by a similar need for addressing a range of questions and concerns, such as the following:

    > “who needs to understand the system, what they need to understand, what types of interpretations are appropriate, and when do these interpretations need to be provided” (Ward and Habli, 2020).

    [^explainableAI]: See the following notable publications: Phillips et al. (2021). Four Principles of Explainable Artificial Intelligence. National Institute of Standards and Technology. https://doi.org/10.6028/NIST.IR.8312;  Miller, T. (2019). Explanation in artificial intelligence: Insights from the social sciences. Artificial Intelligence, 267, 1–38. https://doi.org/10.1016/j.artint.2018.07.007; Diakopoulos, N. (2015).

    [^XAIreview]: For a recent review of methods, see Linardatos, P., Papastefanopoulos, V., & Kotsiantis, S. (2020). Explainable AI: A Review of Machine Learning Interpretability Methods. Entropy, 23(1), 18. https://doi.org/10.3390/e23010018

    [^hci]: Ferreira, J. J., & Monteiro, M. S. (2020). What Are People Doing About XAI User Experience? A Survey on AI Explainability Research and Practice. In A. Marcus & E. Rosenzweig (Eds.), Design, User Experience, and Usability. Design for Contemporary Interactive Environments (Vol. 12201, pp. 56–73). Springer International Publishing. https://doi.org/10.1007/978-3-030-49760-6_4

    [^accountability]: Information Commisioner's Office & Alan Turing Institute. (2020). Explaining decisions made with AI. https://ico.org.uk/media/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisions-made-with-artificial-intelligence-1-0.pdf; Algorithmic Accountability: Journalistic investigation of computational power structures. Digital Journalism, 3(3), 398–415. https://doi.org/10.1080/21670811.2014.976411.

    [^ico2020]: Information Commisioner's Office & Alan Turing Institute. (2020). Explaining decisions made with AI. https://ico.org.uk/media/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisions-made-with-artificial-intelligence-1-0.pdf

    [^ward2020]: Ward, F. R., & Habli, I. (2020). An Assurance Case Pattern for the Interpretability of Machine Learning in Safety-Critical Systems. In A. Casimiro, F. Ortmeier, E. Schoitsch, F. Bitsch, & P. Ferreira (Eds.), Computer Safety, Reliability, and Security. SAFECOMP 2020 Workshops (Vol. 12235, pp. 395–407). Springer International Publishing. https://doi.org/10.1007/978-3-030-55583-2_30

#### Explainability Pattern

![A pattern for designing, developing, and deploying explainable digital mental health technologies](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/patterns/explainability-pattern-final.png)

*Figure 4.2: A pattern for designing, developing, and deploying explainable digital mental health technologies* (:material-magnify-plus: click image to expand, :material-download: download [here](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/patterns/explainability-pattern-final.png))

In previous guidance[@ico2020], we have distinguished between two sub-categories of explanations:

1. *Process-based explanations* of AI systems are about demonstrating that you have followed good governance processes and best practices throughout your design and use.
2. *Outcome-based explanations* of AI systems are about clarifying the results of a specific decision. They involve explaining the reasoning behind a particular algorithmically-generated outcome in plain, easily understandable, and everyday language.

These categories are reflected in our pattern, where they form 'intermediate arguments' that help refine the goal claim and also serve as scaffolding for the main arguments.

As with the fairness pattern, placeholders for `System Description` and `Context of Use` and `Stakeholder` are also included.

The intermediate arguments are then broken into four higher-level property claims and their respective sub-claims, which we group according to the following core attributes of the Explainability principle as specified and operationalised in the context of digital mental healthcare:

- Argument over `transparency and accountability`
- Argument over `responsible project governance`
- Argument over `informed and autonomous decision-making`
- Argument over `sustainable impact`

##### Argument over *transparency and accountability*

This argument addresses the processes and mechanisms that have been undertaken throughout the project lifecycle to establish sufficient forms of transparency and accountability. This includes documentation relevant to the identification of responsible project members, as well as choices made about data (e.g. why certain data types were included or excluded). Importantly, this argument also recommends the inclusion of a statement about sources of funding and conflicts of interest, which was an important matter for trustworthiness that arose during our engagement with participants with lived experience of DMHTs.

##### Argument over *responsible project governance*

This argument is more comprehensive than the others, and so is further split into three sub-arguments:

1. Sub-argument over meaningful engagement: here, meaningful engagement can be seen to include participation in decisions about the formulation of the problem that a DMHT is expected to address, as well as issues of data usage—both of which affect later stages of the project lifecycle and the final behaviour of the deployed system.
2. Sub-argument over interpretability: sufficient levels of accuracy and the potential trade-off with interpretability can require high levels of technical and data literacy Therefore, this argument focuses on the requisite information that is needed to support explainability (recall earlier distinction between `interpretability` and `explainability`).
3. Sub-argument over accessible communication: the previous sub-argument feeds into this sub-argument, which focuses on how 'accessible' forms of communication will achieved, and the challenges of communicating probabilistic information. Ultimately, this sub-argument will depend on decisions reached and evidence obtained through consultation with intended users, as well as on the basis of knowledge about any time-constraints presented by the context of use (e.g. urgency in high-risk care environments).

##### Argument over *informed and autonomous decision-making*

The core attribute motivating this argument is shared with our fairness pattern. Here, the argument emphasises the importance of explanations that refer to the observed behaviours or outcomes of the system. For instance, one of the claims is intended to ensure that explanations are "sufficiently expressive", without overwhelming the user with unnecessary or overly-complex information. This will depend on the intended user and context of use. However, to supplement this claim, emphasis is also placed on the ability for user to challenge outcomes, rather than just having them explained without an option to contest.

##### Argument over *sustainable impact*

The final argument also follows the theme of the fairness pattern, but rather than addressing *equitable impact*, it focuses on *sustainable impact*[^sustainable]. This is important because explanations are sometimes used as a means to justify why a specific norm was transgressed (e.g. why you were late). However, over time, if the same explanation is provided without a change to the offending behaviour, the explanation loses its validity. A similar risk is present in the automated delivery of explanations by algorithmic systems. For example, if an AI chatbot continues to offer the same inaccurate and irrelevant explanations, it is likely to lose the trust of a user. Therefore, assessments about the impact of explainable AI need to account for longer-term dynamics to ensure that the relevant systems are sustainable over time.

[^sustainable]: Not to be confused with the related SAFE-D principle, 'Sustainability'.

The inclusion of clinical safety and efficacy should not suggest that these goals are not significant in their own right. In fact, we would advocate for a separate assurance case (and corresponding pattern) on these goals specifically. Instead, reference is simply made to the need to ensure that some form of explanation is provided to stakeholders.

### Evidential Considerations

Neither of the patterns above include prescriptions about specific evidential artefacts that could be used to ground the assurance case. There are two reasons for this intentional omission:

1. Prescribing specific forms of evidence is too difficult outside of highly constrained contexts where there are clear details about a) the intended use context, b) the type of ML/AI technique being used, and c) the intended users and target audience.
2. Developers and regulators should be free to determine the appropriate forms of evidence, based on developing best practices and standards, many of which do not exist at present.

However, there are a couple of general remarks that can be made, as well as some suggestions for further resources.

First, as we have argued elsewhere[@burr_ethical_2022], the generation, evaluation, and selection of evidence can be guided by the following considerations:

1. Is the evidential artefact/claim *relevant* to the parent claim
2. Is the evidential artefact/claim (or set of artefacts/claims) *sufficient* to justify the parent claim?
3. Is there sufficient *probative value* in the overall assurance case to justify the top-level normative goal?

Outside of the regulatory considerations already mentioned above, there have been several developments in recent years to help organisations address these considerations. Some examples (among many) include:

- [Model Cards for Model Reporting](https://modelcards.withgoogle.com/about): templates for model documentation, which include ethical considerations alongside statistical information to support reuse.
- [Responsible AI Licensing](https://www.licenses.ai/): licenses that help developers restrict the use of their AI technology in order to prevent irresponsible and harmful applications.
- [Data Hazards](https://datahazards.com/): a set of labels that enable project members to make decisions about the risks of data-driven technologies using a shared vocabulary
- [Assurance of Machine Learning in Autonomous Systems (AMLAS)](https://www.york.ac.uk/assuring-autonomy/guidance/amlas/): a methodology for assuring the safety of ML systems, with systematic means for evaluating processes such as model testing or verification.
- [Algorithmic Transparency Standard](https://www.gov.uk/government/collections/algorithmic-transparency-standard): a template for organisations to use when choosing to publish information about how they are using algorithmic systems to aid decision-making.

Typically, these tools, methods, or templates exist to help organisations and project teams address a specific challenge (e.g. licensing, model documentation). The framework and methodology we have presented in this report is designed to work alongside these tools, but it also goes further by helping teams organise them according to a particular goal or objective (e.g. fairness). As such, our framework and methodology is broader in scope and offers a systematic means for choosing when to use specific tools throughout a project's lifecycle and how to bring the documented evidence together to create a trustworthy and justifiable assurance case.
