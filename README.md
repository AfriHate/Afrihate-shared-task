# AfriHate Shared Task Co-located with AfricaNLP 2025: Hate and Offensive Language Detection in African Languages

---

Join Discord | Contact Us | Download Dataset | How to Participate

---

# Content

- Overview
- Importance and Impact
- Participants
- Languages
- Tracks
    - Track 1: Category Classification
    - Track 2: Target Classification
- Pilot Task
- Baselines and Evaluation
- Task Organizers
- Ethical Statement

---

# Overview

Online hate speech is a growing problem worldwide, causing harm to users, polluting online communities, and potentially leading to offline violence. Social media platforms facilitate the rapid propagation of hateful content. However, in regions like Africa, interventions primarily focus on high-profile individuals, often through labour-intensive human moderation which is not scalable. Furthermore, there is limited availability of machine learning tools for African languages due to the scarcity of labeled datasets.

AfriHate introduces the first high-quality labeled social media dataset collection for detecting hate and abusive language in 17 African languages. The datasets will be used in the AfriHate Shared Task, co-located with AfricaNLP 2025, a shared task on hate speech and abusive language detection in African languages with two tracks.

# Rationale of the Shared Task

Africa is home to over 2000 languages, including 75 languages with at least one million speakers each. Despite this linguistic richness, African languages are under-served in NLP. Our datasets aim to create a more inclusive digital landscape by supporting African languages and addressing language-specific challenges and nuances in hate speech detection.

# Participants

- Researchers in low-resource African languages and socio-linguistic phenomena.
- Researchers studying machine learning approaches for hate speech detection.

# Languages

| Language                              | Country         |
|---------------------------------------|-----------------|
| Hausa, Igbo, Yoruba, Nigerian Pidgin  | Nigeria         |
| Amharic, Tigrinya, Oromo, Somali      | Ethiopia        |
| Swahili                               | Kenya           |
| Moroccan Arabic                       | Morocco         |
| Sudanese Arabic                       | Sudan           |
| Twi                                   | Ghana           |
| Mozambican Portuguese                 | Mozambique      |
| Kinyarwanda                           | Rwanda          |
| IsiZulu, Afrikaans, IsiXhosa          | South Africa    |

# Tracks

## Track 1: Category Classification

Given a social media post, classify it into one of three categories: Hate, Offensive, or Normal. This track focuses on understanding the type of language used in the posts and categorizing them accordingly.

## Track 2: Target Classification

Determine the target attribute of the offensiveness in a given social media post. The possible targets include: Ethnicity, Religion, Sexual Orientation, Disability, or Gender. This track aims to identify which group is the target of the offensive content.

# Baselines and Evaluation

Baseline models will be shared, and performance evaluated using accuracy, precision, recall, and macro-F1 metrics. 

# Important Dates and Task Phases

| Description                   | Deadline                                        |
|-------------------------------|------------------------------------------------|
| Sample Data Ready             | 15 April 2025                                  |
| Training Data Ready           | 1 May 2025                                     |
| Evaluation Start              | 15 May 2025                                    |
| Evaluation End                | 31 May 2025                                    |
| System Description Paper Due  | 15 June 2025                                   |
| Notification to authors       | 30 June 2025                                   |
| Camera ready due              | 15 July 2025                                   |
| Workshop                      | 31 July 2025                                   |

The task will be divided into three phases: Development, Evaluation, and Post-Evaluation.

# How to Participate

1. Register: Sign up on the CodaBench competition platform.
2. Track: Decide on the track(s) you want to participate in (Track 1 and/or Track 2).
3. Download: Access the datasets for each track provided in this repository.
4. Develop: Build your models using the provided data.
5. Submit: Submit your predictions on the CodaBench competition platform.

# Competition Rules and Terms
<details>
  <summary>1. Consent to Public Release of Scores</summary>
  <ul>
    <li>By submitting results, you consent to the public release of your scores on:
      <ul>
        <li>the competition website,</li>
        <li>at the AfricaNLP workshop,</li>
        <li>in associated proceedings.</li>
      </ul>
    </li>
</details>

