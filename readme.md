# eXeXeF Project Proposal


## Background

Current approaches to mental illnesses seek medical or behavioral interventions that suppress, remove, or render irrelevant the symptoms. Such methods are imprecise, frustratingly slow to verify efficacy, often high cost, disturbingly commonly abusive, and rife with drug-drug interactions or side effects that place immense burden on the user. In addition, the narratives surounding mental health often adopt a 'curative' mindset that seeks to purge the condition from the individual or prevent their existence in the first place. The rising voices from self-advocacy groups of the actually neurodiverse often challenge these framings and approaches. Rather than a-priori seeking to disentangle an autistics from their autism, ND perspectives center the consent and wishes of the individual in directing their own development. Several traits of various mental health conditions are viewed by some indivuals that have them not as debilitating symptoms, but sources of unique capabilities, insights, and rich experience.

This requires a more nuanced, tunable, and immediate method for controlling dimensions of one's mental dynamics. While modifying the brain is currently impractical, software engineers can create complete cyber-psychological systems that collectively exhibit the behavior a user might strive for. Suitably composable systems can then be tailored not only to the individual's specific symptom expression, but also in alignment with their goals. For example, while individuals with adhd may struggle to focus on a single task in front of them, the routine immense mental leaps can provide constant streams of novel and fascinating ideas worth investigation. Rather than seeking the removal of the condition, by acknowledging that the vast majority of interactions the user takes these days are via computer, software locking out common distraction methods can mitigate undesired dimensions while permitting the idea stream to continue.

## Objective 

Executive Functioning is a common domain of cognition impacted in oft-undesireable ways by a variety of mental health conditions. By creating easily-configurable, non-technical-user friendly, private personal assistant systems, we can potentially empower many neurodiverse individuals in pursuit of self-determination.

## Example Possible Capabilities
- Forcing getting out of bed each day
- Tracking self-state (eaten? showered? laundry? mindfullness check?)
- Breaking down tasks taking longer than expected
- Avoiding Avoidant behavior by curtailing distractions
- Regular practice of therapy skills
- avoiding losing physical stuff via tracking
- recording new ideas to prevent their disappearance
- focusing on a singular project at a time
- daily logging of positive experiences to challenge negative self-talk
- tracking and management of day-to-day basics like paying bills
- reminding/suggesting means of staying in touch with friends regardless of emotional state
- track medication consumption, track performance of medication
- distilling multiple concurrent projects into single concrete goals that can be attempted immediately.
- recognizing current conversation partner and presenting context of communication

## High Level Requirements

### Minimum Requirements

- *Configurable:* The system can be tailored to the user's desired capacities.
- *Documented Deployment* The system does not require technical expertise of any kind to set up.
- *Private:* Leaking intra-system communiques is unacceptable due to the content's sensitivity.
- *Usable:* The user is reasonably able to interact with the system.
- *Worthwhile:* The system must be reasonably likely to provide more benefit than is required for its setup & maintenance.

### Basic Requirements
- *Free to use:* By making use of developer-oriented free hosting resources online, it should be possible to completely avoid costs per user.
- *Automated Deployment:* Given a configuration on the order of desired augmentations or capacities, deploy the system implementing such a goal.
- *Unobtrusive:* Being constantly pinged or managed would likely rapidly become annoying.
- *Approachable Configuration:* The interface for configuration is sufficiently clean and usable that it could reasonably be the discussed and manipulated during a therapy appointment.
- *Condition-tagged capabilities:* Rather than just a big swath of capabilities, associating them with different conditions can help with discovery.

### Ideal Capabilities

- *Therapist Collaboration:* Providing a therapist access to the information as designated by the user can help highlight critically needed conversations & practices of skills.
- *Easily Extensible:* Enable users to create new capabilities without requiring deep programming knowledge; well-supported interfaces akin to IFTTT can help facilitate this.
- *Augmentation Exchange:* Users can label and share capabilities without any technical skill, empowering single creators to address needs of multiple users
- *Voice/Chatbot Interface:* Talking through a blocking task by answering questions can be more approachable than typing, and would increase accessibility. It also could allow for very useful capabilities, such as avoiding avoiding starting the workload by conversing with user about the relative priority of imminent tasks.

