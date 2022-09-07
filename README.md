# ASR (automatic speech recognition) Benchmarks for Turkish
DEVELOPMENT OF TEST CORPUS WITH LARGE VOCABULARY FOR TURKISH SPEECH RECOGNITION SYSTEM AND A NEW TEST PROCEDURE


The most fundamental problem in the automatic speech recognition systems is not the development of a domainspecific automatic speech recognition system, but the development of an automatic speech recognition system with a large vocabulary. Developed automatic speech recognition systems should be tested with a large vocabulary test dataset. For this reason, an automatic speech recognition test corpus was prepared within the scope of the study. Prepared automatic speech recognition test corpus includes conversations from 20 different areas and text files of these conversations. The test procedure presented in the study was also tested on Turkish automatic speech recognition systems with a large vocabulary. It has been observed that the word error rate results ranged between 14-21%. The test corpus and test procedure with a large vocabulary prepared are guiding for the success of automatic speech recognition systems in future studies to be revealed more clearly.

# Preparation of The Turkish ASR Test Corpus 
In speech recognition systems developed specifically for the field, the vocabulary of spoken words belongs to a certain set. However, it is not possible to carry out spontaneous conversations with words belonging to a certain topic. Therefore, within the scope of this study, a test corpus was prepared to test Turkish ASR systems with a large vocabulary. The vocabulary of words used in real life is quite large. Besides, the number of words spoken in rich languages such as Turkish is very high. In addition, conversations in daily life consist of different domains. For example, sports, politics, or science represent a few of these domains. For this reason, a test corpus consisting of different domains has been prepared to test the academic studies in the literature and Turkish ASR systems with a large vocabulary already developed by technology companies. However, it is not enough to just create the test corpus from different domains. Different speakers from different domains should be included in the corpus. For this reason, data were obtained from speakers of different genders in different domains. The domains and speaker information determined for the test corpus prepared are given in Table 1. As seen in Table 1, 20 different domains spoken in daily life in Turkish were added to the test corpus. The parliamentary speeches, which are one of these domains, were obtained from the minutes of the Turkish Grand National Assembly. Conversations about other fields were selected on YouTube. Since there are text equivalents in the minutes of the parliamentary speeches, the transcripts were used in the speech-text matching. However, the text equivalent of the speeches received on YouTube was obtained by real users by listening to the speech recording. In addition, by keeping the gender distribution balanced, the test corpus was ensured to be more effective. For this reason, speech recordings were obtained from a total of 286 different speakers, 143 male and 143 female speakers. The information about the speeches made by different speakers according to a different domain is given in Table 2.

# Table 1. Speaker information by domain
|     Domain   Name    |     Speaking   Time / Seconds    |     Number   of Male Speakers    |     Number   of Female Speakers    |
|----------------------|----------------------------------|----------------------------------|------------------------------------|
|     Science          |     335                          |     5                            |     5                              |
|     Education        |     327                          |     5                            |     5                              |
|     Economy          |     703                          |     9                            |     9                              |
|     Philosophy       |     325                          |     5                            |     5                              |
|     Physics          |     318                          |     5                            |     5                              |
|     News             |     325                          |     5                            |     5                              |
|     Weather          |     397                          |     5                            |     5                              |
|     Law              |     287                          |     5                            |     5                              |
|     Business         |     393                          |     5                            |     5                              |
|     Culture          |     1.067                        |     10                           |     10                             |
|     Magazine         |     960                          |     12                           |     12                             |
|     Math             |     301                          |     5                            |     5                              |
|     Parliament       |     2.088                        |     19                           |     19                             |
|     Humor            |     227                          |     5                            |     5                              |
|     Health           |     838                          |     11                           |     11                             |
|     Art              |     805                          |     10                           |     10                             |
|     Sociology        |     305                          |     5                            |     5                              |
|     Sport            |     425                          |     6                            |     6                              |
|     Agriculture      |     355                          |     5                            |     5                              |
|     Technology       |     431                          |     6                            |     6                              |
|     Total            |     11.212                       |     143                          |     143                            |