<details>
  <summary>2. Score Release and Validity</summary>
  <ul>
    <li>Task organizers reserve the right to withhold scores for:
      <ul>
        <li>incomplete submissions,</li>
        <li>erroneous submissions,</li>
        <li>deceptive submissions,</li>
        <li>rule-violating submissions.</li>
      </ul>
    </li>
    <li>Inclusion of a submission's scores does not constitute endorsement.</li>
  </ul>
</details>

<details>
  <summary>3. Team Participation Rules</summary>
  <ul>
    <li>Participants may be involved in only one team.</li>
    <li>Exceptions may be granted with prior approval from organizers.</li>
  </ul>
</details>

<details>
  <summary>4. Account Management</summary>
  <ul>
    <li>Each team must create and use exactly one account on the Codabench platform.</li>
  </ul>
</details>

<details>
  <summary>5. Team Constitution</summary>
  <ul>
    <li>Team membership cannot be changed after the evaluation period begins.</li>
  </ul>
</details>

<details>
  <summary>6. Development Period Rules</summary>
  <ul>
    <li>Teams can submit up to 999 submissions.</li>
    <li>Results are visible only to the submitting team.</li>
    <li>Leaderboard is disabled.</li>
    <li>Warnings and errors are visible for each submission.</li>
  </ul>
</details>

<details>
  <summary>7. Evaluation Period Rules</summary>
  <ul>
    <li>The teams are constrained to make 3 submissions.</li>
    <li>Only the final submission will be considered official.</li>
    <li>Warnings and errors are visible for each submission.</li>
  </ul>
</details>

<details>
  <summary>8. Post-Competition</summary>
  <ul>
    <li>The gold labels will be released after the competition.</li>
    <li>The teams are encouraged to report results on all their system variants in their description paper.</li>
    <li>The official submission results must be clearly indicated.</li>
  </ul>
</details>

<details>
  <summary>9. Public Release of Submissions</summary>
  <ul>
    <li>Final team submissions may be made public after the evaluation period.</li>
  </ul>
</details>

<details>
  <summary>10. Disclaimer about the Datasets</summary>
  <ul>
    <li>Organizers and affiliated institutions provide no warranties on dataset correctness or completeness.</li>
    <li>They are not liable for dataset access or usage.</li>
  </ul>
</details>

<details>
  <summary>11. Peer Review Process</summary>
  <ul>
    <li>Each participant will review another team's system description paper.</li>
  </ul>
</details>

<details>
  <summary>12. Dataset Usage Restrictions</summary>
  <ul>
    <li>Datasets should only be used for scientific or research purposes.</li>
    <li>Any other use is explicitly prohibited.</li>
    <li>Datasets must not be redistributed or shared with third parties.</li>
    <li>Interested parties should be directed to the official website.</li>
  </ul>
</details>
<details>
  <summary>13. Final ranking</summary>
  <ul>
    <li>To be included in the official task ranking, you MUST submit a system description paper.</li>
  </ul>
</details>

# Dataset paper