- *Lowest Activation Energy:* Even in their most static depression, a new user only needs to accept the install and grunt emphatically for it to find and schedule a therapist appointment, psychiatrist appointment, and apply a default configuration for their professed condition.
- *Augmentation Suggestion:* When a user demonstrates often-undesireable behaviors reasonably expected based off their preferred configuration, suggesting the corresponding component may help steer the user toward their most preferred setup. 
- *Arbitrary Self-construction:* Instead of requiring users to manipulate software to assemble the logic of an augmentation, concisely-stated natural language description of conditions and resultant responce is all that is required to synthesize a new augmentation out of existing modules. Arguably requires development of strong AI?


## Ethics/Social Justice Concerns

+ Depending on the approach taken, subtle differences in framing, language, and UI can easily cascade into sending toxic unintended messages due to the highly nuanced language surrounding ableism. 
+ There is no easy simplification to grouping along any axis of mental health. The desire to assign buckets- you have ADHD, you have Bipolar, you have an anxiety condition- has led to a disturbingly-common reductionist approach; Bipolar people do X, AdHd people do Z. These distinctions are commonly laughably indistinct when examined on an individual level-which is the level we're specifically interested in. Even the neurotypical vs neurodiverse distinction breaks down instantly simply when asking "what constitutes abuse?" or "what is a healthy amount of emotional attachment?"
+ There is a long, long and ongoing history of medical practitioners having sole say over the experiences of the mentally ill. Situations like being spontaneously forced to stay in a hospital isolated from support, well-informed objections to specific drugs due to known symptoms being completely disregarded, and parents' wishes being heavily prioritized over the actual ND individual are alarmingly common in all countries in the current, modern world. **Much care must be taken around the power imbalances between medical professionals, parents, partners, and users themselves.**
+ In the USA, while the disabled who are unable to work are supposedly recieving stipends covering their cost of living, in reality the systems at play are horrendously broken. Requests for coverage often take multiple years to resolve. Funding provided is already brutally low, and commonly briefly disappears without notice or reason. The process for qualifying for disability assistance entails arduous questionings featuring questions like "why haven't you killed yourself yet?". Particularly disabled populations currently commonly live in a perpetual state of dodging death to the best of their ability due to the cost of existing.

## Provided Materials & Recommended Research Topics

+ I recommend looking at FOSS systems similar to IFTTT, such as Huginn. These systems can go a long way toward enabling non-technical creation of new capabilities out of composed structures of specific agents.

+ Approaches such as temporarily changing the local DNS configuration for certain sites, locking out programs or apps, or changing projects/pinned tabs/etc can be very fruitful for addressing many different subproblems. Look for SelfControl on MacOSx, (Offtime) on Android, and the like for inspiration in that regard.

+ I recommend looking up the Autism Self Advocacy Network for better context on curative-acceptance discussion.

+ The perspectives of relevantly-specialized therapists will be particularly useful in finding what are the biggest pain-points for different types of users. Not all theoretical groundings for therapy practice are well suited for thinking about a human brain as a multitude of behaviors & cognitions that can be managed; Accordingly, Cognitive Behavioral Therapists or Dialectical Behavioral Therapists are likely to be the most adaptable to such a "composed cyberpsychological management" approach.

## Questions for Reflection

+ With all the popularity of transhumanism and all the hullaballoo over the Quantified Self Movement, very technologically low-hanging fruit with significant benefit have hardly been attempted or suggested at all, despite the potential to meet the needs of huge swaths of the population. Why?
+ What projects recently have come *close* to addressing ND needs in this way? What 'technical' decisions led to a deprioritization of ND needs?
+ How does the consent-centric, self-determination-centric transhumanism proposed here differ from currently dominant transhumanist narratives? What problems are viewed as most important in each of the two approaches? Who benefits from such interpretations of transhumanist beliefs?

