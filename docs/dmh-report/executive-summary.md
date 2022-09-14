---
authors:
  - Christopher Burr
  - Rosamund Powell
tags:
  - executive summary
  - findings
  - recommendations
  - digital-mental-healthcare
---

# Executive Summary

There is a culture of distrust surrounding the development and use of digital mental health technologies.

As many organisations continue to grapple with the long-term impacts on mental health and well-being from the COVID-19 pandemic, a growing number are turning to digital technologies to increase their capacity and try to meet the growing need for mental health services.

Clearer assurance on how ethical objectives should be considered and implemented (e.g. fair use of data; explainable processes and outcomes) is necessary to help build a more trustworthy and responsible ecosystem. Trustworthy Assurance is a framework and methodology for enabling such an ecosystem, and this report presents findings and recommendations of a project undertaken between July 2021 and June 2022.

As part of this research project, we conducted a series of participatory stakeholder engagement events with students, University administrators, regulators and policy-makers, developers, researchers, and users of digital mental health technologies. Our objectives were a) to identify and explore how stakeholders understood and interpreted relevant ethical objectives for digital mental health technologies, b) to evaluate and co-design the trustworthy assurance framework and methodology, and c) solicit feedback on the possible reasons for distrust in digital mental health.

!!! example "Key Findings"

    1. The current landscape of digital mental health is characterised by significant uncertainty, a lack of transparency or accountability, and a rising demand that outpaces trusted services and resources. This contributes to a culture of distrust, which may prevent vulnerable users from accessing support.
    2. Trustworthy Assurance is a framework and methodology that can support the design, development, and deployment of data-driven technologies and also create a more responsible and trustworthy ecosystem of digital mental healthcare.

!!! check "Recommendations"

    1. Recommendation 2

In each subsequent chapter, these key findings of our project are further contextualised and refined with reference to the specific topics under discussion.

## Report Overview

Our report is structured as follows:

* [Chapter 1 (Introduction)](chapter-1.md) establishes the background context and conceptual foundations for the report, while also outlining the many challenges that exist for researchers, developers, and policy-makers/regulators working in the domain of digital mental healthcare.
* [Chapter 2 (Presenting Trustworthy Assurance)](chapter-2.md) introduces the framework and methodology of 'Trustworthy Assurance'. The framework includes a model of a typical project lifecycle involving a data-driven technology (e.g. health and well-being app), and a discussion of several ethical principles, known as the SAFE-D principles. The framework serves as a guide to our methodology for developing an assurance case that promotes trustworthy goals associated with digital mental health technologies. Finally, this chapter also includes an important discussion about 'argument patterns', which support the material presented in [Chapter 5](chapter-5.md).
* [Chapter 3 (Applying Trustworthy Assurance)](chapter-3.md) presents findings from a research sub-project conducted with students and administrators from UK Universities. These engagement events explored the application of trustworthy assurance to the procurement of digital mental health technologies for use in the higher education (HE) sector, as well as general attitudes and perceptions towards the use of data-driven technologies in higher education. A series of recommendations accompany our thematic analysis.
* [Chapter 4 (Co-Designing Trustworthy Assurance)](chapter-4.md) broadens the scope from the previous chapter to present research findings from a series of stakeholder engagement events carried out with regulators and policy-makers, developers, researchers, and users with lived experience of digital mental health technologies. As with the previous chapter, a set of recommendations accompanies our thematic analysis.
* [Chapter 5 (Developing Trustworthy Assurance)](chapter-5.md) introduces, motivates, and explains two argument patterns that are intended to help project teams meet objectives for fair and explainable digital mental health technologies. This chapter also connects the argument patterns to existing and relevant legislation and regulation (e.g. Equality Act 2010).

### About the Report

The following summarises what this report is and what it is not:

✅ An introduction to 'Trustworthy Assurance'—a framework and methodology for enabling a more trustworthy ecosystem of digital mental healthcare through the responsible and ethical design, development, and deployment of digital technologies.

