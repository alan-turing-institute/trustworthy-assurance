---
authors:
  - Christopher Burr
  - Rosamund Powell
tags:
  - culture-of-distrust
  - landscape
  - digital-mental-healthcare
---

# Introduction

![Illustration of people walking along various intersecting paths in an abstract space](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/ch1-header.jpg){ .off-glb }

!!! warning "Navigating this Chapter"

    This introduction starts with (optional) contextual information and discussion. Those who wish to read only the information that pertains directly to the project should skip to [this section](#about-the-project).

> Do I contradict myself? Very well then I contradict myself, (I am large, I contain multitudes.) --Walt Whitman, Song of Myself

Whitman's ode to self-knowledge and understanding contains many poetically-phrased truths. However, the one expressed in the above line is an *understatement*. If we were to identify and rank the most complex phenomena in the universe, our large and multitudinous minds would sit somewhere near the top of the list!

Even the most stubborn among us must acknowledge that part of this complexity stems from a capacity for our minds to operate as a network of often *contradictory beliefs, attitudes, and opinions*—a network that exists within and among a larger social network of similarly fallible individuals. It would be understandable, therefore, given this reflection, if we came to the conclusion that our minds were never supposed to be understood fully and we just accepted, as Whitman did, that our mental lives are fundamentally contradictory and diverse, and sometimes none the worse for it.

For many people, a prescription of stoic acceptance in the face of overwhelming complexity would be welcomed. But for others, their minds are not just built on top of permissible and tolerable contradictions, they also operate in a manner that prevents them from living a fully self-determined and flourishing life.

In the last decade or so, a wide range of digital and data-driven technologies have emerged that promise to improve both our knowledge and understanding of our complex minds and its capabilities, as well as enhance our overall well-being. This fact is unsurprising. Our species has used technology to learn about and restructure both our external and internal worlds for hundreds of thousands of years. And during our time on this planet, technology has both enhanced and diminished our knowledge, understanding, and individual and social welfare. So, why has so much attention been paid in recent years to a recurring cycle of technological innovation?

## Laying the Foundations

Towards the start of the 21st Century, a convergence of several social and technical factors gave rise, first, to an interest in the big data revolution, and, second, to a renewed interest in Machine Learning (ML) and Artificial Intelligence (AI). Let's look at each of these briefly, as they help establish important and explanatory context for this report.

The big data revolution occurred as a result of increased and widespread use of Internet of Things (IoT) or mobile devices (i.e. the sources of data); availability of affordable cloud computing infrastructure (i.e. for extracting, loading, and transforming the data); and ongoing development of open-source frameworks and software libraries for more efficient and distributed data storage and analysis (e.g. Apache Hadoop, Python), among other factors.

To help differentiate *big* data from ordinary data collection, analysis, and use, many have pointed to the five V's of big data:

* Volume: the *amount* of data being extracted
* Variety: the *types* of data being extracted
* Velocity: the *speed* at which data is extracted
* Value: the *socioeconomic benefit* of data
* Veracity: the *accuracy* of data

In the context of digital mental healthcare, all of these are noteworthy, but three stand out against the backdrop of this report's opening remarks regarding the complex phenomena of interest (our minds):

1. How **accurate** are the data we are now collecting, analysing, and using?
2. Given the **variety** of minds that populate this plant, how representative are the types of data?
3. How much of a gap is there between the socioeconomic **value** of data and the value to the individual who is represented by the data? Or, to put it more bluntly, who benefits from the data?

We (the authors) have heard and discussed many variants of these questions over the course of this project. For example, concerns about accuracy and variety are deeply connected to considerations around the regulatory assessment of clinical efficacy and safety for novel data-driven medical devices.[^regulatory] But more than this, accuracy and variety also underpin broader ethical concerns about existing barriers to enabling a fairer and more accessible healthcare system (e.g. the digital divide that systematically excludes certain people and groups from benefits associated with digital technologies). However, although data are important, addressing these questions is just one part of the puzzle.

[^regulatory]: See for example, the work programme being conducted by the Medicines & Healthcare Regulatory Agency (MHRA) on [Software and AI as a Medical Device](https://www.gov.uk/government/publications/software-and-ai-as-a-medical-device-change-programme/software-and-ai-as-a-medical-device-change-programme), the [Evidence standards framework](https://www.nice.org.uk/about/what-we-do/our-programmes/evidence-standards-framework-for-digital-health-technologies) (ESF) for digital health technologies from the National Institute for Health and Care Excellence (NICE), and the proposed work from the [Multi-agency advisory service](https://transform.england.nhs.uk/ai-lab/ai-lab-programmes/regulating-the-ai-ecosystem/the-multi-agency-advice-service-maas/) (MAAS) for artificial intelligence (AI) and data-driven technologies, which is being funded by the [NHS AI Lab](https://transform.england.nhs.uk/ai-lab/).

Turning to the technologies themselves—another significant piece—we can similarly identify several explanatory factors behind the recent surge of interest in machine learning algorithms (ML) and artificial intelligence (AI). Developments in this domain build on top of the aforementioned factors behind the big data revolution—ML and AI are, after all, sometimes referred to as '*data-driven* technologies':

* Theoretical advances in machine learning for robotics and intelligent software agents (e.g. DeepMind's Alpha Go)
* Improved application of deep neural networks to well-defined tasks such as medical imaging or speech detection
* Hardware improvements in specialised computer processor architectures to allow for more efficient and effective edge computing

All of these developments are important, but again there are three aspects that stand out as significant:

1. The ability for ML/AI systems to operate *autonomously*
2. The ability for ML/AI systems to *learn from* their environments
3. The ability for ML/AI systems to *adapt to* and *affect* their environments

As we will see throughout this report, these features of ML algorithms and AI systems create possible risks and benefits to the realisation of ethical goals associated with digital mental healthcare. For instance, the ability to respect a patients *right to autonomous decision-making*.
Furthermore, these issues intersect with the issues raised by the previous three questions pertaining to data (e.g. the ability to operate autonomously in complex environments with insufficiently accurate data).

These topics already paint a very complex picture, but there is also a further level of complexity involved with understanding the dynamic feedback loops that emerge in mental healthcare when autonomous and adaptive systems are used to complement existing therapeutic interventions, many of which are already poorly understood (e.g. Selective Serotonin Reuptake Inhibitors). This complexity can cause issues for our existing research, development, and regulatory frameworks, such as when performing clinical trials (e.g. how should we control for the effects of adaptive and personalised technologies?).

Collectively, these six points about Big Data and ML/AI help to establish the background and context for this report, and also help us gain some conceptual clarity when attempting to address the uncertainty around trustworthy DMHTs. Some of this uncertainty stems from the technologies themselves (as noted above). But other key aspects of this uncertainty arise because a) the concept ‘trustworthy digital mental health technology’ is a poorly defined term[^trust] that captures a vast and heterogeneous class of tools and services, and b) our relationships to and interactions with the technologies are also varied. It is not just the technologies that are complex after all. As eloquently captured by Whitman at the start, we—the individual members of the class, 'humanity'—are large and contain multitudes.

[^trust]: For the purpose of this report we use the term 'trust' to refer to those characteristics of a person's beliefs or attitudes that are directed towards an object, person, or proposition (among other things), whereas 'trustworthiness' refers to the perceived property or attribute which an individual uses to determine whether to place trust (e.g. whether to trust a news article based on its quoted sources).

These many layers of complexity coalesce into a particularly thorny problem. If we cannot trust the technologies themselves, we will not be able to trust the information gained from them about our own minds. But if we do not understand our minds, we may be unable to fully determine and address the cause of our trust or distrust. And, as we have just noted, understanding the social environment is also a vital part of addressing this fundamentally sociotechnical problem. As you can probably guess by know, adding another element to our picture is not likely to reduce its complexity.

## The Current (Socioeconomic) Landscape of Digital Mental Healthcare

To explore and understand the socioeconomic landscape of digital mental healthcare, let us start by addressing two outstanding questions:

1. What is meant by 'digital mental healthcare technology'?
2. Why and how are 'digital mental healthcare technologies' being used?

### What are digital mental health technologies?

This is not an easy question to answer because of the multifaceted ways that the term 'digital mental health technology' could be employed.

We can attempt to answer the question by drawing distinctions between, say, the use of digital technologies within formal healthcare settings (e.g. NHS) and those outside. However, as we have explored in previous research[^burr2020], this boundary is vaguely drawn at best, and unhelpful at worst, when it comes to understanding DMHTs and the ethical issues surrounding their design and use.

[^burr2020]: Burr, C., J. Morley, M. Taddeo, & L. Floridi. (2020). Digital Psychiatry: Risks and Opportunities for Public Health and Wellbeing. IEEE Transactions on Technology and Society, 1(1), 21–33. https://doi.org/10.1109/TTS.2020.2977059

One reason for this is that outside of formal healthcare systems, DMHTs have been employed in social domains and contexts as diverse as financial services, education (e.g. schools and universities), and employment. And, furthermore, DMHTs have been used within such domains for myriad purposes ranging from vulnerability assessment through to proactive intervention[^burr2020]. There is also the use of DMHTs by social media platforms and charities to consider, which tends to cross many of these boundaries, especially those between work and home life, making it difficult to draw useful distinctions unless a narrow focus is defined in advance (e.g. studying the use of NLP used for risk assessment of adolescents on social media)[^conversation].

[^conversation]: We explored this point more fully in a separate article: Burr, C. (2022). Charities are contributing to growing mistrust of mental-health text support—Here’s why. The Conversation. Retrieved 29 July 2022, from [http://theconversation.com/charities-are-contributing-to-growing-mistrust-of-mental-health-text-support-heres-why-179056](http://theconversation.com/charities-are-contributing-to-growing-mistrust-of-mental-health-text-support-heres-why-179056)

What about focusing on the technologies themselves? Again, this is not an easy feat. Some organisations, such as the Nuffield Council on Bioethics have focused on *emerging* technologies to narrow their scope [^Nuffield]. In doing so, they have identified specific ethical challenges associated with the following class of technologies:

* Smartphone apps and chatbots
* Predictive analytics (e.g. based on digital phenotyping)
* Consumer neurotechnology (e.g. portable electroencephalography devices)
* Immersive technology (e.g. VR)

[^Nuffield]: Nuffield Council on Bioethics (2022) The role of technology in mental healthcare. [https://www.nuffieldbioethics.org/assets/pdfs/The-role-of-technology-in-mental-healthcare.pdf](https://www.nuffieldbioethics.org/assets/pdfs/The-role-of-technology-in-mental-healthcare.pdf)

But none of these categories are suitable for building a definition of DMHTs writ large. For instance, let's look at so-called "digital phenotyping"—an increasingly popular area of digital mental healthcare—, defined as follows:

> We also introduce the term “digital phenotyping” to refer to the “moment-by-moment quantification of the individual-level human phenotype in-situ using data from smartphones and other personal digital devices.”[^torous]

[^torous]: Torous et al. (2016) New Tools for New Research in Psychiatry: A Scalable and Customizable Platform to Empower Data Driven Smartphone Research. JMIR Ment Health. [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4873624/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4873624/)

Putting aside the previously raised data challenges associated with the "quantification of the individual-level human phenotype" (e.g. how to construct *accurate* scales that apply to all *varied* people while retaining *value*), there is also wide variation between 'smartphones' and 'other personal digital devices', such as wearables. For instance, some smartphone apps may use advanced forms of machine learning algorithms or AI to infer novel attributes regarding a user's mental health. And, others may offer nothing more than a simple interface and database for users to record how they are feeling at a particular time or on a particular day. Furthermore, some wearables may store and process sensitive information locally on a user's device, whereas others may store data on the cloud and share health-related information with a vast number of organisations across jurisdictions with varying levels of data protection.

What about if we move to a lower level of abstraction, such as the algorithmic technique used by the digital technology? Here too we would find difficulties with delineating the meaning of the term ‘digital mental health technology’. For example, the use of *unsupervised machine learning* by trusted clinical researchers may be justified if used responsibly as a form of exploratory research or hypothesis generation. But, if a complex version of the technique were deployed by a local council to determine how best to spend limited resources (e.g. resulting in clusters that were not clearly interpretable by humans), the potential lack of transparency could undermine efforts to remain accountable to their residents.

Regardless of the level of abstraction we adopt, there will always be some difficulty with clearly defining this nebulous term. Therefore, while it may seem unsatisfying to a reader who wishes to know *precisely* what the term 'digital mental health technology' comprises, for our present purposes the following (loose and permissive) definition shall suffice:

> The term 'digital mental health technology' refers to any digital technology that has been designed, developed, and deployed with the goal of improving or otherwise impacting some mental health outcome for an individual or group of people.

In particular, this report will pay close attention to those technologies that are data-driven and/or use some form of machine learning or AI, given the considerations outlined in the opening sections.

We acknowledge that many will find this definition too permissive, but this report is not concerned with developing a robust philosophical definition or a taxonomy that can be used to delineate the precise nature of DMHTs. Rather, it is focused on the defence of a methodology to help make DMHTs more trustworthy and ethical. Therefore, the broader the class that can be drawn the better it will be for our goals, because more technologies will fall within its scope[^examples]. And, insofar as there are legal considerations that demand precise definitions, these issues will be addressed along different lines (e.g. operationalising standards of assessment for equitable treatment).

[^examples]: For instance, if we draw the class as comprising digital technologies for "health and well-being" we will capture technologies as diverse as ML algorithms used to identify associations between genetic factors and mental health outcomes, to mobile apps that use natural language processing techniques to help users better understand their feelings through a smart diary.

!!! info "Examples"

    A set of illustrative examples of DMHTs can be found on [this page](appendix-2.md).

Let us now turn to the second question.

### Why and how are digital mental healthcare technologies being used?

The following statistics offer a partial and fragmented perspective to help frame this question, focusing on the UK specifically:

* Over 60% of children and young people with diagnosed mental health conditions do not receive NHS care.[^nhs]
* Rates of probable mental health disorders in children and young people (aged 6 to 16 years) have risen from 11.6% in 2017 to 17.4% in 2021.[^nhs2]
* Approximately two-thirds of people who die by suicide are not in contact with NHS mental health services.[^ons]
* In the first 3 months of 2021, 1 in 5 adults in Britain experienced some form of depression (over double the pre-pandemic figures).[^ons2]
* During the pandemic both males and females saw an increase in anxiety and a reduction in 'life satisfaction'—a subjective measure of well-being that asks individuals to evaluate their life as a whole, rather than time-specific emotions. However, females experienced lower life satisfaction and happiness than males.[^ons2]

[^nhs]: https://www.england.nhs.uk/mental-health/cyp/
[^nhs2]: https://digital.nhs.uk/data-and-information/publications/statistical/mental-health-of-children-and-young-people-in-england/2021-follow-up-to-the-2017-survey
[^ons]: https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/bulletins/suicidesintheunitedkingdom/2020registrations
[^ons2]: https://www.ons.gov.uk/peoplepopulationandcommunity/wellbeing/articles/coronavirusanddepressioninadultsgreatbritain/januarytomarch2021

When we consider these figures, combined with a reflection of the impact wrought by the COVID-19 pandemic on an already over-burdened mental health sector, we can begin to understand why many organisations across the public, private, and third sectors are deploying digital technologies to augment and complement their services, and why many users in turn have engaged.

But if we are to implement digital technologies in an ethical and trustworthy manner, there are several considerations that need to be addressed. 

The first two relate to choice and access, as outlined in a briefing note from the Nuffield Council on Bioethics[^Nuffield] (emphasis ours):

1. "Many people affected by mental health problems *do not have access to* or are *reluctant to use* mental healthcare technologies. If these are to become widely adopted in the future, there should be choice about using them."
2. "Technology solutions *should not divert resources from other important forms of mental healthcare* and support and *should be used as an addition* to what is already available, *rather than a replacement*."

The latter conclusion is echoed here because it is a theme that emerged frequently in our own project among diverse stakeholder groups. That is, DMHTs should augment and support, but never replace human decision-making or human-centred services. And, the former conclusion is also important because it captures something salient about trust. 

For some potential users, such as elderly patients, a lack of access can be due to their needs not being sufficiently considered when designing the service or technological interface.[^design] This form of inaccessibility is sometimes overlooked due to an emphasis on other economic barriers (e.g. digital poverty). However, even users that a) have access to the services (in both senses of the term ‘access), and b) potentially benefit from use of the respective technology, may still have legitimate reasons for not wishing to use the service due to a distrust (or, “reluctance” to use the same term from the above quotes) in the service or the organisation responsible for designing, developing, and deploying it. In some cases, this distrust arises due to legitimate concerns about violations of data privacy or mishandling of sensitive information by commercial organisations.

[^design]: See references and discussion on 'universal design' in Burr, C., Taddeo, M., & Floridi, L. (2020). The Ethics of Digital Well-Being: A Thematic Review. Science and Engineering Ethics. [https://doi.org/10.1007/s11948-020-00175-8](https://doi.org/10.1007/s11948-020-00175-8)

However, the unethical behaviour and transgressions of law by commercial organisations such as Facebook[^facebook] can have a wider impact beyond their own disastrous public relations. They can also contribute to a growing culture of distrust in the ecosystem more broadly, affecting the public and third sectors, as members of the public may be unable to separate the differing ethical, social, or legal norms that govern each sector or domain.[^conversation] This is understandable from the perspective of the user, as the norms that regulate and govern the public, private, and third sectors are complex and deeply interwoven. But it is still characteristic of an unethical and irresponsible approach to research and innovation, and one that is unlikely to build trust.

[^facebook]: For a timeline that conveys a shocking pattern of behaviour at Facebook, which is hard to treat as anything other than a flagrant disregard for user’s data privacy, see [Facebook data privacy scandal: A cheat sheet](https://www.techrepublic.com/article/facebook-data-privacy-scandal-a-cheat-sheet/).

## A Culture of Distrust

In the context of the law, it is well known that states and public sector organisations are beholden to wide-ranging legal duties, both positive and negative, such as those set out in human rights law or in national legislation (e.g. the public sector equality duty created by the UK's Equality Act 2010).

Commercial organisations are not obligated to observe all of the same principles or rules as public sector organisations, but are nevertheless required to comply with myriad information governance standards, legislation designed to protect environmental sustainability and public health, and a whole host of other corporate or fiduciary duties[^ea10].

[^ea10]: It is important to note that private organisations are still bound by the legal duties of non-discrimination, even where they fall outside the wider scope of the public sector equality duty. For further advice and guidance on these topics, see [this recent publication](https://www.equalityhumanrights.com/en/advice-and-guidance/artificial-intelligence-public-services) by the Equality and Human Rights Commission on Artificial Intelligence in Public Services.

Third sector organisations, such as charities or volunteer groups, may have less restrictive legislation governing their conduct, but are still expected to adhere to necessary transparency and accountability standards over matters such as the organisation and incorporation of managing trusts.

Such legal requirements create an interlocking foundation upon which public perceptions and attitudes towards trust can be based, but are often difficult to separate and pick apart. And, even where one is able to do so, legal requirements typically set only the *minimal standards* expected of organisations. To put it simply, and sidestep a vast amount of important jurisprudence, just because something is legal does not guarantee it is ethical or socially acceptable.

On top of the norms that fall within the scope of the law, modern institutions and organisations are also expected to observe and comply with an expansive and shifting set of ethical and social norms. For example, while underpinned by legal mechanisms, matters of social justice and fairness go beyond the legal requirements to ensure non-discrimination (e.g. poverty, a risk factor associated with worse mental health outcomes, is not a protected characteristic[^protected] as set out in the Equality Act 2010)[^reviewer]. Moreover, legal texts often leave wide scope for actions that may be sufficient to discharge duties corresponding to individual rights[^article8], but are seen by many as, at best, failing to observe the spirit of the law, and at worst, morally impermissible.

[^protected]: The [Equality Act 2010](https://www.legislation.gov.uk/ukpga/2010/15/part/2/chapter/1) sets out the following protected characteristics:

    - Age
    - Disability
    - Gender reassignment
    - Marriage and civil partnership
    - Pregnancy and maternity
    - Race
    - Religion or belief
    - Sex
    - Sexual orientation
    
    They are protected in the sense that the law is designed to protect individuals from unfair treatment or discrimination on the basis of these characteristics.

[^reviewer]: Our thanks to a reviewer for bringing the following example to our attention of a local council who unanimously voted to make 'care experience' a protected characteristic within its constituency: [https://www.cypnow.co.uk/news/article/cumberland-council-votes-to-make-care-experience-a-protected-characteristic](https://www.cypnow.co.uk/news/article/cumberland-council-votes-to-make-care-experience-a-protected-characteristic).

A particularly well known illustration of this problem is the EU's General Data Protection Regulation (GDPR) and ePrivacy Directive. The GDPR (and directive) resulted in widespread changes to the operation of cookies, including a requirement to receive users’ consent before any cookies were used, except those strictly necessary. However, as almost everyone will know from first-hand experience, the manner in which some organisations secure consent can range from the entirely user-friendly, to the intentionally frustrating use of dark patterns[^dark] or hours long process of flipping hundreds of opt-out toggle buttons. Here, the expectations that society have regarding what is both legally and morally permissible clearly differ substantially from what is desirable from the perspective of the organisation and the law.

[^article8]: For instance, Article 8 of the EU Charter of Fundamental Rights (On the Protection of personal data) states, "1. Everyone has the right to the protection of personal data concerning him or her. 2. Such data must be processed fairly for specified purposes and on the basis of the consent of the person concerned or some other legitimate basis laid down by law. Everyone has the right of access to data which has been collected concerning him or her, and the right to have it rectified. 3. Compliance with these rules shall be subject to control by an independent authority." Provisions 1 and 2 help to delineate the remit of an individual's right, whereas provision 3 establishes a corresponding duty on member states that helps ensure the aforementioned rights are guaranteed and protected.

[^dark]: Dark patterns are design elements of an user interface that have been intentionally chosen to manipulate or deceive users into taking actions or making sub-conscious choices, which they would be unlikely to do when conscious of the outcome (e.g. purchasing a more expensive product, agreeing to invasive privacy policies).

But these expectations also differ depending on whether the organisation is part of the public, private, or third sector, and what role they play within each sector. And, furthermore, expectations are not equally shared across a vast and homogenous “public”. Quite the opposite in fact.

Consider, for example, the range of attitudes that members of the public may have towards a private company extracting economic value from their data collection activities. Depending on key details about the informational content of the data, attitudes could range from shareholder praise for savvy corporate governance, through to begrudging toleration by consumers, and up to the vehement and vocal criticism by privacy activists or employee campaign groups.

And to add one final layer of complexity, to really drive home Whitman's point from the start of this chapter, the scope and distribution of this variation may increase as we expand our field of consideration to the public and third sectors. Now, the same data extraction could be seen as deeply unethical or impermissible by those who were in favour of it originally. In terms of underlying values, therefore, *pluralism* and *variation* should be expected when considering the attitudes of the *publics* (reiterating the emphasis on the plural).

By now, you may be feeling as though stoic acceptance in the face of overwhelming complexity is inevitable. What other options are there? You may be thinking, for instance, that there are simply too many factors for any one person or organisation to consider when researching, developing, or regulating DMHTs.

However, this report (and our project more generally) aims to challenge this attitude, while fully acknowledging the overwhelming complexity involved. Our approach and methodology in many respects embodies the principle that *light is the best disinfectant*. And, framed as a set of recommendations, which include but build on the two conclusions from the Nuffield Council on Bioethics above:

=== "Additional Recommendations"

    1. Organisations that choose to use DMHTs should consider broader ethical goals, in addition to traditional goals such as ‘safety’ and ‘efficacy’, to help create a more ethical, responsible, and trustworthy ecosystem of digital mental healthcare.[^consistency]
    2. Organisations should provide transparent and evidence-based assurance about how these ethical goals have been operationalised and secured during the design, development, and deployment of DMHTs.

=== "Original Conclusions from Nuffield Council on Bioethics"

    1. Many people affected by mental health problems do not have access to or are reluctant to use mental healthcare technologies. If these are to become widely adopted in the future, there should be choice about using them.
    2. Technology solutions should not divert resources from other important forms of mental healthcare and support and should be used as an addition to what is already available, rather than a replacement.

[^consistency]: To emphasise the consistency of this recommendation with the conclusions from the Nuffield Council report we should also acknowledge that this ‘digital ecosystem’ must be complementary with, supportive of, and enhance more traditional healthcare services (qua conclusion 2).

With these points in mind, we can now turn to the project itself and introduce the notion of trustworthy assurance—a methodology that can help address all of the above recommendations (and more to come).

## About the Project

Assurance is a process of establishing trust.

Whether we trust someone or some object depends, in part, on the evidence we have to help us evaluate whether there are good grounds for placing trust. In other words, what is the evidence of their trustworthiness?

When it comes to trust, we do not expect the same level of evidence when assessing the trustworthiness of different people, objects, or systems. A trustworthy doctor, for example, is not assessed by the same standards as a trustworthy friend. And, similarly, the trustworthiness of an AI chatbot used in customer services is not (and ought not) be evaluated by the same measures as an AI chatbot used to support people with their mental health.

In short, when we speak of 'trustworthy assurance' we are creating room for a wide variety of associated goals and standards, to accommodate the complexity alluded to in the previous sections. These can, of course include goals and standards related to ‘safety’ or ‘clinical efficacy’, which carry their own ethical significance. However, for present purposes we are primarily interested in those goals that are directly framed in terms of ethical principles (e.g. fairness).

Our project focused directly on a methodology for making the assessment, communication, and realisation of these goals more robust and transparent. The methodology is known as ‘argument-based assurance’ (ABA) and we can define this methodology as follows:

> Argument-based assurance is a process of using structured argumentation to provide assurance to another party (or parties) that a particular claim (or set of related claims) about a property of a system is warranted given the available evidence.[@burr2022]

We offer a simplified introduction to ABA in the following chapter. But various types of ABA are already widely used in safety critical domains, and have also been used in the context of healthcare[^ABA]. Typically, the purpose of ABA is to assess and communicate the *safety* of a system within a particular environment. Our project was concerned with the question of whether a revised and extended version of the methodology could be used for a broader set of ethical goals, such as fairness or explainability (see [Chapter 5](chapter-5.md)).

[^ABA]: See an older, but still important report from [Health Foundation](https://www.health.org.uk/sites/default/files/UsingSafetyCasesInIndustryAndHealthcare.pdf) as well as a more recent proposal: Habli et al. (2020). Enhancing COVID-19 decision making by creating an assurance case for epidemiological models. BMJ Health &amp; Care Informatics, 27(3), e100165. https://doi.org/10.1136/bmjhci-2020-100165

There is an immediate question that ought to be addressed here:

!!! question "Question"

    How should ethical goals be determined and operationalised in the context of the design, development, and deployment of DMHTs?

Our approach in this project to determining and operationalising the relevant ethical goals was *participatory* in nature, and was driven by three primary objectives:

1. To explore whether and how the methodology of ABA could be extended to address ethical issues in the context of digital mental healthcare.
2. To evaluate how an extension of the methodology could support stakeholder co-design and engagement, in order to build a more trustworthy and responsible ecosystem of digital mental healthcare.
3. To lay the theoretical and practical foundations for scaling the trustworthy assurance methodology to new domains, while integrating wider regulatory guidance (e.g. technical standards).

To realise these objectives, several workshops were organised and run over the course of the project with a diverse set of participants. Broadly, we categorised these stakeholder groups as follows:

- University students
- University administrators
- Policy-makers and regulators in healthcare
- Developers of DMHTs
- Researchers working in disciplines adjacent to digital mental healthcare
- Users with lived experience of DMHTs

Workshops and interviews were held with representatives from each of these stakeholder groups, where tailored activities were run to both understand their attitudes towards DMHTs, but also to a) help us evaluate methodological questions related to trustworthy assurance and b) identify which ethical values and principles matter most to them in the present context.

Chapters 2 and 3 present our findings, analysis, and recommendations from the engagements. Here, we shall just speak to the procedural matter of operationalising ethical principles through processes of stakeholder participation and engagement.

### SAFE-D Principles

In previous work, we have defended an ethical framework for evaluating the harms and benefits of data-driven technologies, which has already been revised, tested, and validated with a wide-variety of stakeholders[^coe].

We refer to this framework as the *SAFE-D framework*, because it establishes five principles that form the acronym SAFE-D (or, ‘safety’, which is another important component of trustworthy AI):

- Sustainability
- Accountability
- Fairness
- Explainability
- Data (Quality, Integrity, Protection and Privacy)

[^coe]: The most recent and comprehensive account of this framework can be found in the following proposal to the Council of Europe: Leslie, D., Burr, C., Aitken, M., Katell, M., Briggs, M., & Rincon, C. (2022). Human rights, democracy, and the rule of law assurance framework for AI systems: A proposal. [https://rm.coe.int/huderaf-coe-final-1-2752-6741-5300-v-1/1680a3f688](https://rm.coe.int/huderaf-coe-final-1-2752-6741-5300-v-1/1680a3f688).

Each of the SAFE-D principles has a subset of core attributes that help to specify and operationalise the principles throughout a project's lifecycle using a series of processes and activities (see [next chapter](chapter-1.md) for full details).

In other words, while the principles themselves act as starting points for context-specific reflection and deliberation with affected stakeholders, it is the core attributes that serve as practical guardrails throughout a project’s lifecycle. For instance, the principle of 'explainability', which emphasises core attributes such as transparency, interpretability, and accessibility of an automated system, has a particular ethical significance when utilised in a domain such as digital mental healthcare. That is, ensuring digital mental healthcare technologies and services are *explainable* is a key part of respecting a patient's right to informed and autonomous decision-making. This right cannot be upheld and respected without ensuring sufficiently *transparent*, *interpretable*, and *accessible* forms of information about how a digital technology operates (e.g. how an algorithmic system reaches a decision). How organisations achieve this goal is something this project and report addresses directly.

While the SAFE-D principles have been designed and refined over multiple years (in a domain-general context) their relevance in digital mental healthcare had, hitherto, not been evaluated. Therefore, part of this project involved the following:

1. Understanding which, if any, of the SAFE-D principles were significant to different groups of stakeholders, and whether specific core attributes could be identified and developed in conjunction with stakeholders.
2. Identifying if there were any gaps or omissions in the SAFE-D framework.
3. Determining whether any of the revised and domain-specific principles or attributes could serve as top-level goals or property claims in trustworthy assurance cases (see [Chapter 2](chapter-2.md)).

Our findings and analysis that address these specific research questions comprise the majority of [Chapters 3](chapter-3.md) and [4](#chapter-4.md). Among other findings and recommendations, these sections show there is strong evidence to suggest that the methodology of trustworthy assurance will lead to positive impacts in digital mental healthcare, and help foster a more responsible ecosystem of research and innovation.

Before we discuss these findings and analysis though, it is necessary to introduce and explain the methodology of trustworthy assurance, which is the topic of the next chapter.
