# Survey-based-keyword-extraction-evaluation

***This is the repositoy for the paper: From Precision to Perception: User Surveys in the Evaluation of Keyword Extraction Algorithms.
* The aim of this study is to incorporate user perceptions in keyword extraction evaluation.
* We use TF-IDF, KeyBERT and Llama 2 to extract keywords from five articles.
* We Use potato annotation for survey design, see more details about potato here: https://github.com/davidjurgens/potato
* There are three experiments (preliminary, main and supplementary) to collect user perceptions on keywords.

* Experiment Configuration Summary

| **Experiment**     | **Number Of Task Instances Assigned To Each Participant** | **Number Of Task Instances In The Pool**                                          | **Number Of Questions For Each Task Instance** |
|--------------------|------------------------------------------------------------|------------------------------------------------------------------------------------|-----------------------------------------------|
| Preliminary        | 3                                                          | 30 (*5 articles × 3 keyword sets × 2 question groups*)                             | 9                                             |
| Main               | 4                                                          | 20 (*5 articles × 4 keyword sets*)                                                 | 5                                             |
| Supplementary      | 3                                                          | 5 (*all keyword sets showed on the same instance*)                                 | 9                                             |

* URLs for the five task articles used in the experiments:

| **Id** | **URL** |
|-------:|---------|
| **1** | [More than one in 10 young women in UK identify as lesbian, gay, bisexual or other](https://www.theguardian.com/society/2022/may/25/more-than-one-in-10-young-women-now-identify-lesbian-gay-bisexual-or-other) |
| **2** | [Euro 2022 and the future of women’s football](https://www.theguardian.com/news/audio/2022/jul/29/euro-2022-and-the-future-of-womens-football) |
| **3** | [14th-century samurai sword found in car at Swiss border](https://www.theguardian.com/world/2022/may/31/14th-century-samurai-sword-found-in-car-at-swiss-border) |
| **4** | [Kanye West escorted out of Skechers office after showing up unannounced](https://www.theguardian.com/music/2022/oct/26/kanye-west-escorted-out-skechers) |
| **5** | [An An, world’s oldest captive male giant panda, dies in Hong Kong zoo aged 35](https://www.theguardian.com/world/2022/jul/21/an-an-worlds-oldest-captive-male-giant-panda-dies-in-hong-kong-zoo-aged-35) |

*In total, 552 participants took part in these three experiments.
Total number of participants and distribution of gender.

| Experiment       | Participants |
|------------------|--------------|
| Preliminary      | 196          |
| Main             | 264          |
| Supplementary    | 92           |

| Gender                    | Preliminary | Main  | Supplementary |
|---------------------------|-------------|-------|----------------|
| Woman                     | 67.9%       | 61.0% | 63.0%          |
| Man                       | 29.1%       | 35.6% | 33.7%          |
| Non-binary                | 2.5%        | 2.3%  | 1.1%           |
| Prefer not to disclose    | 0.5%        | 0.4%  | 0.0%           |
| Prefer to self-describe   | 0.0%        | 0.7%  | 2.2%           |

| Age                  | Preliminary Experiment | Main Experiment | Supplementary Experiment |
|----------------------|------------------------|------------------|---------------------------|
| < 18                | 0.0%                   | 0.0%             | 0.0%                      |
| 18 - 24             | 14.3%                  | 13.3%            | 13.1%                     |
| 25 - 29             | 15.8%                  | 17.4%            | 18.5%                     |
| 30 - 34             | 19.9%                  | 14.8%            | 16.3%                     |
| 35 - 39             | 12.2%                  | 12.5%            | 17.4%                     |
| 40 - 44             | 9.7%                   | 11.0%            | 13.1%                     |
| 45 - 49             | 0.6%                   | 0.9%             | 0.3%                      |
| 50 - 54             | 11.2%                  | 5.7%             | 4.3%                      |
| 55 - 59             | 3.1%                   | 6.8%             | 4.3%                      |
| 60 - 65             | 5.1%                   | 6.4%             | 0.0%                      |
| > 65                | 3.1%                   | 4.2%             | 7.6%                      |
| Prefer not to disclose | 0.0%               | 0.0%             | 1.1%                      |

*In the preliminary experiment, we ask participants to provide their feedback on task fatigue level:
*Note: 182 out of 196 participants provided feedback on their fatigue level.*
| **Fatigue Level**                                   | **Participants** |
|-----------------------------------------------------|------------------|
| Exhausted *(1 article)*                             | 3                |
| Somewhat fatigued *(2 articles)*                    | 37               |
| Just right *(3 articles)*                           | 98               |
| Not too bad *(4 articles)*                          | 32               |
| Energised *(5 articles)*                            | 7                |
| Extremely energised *(6 or more articles)*          | 5                |

*An example of the task instance page for the preliminary experiment:
!(Survey_instance_config/instance.jpg)