# Table 2. Speaker durations by domain
|     Domain   Name    |     Total   Speaking Time of Male Speakers /    Seconds    |     Total   Speaking Time of Female Speakers /    Seconds    |     Total   Speaking Time /   Seconds    |
|----------------------|------------------------------------------------------------|--------------------------------------------------------------|------------------------------------------|
|     Science          |     184                                                    |     151                                                      |     335                                  |
|     Education        |     160                                                    |     167                                                      |     327                                  |
|     Economy          |     388                                                    |     315                                                      |     703                                  |
|     Philosophy       |     147                                                    |     178                                                      |     325                                  |
|     Physics          |     170                                                    |     148                                                      |     318                                  |
|     News             |     191                                                    |     134                                                      |     325                                  |
|     Weather          |     179                                                    |     218                                                      |     397                                  |
|     Law              |     132                                                    |     155                                                      |     287                                  |
|     Business         |     212                                                    |     181                                                      |     393                                  |
|     Culture          |     667                                                    |     400                                                      |     1.067                                |
|     Magazine         |     477                                                    |     483                                                      |     960                                  |
|     Math             |     167                                                    |     134                                                      |     301                                  |
|     Parliament       |     1.116                                                  |     972                                                      |     2.088                                |
|     Humor            |     119                                                    |     108                                                      |     227                                  |
|     Health           |     442                                                    |     396                                                      |     838                                  |
|     Art              |     394                                                    |     411                                                      |     805                                  |
|     Sociology        |     171                                                    |     134                                                      |     305                                  |
|     Sport            |     225                                                    |     200                                                      |     425                                  |
|     Agriculture      |     208                                                    |     147                                                      |     355                                  |
|     Technology       |     250                                                    |     181                                                      |     431                                  |
|     Total            |     5.999                                                  |     5.213                                                    |     11.212                               |

# Table 3. Number of words by domain

|     Domain   Name    |     Number   of Words    |     Number   of Unique Word    |
|----------------------|--------------------------|--------------------------------|
|     Science          |     633                  |     424                        |
|     Education        |     632                  |     414                        |
|     Economy          |     1576                 |     907                        |
|     Philosophy       |     651                  |     424                        |
|     Physics          |     673                  |     422                        |
|     News             |     587                  |     436                        |
|     Weather          |     898                  |     476                        |
|     Law              |     520                  |     381                        |
|     Business         |     789                  |     505                        |
|     Culture          |     1440                 |     927                        |
|     Magazine         |     1711                 |     970                        |
|     Math             |     712                  |     383                        |
|     Parliament       |     3.723                |     1.756                      |
|     Humor            |     473                  |     324                        |
|     Health           |     1354                 |     832                        |
|     Art              |     1470                 |     845                        |
|     Sociology        |     573                  |     409                        |
|     Sport            |     892                  |     568                        |
|     Agriculture      |     694                  |     466                        |
|     Technology       |     894                  |     579                        |
|     Total            |     20.895               |     12.448                     |

# Table 4. WER results for different Turkish ASR systems
|     Name of Turkish ASR System    |     Minimum WER    |     Maximum WER    |     Average WER    |
|-----------------------------------|--------------------|--------------------|--------------------|
|     Polat and Oyucu               |     0.0            |     68.0           |     20.24          |
|     Google Speech to Text         |     1.0            |     96.0           |     20.75          |
|     Amazon Transcribe             |     0.0            |     77.0           |     19.25          |
|     Azure Speech to Text          |     0.0            |     58.0           |     14.35          |

# Conclusion and Recommendations
Due to the significant improvements in the success rates of automatic speech recognition systems, the application areas are increasing day by day. However, even state-of-the-art speech recognition systems that give some comparative results do not give successful results outside the vocabulary area. For this reason, first of all, related studies were reviewed. Then, a test corpus was prepared for Turkish ASR systems, where we can evaluate the large vocabulary problem. Using the prepared test corpus, a test procedure was prepared for the comparative evaluation of future Turkish ASR systems.

The test procedure prepared within the scope of the study has been tested on Google Speech to Text, Amazon Transcribe and Azure Speech to Text services. It has also been tested on the ASR system, which has a large vocabulary prepared by Oyucu and Polat in 2020. It has been observed that the obtained WER results vary between 14-21% and different ASR services have their advantages and disadvantages. Google's preprocessing of speech files and not processing files above a certain signal-to-noise ratio causes the maximum WER value to be high. However, this situation is completely different in Azure and Amazon. Therefore, they have a lower maximum WER ratio. When the existing Turkish ASR services were examined, it was seen that the problem of large vocabulary could not be solved. For this reason, studies should be carried out on the problem of large vocabulary for Turkish in future studies. The test corpus and test procedure presented in this study will guide the studies on large vocabulary.

# Sample audio and text files that can be used for ASR

# You can contact us for more data.

saadinoyucu@gmail.com

