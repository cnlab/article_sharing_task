# Log Files

This folder will store 4 different log outputs from the python script per subject, if the task is run successfully: one csv file for each of the runs (subj1_run1.csv and subj1_run2.csv),  one csv consisting of both runs (subj1.csv), and one .log file consisting of both runs (subj1.log).

Here is a key of what each column means:
1. content: the 'content' topic that the participant was randomly asked about - only applies to the content condition.<br>
2. cond: the condition of the trial.<br>
3. time: the length of the screen where participants read (and heard in headphones) the article headline and abstract.<br>
4. headline: text of the headline of the article for the trial.<br>
5. abstract: text of the abstract of the article for the trial.<br>
6. id: article ID (matches with the specified stimuli)<br>
7. between_fixation_raw: time of the between trial fixation (in ms)<br>
8. button_raw: time of button press by the participant (if blank, means participant failed to record a button press on time) (in ms)<br>
9. clue_onset_raw: time of "clue screen" onset (in ms)<br>
10. rate_onset_raw: time of the rate screen onset (in ms)<br>
11. rt_raw: time of the button press (in ms)<br>
12. run_raw: indicates run #<br>
13. within_fixation_raw: time of the within trial fixation (in ms)<br>
14. order: trial order #