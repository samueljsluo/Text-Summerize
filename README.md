# Text Summerize
 
## This notebook aims to compare different mathods of text summarization.
 
Text: 

```
SINCE PRESIDENT JOE Biden on March 11 directed that states make every adult eligible for a coronavirus vaccine by May 1, many states have ramped up their vaccine rollouts; 
moving up dates and announcing new eligibility to meet the president's timeline. But vaccine rollouts vary by state.
Alaska was the first state to announce and implement eligibility for all adults on March 9. 
Mississippi has since followed suit, with all individuals 16 and older becoming eligible on March 16, while West Virginia opened up eligibility to all adults on March 22. 
All Arizonans 16 and older are eligible for a vaccine on March 24, and adults in Texas are eligible as of March 29.
Still, most states are weeks away from opening up eligibility entirely. 
For the majority of states, elderly populations and health care workers have been prioritized, with eligibility being opened up to those with certain high-risk medical conditions and other essential workers more recently.
But just because states make certain populations eligible does not mean those individuals will secure a vaccine anytime soon, and some populations will continue to be prioritized above others, depending on the state's approach. 
While some states have taken on an age-based vaccine rollout, others have instituted an equity-based rollout, while others have gone for a hybrid approach. 
Rhode Island, for example, is accelerating distribution of the vaccines to those living in ZIP codes disproportionately impacted by the coronavirus, and to those with certain health conditions that make them more vulnerable.
Regardless of approach, some individuals across the country are getting vaccinated without necessarily having priority at the state level, as vaccine rollouts operate differently at the federal, state and county levels. In Delaware, for example, those 50 and older are eligible for a vaccine at local pharmacies, but not with medical providers, or at hospitals. 
And in various parts of the country others, still, are able to get a dose of a vaccine by being in the right place at the right time, such as at a grocery store as the day comes to an end, and unused vaccines run the risk of going to waste.
```

* PyTextRank with SpaCy

```
SINCE PRESIDENT JOE Biden on March 11 directed that states make every adult eligible for a coronavirus vaccine by May 1, many states have ramped up their vaccine rollouts; 
moving up dates and announcing new eligibility to meet the president's timeline.
For the majority of states, elderly populations and health care workers have been prioritized, with eligibility being opened up to those with certain high-risk medical conditions and other essential workers more recently.
But vaccine rollouts vary by state.
But just because states make certain populations eligible does not mean those individuals will secure a vaccine anytime soon, and some populations will continue to be prioritized above others, depending on the state's approach.
Regardless of approach, some individuals across the country are getting vaccinated without necessarily having priority at the state level, as vaccine rollouts operate differently at the federal, state and county levels.
```

* TextRank and Universal Sentence Embedding

```
Regardless of approach, some individuals across the country are getting vaccinated without necessarily having priority at the state level, as vaccine rollouts operate differently at the federal, state and county levels.
But just because states make certain populations eligible does not mean those individuals will secure a vaccine anytime soon, and some populations will continue to be prioritized above others, depending on the state's approach.
SINCE PRESIDENT JOE Biden on March 11 directed that states make every adult eligible for a coronavirus vaccine by May 1, many states have ramped up their vaccine rollouts; moving up dates and announcing new eligibility to meet the president's timeline.
All Arizonans 16 and older are eligible for a vaccine on March 24, and adults in Texas are eligible as of March 29.
In Delaware, for example, those 50 and older are eligible for a vaccine at local pharmacies, but not with medical providers, or at hospitals.
```

* Gensim Summarization

```
SINCE PRESIDENT JOE Biden on March 11 directed that states make every adult eligible for a coronavirus vaccine by May 1, many states have ramped up their vaccine rollouts; 
Mississippi has since followed suit, with all individuals 16 and older becoming eligible on March 16, while West Virginia opened up eligibility to all adults on March 22.
For the majority of states, elderly populations and health care workers have been prioritized, with eligibility being opened up to those with certain high-risk medical conditions and other essential workers more recently.
But just because states make certain populations eligible does not mean those individuals will secure a vaccine anytime soon, and some populations will continue to be prioritized above others, depending on the state's approach.
Regardless of approach, some individuals across the country are getting vaccinated without necessarily having priority at the state level, as vaccine rollouts operate differently at the federal, state and county levels.
```
