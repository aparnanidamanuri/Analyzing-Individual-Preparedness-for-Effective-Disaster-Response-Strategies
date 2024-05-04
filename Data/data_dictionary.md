# Data Dictionary for FEMA National Household Survey Dataset

## Demographic Information
- `id`: Unique respondent identifier.
- `age`: Age of the respondent.
- `sex`: Sex of the respondent.
- `education`: Highest completed level of education.
- `vocational`: Attendance at a technical trade or vocational school.
- `ethnicity`: Hispanic, Latino, or Spanish origin.
- `race_selfid`: Self-identified race of the respondent.
- `disability`: Presence of a disability or health condition affecting emergency response capacity.

## Household Composition
- `care`: Responsibility for assisting an elderly person or someone with a disability.
- `numadult`: Number of adults living in the household.
- `numchild`: Number of children under the age of 18 in the household.
- `numchild_school`: Whether any children attend school outside the home.
- `numchild_school_emerplan`: Awareness of the school's emergency plan.

## Language and Communication
- `primarylanguage`: Primary or main language spoken in the household.
- `language`: Preferred language for survey completion.

## Housing and Living Conditions
- `homeownership`: Homeownership status (rent or own).
- `rentmortgage`: Monthly rent or mortgage expenses.
- `hometype`: Type of home the respondent lives in.
- `income`: Total household annual income before taxes.

## Employment and Socioeconomic Status
- `employment`: Current employment status.
- `socioeconomically_disadvantaged`: Socioeconomic status based on state, household size, and income.

## Minority Status and Experiences
- `lgb_selfid`: Self-identification as LGBTQIA+.
- `lgb_orientation`: Sexual orientation.
- `lgb_gender`: Gender identity.
- `lgb_obstacles`: Obstacles in accessing preparedness resources due to LGBTQIA+ identity.
- `rel_selfid`: Affiliation with an organized religion or spiritual practice.
- `rel_affiliation`: Specific religion or spirituality affiliation.
- `rel_minority`: Consideration as a religious minority.
- `rel_influence`: Influence of religious or spiritual identity on preparedness.

## Disaster Preparedness
- `dis_prep`: Consideration of preparing for a disaster.
- `dis_soc`: Degree of preparedness for a disaster.
- `dis_awareness`: Awareness of information on disaster preparedness.
- `dis_exp`: Experience with the impacts of a disaster.
- `dis_stepshelp`: Belief in the efficacy of preparedness steps.

## Calculated Fields
- `sixtyplus`: Age collapsed into two groups (18-59, 60+).
- `englishlang`: Whether English is the primary language spoken in the household.
- `rurality`: Rurality designation based on ZIP code, county, and state.
- `income_agg`: Household annual income collapsed into categories.

## Imputed Fields
- `age_imputed`: Indicator for whether the value in 'age' is imputed.
- `sex_imputed`: Indicator for whether the value in 'sex' is imputed.
- `education_imputed`: Indicator for whether the value in 'education' is imputed.
- `race_imputed`: Indicator for whether the value in 'race_selfid' is imputed.
- `disability_imputed`: Indicator for whether the value in 'disability' is imputed.
- `homeownership_imputed`: Indicator for whether the value in 'homeownership' is imputed.
- `income_imputed`: Indicator for whether the value in 'income' is imputed.
- `ethnicity_imputed`: Indicator for whether the value in 'ethnicity' is imputed.

## Survey Metadata
- `date`: Date of survey completion.
- `time`: Time of survey completion.

Please note that this data dictionary is a high-level overview and may not include every variable present in the dataset. For a complete list of variables and their descriptions, refer to the full dataset documentation provided by FEMA.

