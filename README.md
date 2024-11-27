# CleanedDataset-of-Movie-Preferences-and-Personality-Profiles
This repositery includes information from [the original dataset](https://github.com/shufanfan/Dataset-of-Movie-Preferences-and-Personality-Profiles), but several modifications have been made:
* Translated content from Chinese to English.
* Removed several rows containing invalid data.
* Included only the following fields: user_id, user gender, personality traits, movie watching frequency, and movie genre preferences.
* Based on the Cronbach’s Alpha, McDonald’s Omega, and Correlation Matrix analysis, I calculated the average scores for Conscientiousness, Extraversion, and Neuroticism. The dimensions Openness and Agreeableness were removed due to low reliability, indicating issues with the corresponding questions in the original questionnaire. As a result, data from these two dimensions will not be used in further research.
* Link to the questionnaire: https://observablehq.com/@nujguerra/survey-on-movie-watching-intentions-and-personalit
* Link to the original dataset: https://github.com/shufanfan/Dataset-of-Movie-Preferences-and-Personality-Profiles
## The columns representing in the dataset are:
* user_id: Unique identifier for each respondent
* Extraversion_Avg：The average score for Extraversion.
* Conscientiousness_Avg: The average score for Conscientiousness.
* Neuroticism_Avg: The average score for Neuroticism.
* E1: Score in the question: I enjoy being with many people
* E2: Score in the question: I am a very active and lively person.
* E3: Score in the question: I know many people like me.
* E4: Score in the question: I enjoy doing things with others.
* E5: Score in the question: I enjoy talking to strangers.
* E6: Score in the question: I consider myself to be always "in high spirits."
* C1: Score in the question: If I make a commitment, I try my best to fulfill it.
* C2: Score in the question: I always complete my work positively and effectively.
* C3: Score in the question: I consider myself a reliable person.
* C4: Score in the question: I always do my work in an orderly manner.
* C5: Score in the question: I am willing to work on work-related matters outside of work hours.
* N1: Score in the question: I often feel helpless and wish someone could help me solve my problems.
* N2: Score in the question: I often feel sad and depressed.
* N3: Score in the question: I often feel nervous and anxious.
* N4: Score in the question: I easily notice changes in my mood and feelings due to different environments.
* N5: Score in the question: I might be someone who brings trouble to myself.
* gender: The gender of the respondent.
* Movie_watching_frequency: How often does the respondent watch a movie? Values include: Several times a week, At least once a week, At least once every two weeks, At least once a month, and Less than once a month.
* favorite_genre: The genre of movies that the respondent watches most frequently.
