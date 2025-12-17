jsPsych – initializes and controls the experiment flow
NUM_TRIALS – number of trials entered by the user
get_trial_count – collects trial count from the participant
go_trial – shows left/right arrow image and records key response
stop_trial – shows stop signal image and blocks responses
correct_key – stores the correct key for the current go trial
correct – indicates whether the participant pressed the correct key
trial_sequence – array holding all trials in order
build_trials – generates trials and inserts a stop trial every 100th trial
Keys: Left → f, Right → j, Stop → no key
Run: Open index.html
Output: CSV file downloads automatically