❌ A comprehensive user guide for 'Trustworthy Assurance' or argument-based assurance—though links and further resources are provided.[^online]

✅ A summary of findings from research conducted on the application of trustworthy assurance to the procurement of digital mental health technologies for use in the higher education (HE) sector.

❌ Findings from a sociological study or series of generalisable results from scientific experiments.

✅ A summary of findings from a series of more general stakeholder engagements, exploring the ethics of digital mental healthcare and attitudes towards trustworthy and untrustworthy technologies.

❌ A report with a strong international or multi-national focus. While we make reference to non-UK developments in this domain, our primary focus is on the UK. However, the methodology we present and many of the findings we discuss have value beyond the UK.

✅ An explanation and discussion of two argument patterns exploring the goals of fairness and explainability in the design, development, and deployment of digital mental health technologies.

❌ A critical examination of argument-based assurance.[^critical]

✅ A series of recommendations, targeted at different stakeholders, for how to enable a more responsible and trustworthy ecosystem of digital mental healthcare.

❌ A review of the current legislative or regulatory publications that are relevant to digital mental healthcare.

[^online]: Work is underway to develop an user guide, and this will be added to the online version of our report when ready. The guide will also include instructions on how to use our tool for producing assurance cases.

[^critical]: The following documents provide a more critical examination for those interested: [(Sujan and Habli, 2021)](https://qualitysafety.bmj.com/content/30/12/1047.abstract); [(Burr and Leslie, 2022)](https://link.springer.com/article/10.1007/s43681-022-00178-0).

### Who is this report for?

This report is primarily targeted at the following groups:

---

<div markdown>

  ![Icon of a regulator controlling sliders on a screen](../assets/icons/regulator-icon.png){ align=left width=15% }
  
  **Policy-makers and Regulators**

  Policy-makers and regulators will find the recommendations and guidance we set out of specific interest, and will find value in the methodology that we set out in [Chapter 2](chapter-2.md) because it is framed in procedural terms, and with links to process-based forms of governance. We also link our two argument patterns, which are presented in [Chapter 5](chapter-5.md), to specific legislative and regulatory developments in healthcare.

---

  ![Icon of a regulator controlling sliders on a screen](../assets/icons/decision-maker-icon.png){ align=right width=15% }
  
  **Senior Decision-Makers**

  Senior Decision-Makers, like policy-makers and regulators, will likely benefit from our methodology of Trustworthy Assurance. Specifically, from exploring its procedural underpinnings that are discussed in the section on a typical ML or AI lifecycle (see [Chapter 2](chapter-2.md)).

---

  ![Icon of a regulator controlling sliders on a screen](../assets/icons/developer-icon.png){ align=left width=15% }
  
  **Developers and Product Managers**

  While our framework and methodology is set out in accessible forms, rather than adopting formal syntax and schemas for argument-based assurance, Trustworthy Assurance is primarily aimed at developers and product managers. That is, one of its key values is as a reflective and deliberative aid to demonstrating how ethical principles and decisions have been undertaken and establish through a project's lifecycle, with easy means for justifying the relevant claims by linking them to evidence. Therefore, developers and product managers are a key stakeholder group that we have targeted in this report and research project.

---

  ![Icon of a regulator controlling sliders on a screen](../assets/icons/researcher-icon.png){ align=right width=15% }
  
  **Researchers**

  While researchers may find less practical value in our framework and methodology, our report highlights and emphasises significant knowledge gaps and research opportunities for improving our collective understanding about the individual and social impacts of digital mental health technologies. Therefore, our report can also be seen as a call for further research into specific areas, including the evaluation and validation of the Trusworthy Assurance framework and methodology.

</div>

---

Users of digital mental health technologies may also find value in the report, but it has not been produced with members of the public as primary target audience. In general, the responsibility for utilising the methodology and implementing and acting upon the recommendations is for the groups above; they are not the responsibility of the user!