The following paper will be used for the dataset: [**AfriHate: A Multilingual Collection of Hate Speech and Abusive Language Datasets for African Languages**](https://arxiv.org/pdf/2501.08284) by Shamsuddeen Hassan Muhammad, Idris Abdulmumin, Abinew Ali Ayele, David Ifeoluwa Adelani, Ibrahim Said Ahmad, Saminu Mohammad Aliyu, Nelson Odhiambo Onyango, Lilian D. A. Wanzare, Samuel Rutunda, Lukman Jibril Aliyu, Esubalew Alemneh, Oumaima Hourrane, Hagos Tesfahun Gebremichael, Elyas Abdi Ismail, Meriem Beloucif, Ebrahim Chekol Jibril, Andiswa Bukula, Rooweither Mabuya, Salomey Osei, Abigail Oppong, Tadesse Destaw Belay, Tadesse Kebede Guge, Tesfa Tegegne Asfaw, Chiamaka Ijeoma Chukwuneke, Paul Röttger, Seid Muhie Yimam, Nedjma Ousidhoum. This paper will provide the details necessary for understanding the data collection, annotation process, and baseline experiments.

# Communication

- Join our Discord Channel to ask questions and receive updates (coming soon).
- If you have any questions or issues, please feel free to create an issue.
- Contact organizers at: afrihate-africanlp-2025-organizers[at]googlegroups[dot]com

# FAQs
<details>
  <summary>Do I have to participate in all languages for a given track?</summary>
  <ul>
    <li>No, you can participate in one or more languages.</li>
  </ul>
</details>

<details>
  <summary>How will you verify my submitted model?</summary>
  <ul>
    <li>To be included in the final team rankings of our shared task, it is mandatory for participants to submit a system description paper describing their approaches and methodologies in detail, therefore ensuring scientific integrity.</li>
  </ul>
</details>

<details>
  <summary>When will you release the gold labels?</summary>
  <ul>
    <li>For the dev set, the gold labels will be released when the evaluation phase starts and the gold labels for the different test sets will be released after the competition is over.</li>
  </ul>
</details>

<details>
  <summary>Can I use LLMs in the different tracks?</summary>
  <ul>
    <li>Yes.</li>
  </ul>
</details>
<details>
<summary>Can I use additional datasets (e.g, publicly provided ones from other sources)?</summary>
  <ul>
    <li>Yes. Please do cite them in the system description paper.</li>
  </ul>
</details>
<details>
  <summary>How was the data collected?</summary>
   <ul>
    <li>
   The data collection process a standard one, you can check previous papers in the area to have an idea (e.g., https://aclanthology.org/S18-1001.pdf). We have data instances (text snippets) annotated by >3 annotators. The annotators decide whether the text convey some kind of hate or offensive content. 
   For details about the data sources, annotation guidelines, number of annotators per language, etc., please check our paper, Muhammad et al. (2025).
    </li>
   </ul>
</details>
<details>
  <summary>How was the data annotated and did you use LLMs to annotate it?</summary>
   <ul>
    <li>
  No. The data instances were annotated by (>=3) native speakers and no LLMs were involved in the process. The annotators labeled the whole sentences not the words.
    </li>
   </ul>
</details>
<details>
  <summary>Will I be included in the final ranking if I do not write a system description paper?</summary>
  <ul>
    <li>No. You MUST write a system description paper to be included in the final ranking.</li>
  </ul>
</details>

<details>
  <summary>I have never written a system description paper. How can I write one?</summary>
  <ul>
    <li>We will have an online writing tutorial and share resources to help you write a system description paper.</li>
  </ul>
</details>

<details>
  <summary> Our system did not perform very well, should I still write a system description paper? </summary>
 <ul>
    <li> We want to hear from all of you even if you did not outperform other systems! Write about the details of your system. (Yes we want your insights from any negative results!)</li>
  </ul>

</details>

#  Resources

2. SemEval 2025 Shared Tasks
3. Frequently Asked Questions about SemEval
4. Paper Submission Requirements
5. Guidelines for Writing Papers
6. Paper style files
7. Paper submission link (to be added)

# Organizers

| Organizer                  | Affiliation                                          | Role                        |
|----------------------------|------------------------------------------------------|-----------------------------|
| Shamsuddeen Hassan Muhammad | Bayero University; MasaKhane                 | Ph.D. Candidate in NLP      |
| Idris Abdulmumin            | Ahmadu Bello University; MasaKhane           | Ph.D. in NLP                |
| David Ifeoluwa Adelani     | Masakhane;                       | Ph.D. in NLP                |
| Ibrahim Sa’id Ahmad        | Bayero University; MasaKhane                  | Ph.D. in NLP                |
| Saminu Mohammad Aliyu      | Bayero University; MasaKhane                  | Ph.D. Candidate             |
Tadesse Destaw Belay | IPN; EthioNLP | Ph.D. Candidate |
| Abinew Ali Ayele           | Bahir Dar University; EthioNLP | Ph.D. Candidate             |
| Seid Muhie Yimam           | Universität Hamburg; Masakhane; EthioNLP             | Ph.D. in NLP                |
---

**NOTE** Some of the content in this page are adapted from **Our** previous shared task pages such as [SemEval2025-Task11](https://github.com/emotion-analysis-project/SemEval2025-Task11)
