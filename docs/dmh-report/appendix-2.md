---

authors:
  - Christopher Burr
  - Rosamund Powell
tags:
  - examples
  - digital-mental-health-technologies
 
---

# Appendix 2: Examples of Digital Mental Health Technologies

![An illustration showing different uses of AI](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/artificial-intelligence.png)

!!! info "Work in Progress"

    This page is a work-in-progress. Additional examples will be added as they are produced, but the goal is not to develop a comprehensive list nor carry out a systematic review of the examples according to a specific methodology. Rather, it is to provide an illustrative set of examples for those who are new to this field.
    
## Smartphone Apps

There are countless smartphone apps available to consumers. Some are free to download, others require a one-off purchase, and others require ongoing subscriptions. In some instances, employers or other organisations (e.g. Universities) may provide access to individuals through group subscriptions or via formal healthcare services. As a category, `smartphone app` does not provide any indication of the type of functionality of the underlying services. Apps can range from simple meditation apps that could be beneficial for a wide-range of users (e.g. dealing with stress, anxiety, or productivity) to AI chatbots that target users with specific mental health issues. 

A prominent concern in this area is the lack of enforceable regulation that prevents developers from exploiting social media advertising networks to target users with mental health issues (e.g. depression, anxiety) while skirting around medical device regulation by referring to their service as a "well-being tool".

