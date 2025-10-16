# Data from: Temperament and cognitive flexibility across lemur species

Dataset DOI: [10.5061/dryad.8kprr4z18](10.5061/dryad.8kprr4z18)

## Description of the data and file structure

This data set consists of four files (.xlsx format) with the data from this study. Each file includes a data tab with all the data from the task, as well as a key tab where all the variables reported in the main data tab are defined (also appended below).

Each data file also includes the demographic characteristics of the lemurs that participated in the task (e.g., their species, age and sex); the relevant experimental parameters for the task (e.g., the trial type and trial number), and their responses (e.g., choices to approach or correct choices). NA values are defined for each task and indicate that a particular response measure was not applicable to that lemur (e.g., they did not participate in that task or they did not produce the relevant response).

### Files and variables

#### File: Cantwell_et_al_Lemurs_Novel_Object_Task.xlsx

**Description:** data from a task assessing responses to novel objects, by individuals from seven lemur species (willingness to approach, latency to approach, and duration in proximity)

##### Variables

* Code ID: Lemur's unique identifying code
* Species: Lemur's species (one of seven: ring-tailed lemurs; mongoose lemurs; black and white or red ruffed lemurs; Coquerel's sifakas; blue-eyed black lemurs; crowned lemurs; collared lemurs)
* Sex: Lemur's sex (M = male, F = female)
* Age: Age in years at time of test
* Trial_Num: Trial number
* Trial_Type: Trial type (baseline = table only; person = person sitting at table; static = stationary novel object; moving = moving novel object)
* DurationInProximity: Amount of time spent in the proximity area in seconds
* Approach: Whether or not the lemur approached the proximity area at any point during the trial (1 = yes, 0 = no)
* LatencyProximity: Latency to approach the proximity area in seconds (NA = lemur did not approach the proximity area within the trial time limits)

#### File: Cantwell_et_al_Lemurs_Persistence_Task.xlsx

**Description:** data from a task assessing persistence to acquire inaccessible food, by individuals from seven lemur species (duration of attempt to access)

##### Variables

* Code ID: Lemur's unique identifying code
* Species: Lemur's species (one of seven: ring-tailed lemurs; mongoose lemurs; black and white or red ruffed lemurs; Coquerel's sifakas; blue-eyed black lemurs; crowned lemurs; collared lemurs)
* Sex: Lemur's sex (M = male, F = female)
* Age: Age in years at time of test
* TotalManip: Total amount of time spent in contact with the box during the trial in seconds

#### File: Cantwell_et_al_Lemurs_Reversal_Learning_Task.xlsx

**Description:** data from a task assessing abilities to update responses across seven lemur species (trials to learn an initial contingency and responses after contingency is flipped)

##### Variables

* CodeID: Lemur's unique identifying code
* Species: Lemur's species (one of seven: ring-tailed lemurs; mongoose lemurs; black and white or red ruffed lemurs; Coquerel's sifakas; blue-eyed black lemurs; crowned lemurs; collared lemurs)
* Sex: Lemur's sex (M = male, F = female)
* Age: Age in years at time of test
* NumberLearningTrials: Number of trials needed to proceed with the test
* Trial_Num: Trial number within entire session
* Trial_Num_Type: Trial number within each trial type
* TrialType: The type of trial presented (exposure = food is hidden in full view of subject; learning trials = food is always hidden under the same box; test = contingencies are switched)
* Choice: Lemur's choice: 1 = correct choice (choice of the baited location on that trial); 0 = incorrect choice (choice of the empty location)

#### File: Cantwell_et_al_Lemurs_Task_Interrelationships.xlsx

**Description:** Task Interrelationships: integrated data from individuals' performance across the three tasks

##### Variables

* Code ID: Lemur's unique identifying code
* Species: Lemur's species (one of seven: ring-tailed lemurs; mongoose lemurs; black and white or red ruffed lemurs; Coquerel's sifakas; blue-eyed black lemurs; crowned lemurs; collared lemurs)
* Sex: Lemur's sex (M = male, F = female)
* Age: Age in years at time of test
* TotalManip: Total amount of time spent in contact with the box during the persistence task in seconds
* ReversalCorrect: Number of correct reversal learning trials (NAs are individuals who did not complete this task)
* LearningTrials: Number of trials required to proceed to the reversal phase in the reversal learning task (NAs are individuals who did not complete this task)
* NovelMean: Average amount of time spent in the proximity area across novel object trials in seconds, including no-approach responses (e.g., 0 seconds of proximity)
* LatencyMean: Average latency to approach the proximity area across novel object trials in seconds, including no-approach responses (latency set at 60-second maximum)
* NovelMeanApproach: Average amount of time spent in the proximity area across novel object trials in seconds, excluding trials where the lemur does not approach this area (NA = lemur never approached on any trial)
* LatencyMeanApproach: Average latency to approach the proximity area across novel object trials in seconds, excluding trials where the lemur does not approach this area (NA = lemur never approached on any trial)

#
