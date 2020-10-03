# Insurance_research

## PlanSwitchingAnalysis
- Creates dummy variables switch_up, switch_down and addition.
- Codes dummy variables using conditions on network_type and endo_type.

## ModifySwitchCodingData
- Creates dummy variables pre-post switch_up and pre-post switch_down, stay_high and stay_low.
- Codes dummy variables as 1 after switch and 0 before switch.
- Identifies people who buy a VIP plan and never switch (Stay_high = 1).
- Identifies policy holders who buy an economy plan and never switch (Stay_low = 1).

## GenerateSummaryStats
- Comapres the groups created in the above files on the variables NumClaims and avgclaimamt.
- Uses 2 sided t-test to compare if there is significant differences in the groups for those variables.