Furthermore, as a recent study by [Mozilla](https://foundation.mozilla.org/en/privacynotincluded/) highlights, the quality of data privacy and protection practices varies widely, with some developers being very transparent about their data collection, analysis, and storage, while others skirt the boundaries of what is legal.

!!! tip "Privacy Not Included"

    The 'Privacy Not Included' study, carried out by Mozilla, is a consumer-facing guide on the apps, services, and internet-connected devices that do and do not respect user rights to data privacy and protection. They have a whole section on mental health apps, which we highly recommend exploring. 
    
    Their methodology is also available here: [https://foundation.mozilla.org/en/privacynotincluded/about/methodology/](https://foundation.mozilla.org/en/privacynotincluded/about/methodology/)

A recent standard produced by the International Standards Organisation (ISO) demonstrates one means for bringing more structure to health and wellness apps through the standardisation of reporting labels (see Figure 1)[^iso]. Labels such as these could represent a significant type of evidence to ground assurance cases, subject to the formation of consensus around such best practices.

[^iso]: Reprinted from PD CEN ISO/TS 82304-2:2021, Health Software— Health and wellness apps. Quality and reliability. Permission to reproduce extracts from British Standards is granted by BSI Standards Limited (BSI). No other use of this material is permitted.  British Standards can be obtained from BSI Knowledge knowledge.bsigroup.com

![An example of a lable to accompany health and wellness apps](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/applabel.png)
*Figure 1. A label showing dimensions of quality and reliabiluty for health and wellness apps. (PD CEN ISO/TS 82304-2:2021)*

<div class="grid cards" markdown>

-   :material-robot:{ .lg .middle } __Wysa Chatbot__

    ---

    According to the [develeoper's website](https://www.wysa.io/faq[), "Wysa AI Coach is an artificial intelligence-based 'emotionally intelligent' service which responds to the emotions you express and uses evidence-based cognitive-behavioral techniques (CBT), DBT, meditation, breathing, yoga, motivational interviewing and micro-actions to help you build mental resilience skills and feel better."

    ✅ ML/AI: this app is explicit in its use of AI for enabling automated conversations with users.

    ![A screenshot of the Wysa AI coach app. From the Wysa Press Kit.](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/wysa.jpg)
    *A screenshot of the Wysa AI coach app. Reprinted from the [Wysa Press Kit](https://www.wysa.io/media).*
    
    [:octicons-arrow-right-24: Visit Developer's Site](https://www.wysa.io)

-   :material-meditation:{ .lg .middle } __Headspace__

    ---

    Headspace’s core products are mobile and web-based apps that focus on mindfulness, meditation, sleep, exercise, and focus content (e.g. guided exercises). The company [publishes research](https://www.headspace.com/science) to support its claims about efficacy and outcomes.

    ✅ ML/AI: the use of ML or AI is not a prominent feature in the app, but the organisation does make use of ML to tailor recommendations to users, and has [published plans](https://headspace.medium.com/infrastructure-design-for-real-time-machine-learning-inference-e140793d6741) to make use of additional data.

    ![A screenshot of the Headspace app. From the Headspace Press Kit.](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/headspace.jpg)
    *A screenshot of the Headspace app. Reprinted from the [Headspace Press Kit](https://www.headspace.com/press-and-media).*
    
    [:octicons-arrow-right-24: Visit Developer's Site](https://www.headspace.com)
    
</div> 


## Virtual or Augmented Reality (VR/AR)

The use of VR/AR technologies to support mental health are primarily used in research projects at present, while the efficiacy of such tools is investigated. A wide variety of research projects are exploring how these DMHTs could be used to support mental health outcomes related to psychosis, social anxiety, and chronic pain, among others.

<div class="grid cards" markdown>

-   :material-virtual-reality:{ .lg .middle } __Virtual Body and Anxiety Reduction__

    ---

    A research team at the Department of Psychiatry (University of Oxford) have explored how the observation of a virtual body double engaged in social interaction may reduced persecutory thoughts associated with anxiety. The study demonstrates limited but positive evidence for a decreased anxiety.

    ✅ ML/AI: automated techniques are used to control the behaviours of the artificial agents that the virtual body double interacts with, although pre-recorded dialogue is also used.

    ![An image of the body doubles in VR space. Reprinted from Gorisse et al. (2021)](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/vr-freeman.jpg)
    *An image of the body doubles in VR space. Reprinted from [Gorisse et al. (2021)](https://www.nature.com/articles/s41598-021-03373-x)* 

    [:octicons-arrow-right-24: Read Publication](https://www.nature.com/articles/s41598-021-03373-x)

-   :material-account-injury:{ .lg .middle } __VR and Chronic Pain__

    ---

    Although broader than mental health, chronic pain has stong bi-directional associations with mental health issues, such as depression. Many studies have explored whether VR can help reduce the experience of chronic pain. For instance, allowing users to explore movements in a virtual space that would typically cause an experience of pain were they carried out for real. A recent scoping review of 44 studies concludes that VR can have *short-term* analgesic effects in acute pain settings, but that *long-term* efficacy for chronic pain conditions has not been established. 
    
    ❌ ML/AI: not applicable

    [:octicons-arrow-right-24: Read Publication](https://academic.oup.com/painmedicine/article-abstract/23/1/105/6321464?login=false)
    
</div> 

## Decision Support Tools

By 'decision support tools' we mean DMHTs that are designed to be used to augment or support the decision-making of healthcare professionals.

<div class="grid cards" markdown>

-   :material-message-text:{ .lg .middle } __IESO Digital Health__

    ---

    IESO Digital Health is one of the leading providers of online mental health services for the NHS, as part of the Improving Access to Psychological Therapies (IAPT) programme. The company have developed an AI-powered decision support tool, which "automatically annotates therapist utterances in real-time" to support CBT. The tool can be used for several purposes, including "to monitor the delivery of crucial elements in live therapy" and to remind the therapist "to set an agenda or to set homework when they have not done so."

    ✅ ML/AI: the tool uses a deep learning method known as bidirectional long short-term memory.

    ![An image of an example therapy session with automated labels applied in real time. Reprinted from Cummins et al. (2019)](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/ieso.png)
    *An image of an example therapy session with automated labels applied in real time. Reprinted from [Cummins et al. (2019)](https://doi.org/10.1145/3308558.3314128)*

    [:octicons-arrow-right-24: Visit Developer's Site](https://www.iesohealth.com/)
    
</div> 

## Neurotechnologies

Neurotechnologies are are another class of technologies that are broader than mental health specifically, and also include wearables such as headbands as well as  Brain-Computer Interfaces (BCIs). They have received widespread attention from the bioethics community.[^nuffield]

[^nuffield]: For example, see these resources and articles from Nuffield Council on Bioethics: [https://www.nuffieldbioethics.org/topics/data-and-technology/neurotechnology](https://www.nuffieldbioethics.org/topics/data-and-technology/neurotechnology)

<div class="grid cards" markdown>

-   :material-brain:{ .lg .middle } __EEG Headbands__

    ---

    The FocusCalm is an EEG headband by BrainCo—a company that grew out of the Harvard Innovation Lab. The device is currently marketed as a DMHT to measure brain activity and offer real-time feedback to focus and relax your mind. However, an earlier version of the product was tested as a tool for improving the attention of Chinese school students during lessons, before [it was halted](https://www.theguardian.com/world/2019/nov/01/chinese-primary-school-halts-trial-of-device-that-monitors-pupils-brainwaves) following complaints from parents.

    ✅ ML/AI: the company claims to use ML algorithms to help interpret EEG frequency bands.

    ![An image of a Chinese pupil wearing an EEG headband.](https://raw.githubusercontent.com/alan-turing-institute/trustworthy-assurance/main/docs/assets/images/eeg.jpg)
    *An image of a Chinese pupil wearing an EEG headband.*

    [:octicons-arrow-right-24: Visit Developer's Site](https://focuscalm.com/)
    
</div> 