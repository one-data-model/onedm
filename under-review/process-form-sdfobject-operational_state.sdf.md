# Basic info (filled in by contributor)

Model: https://github.com/one-data-model/playground/blob/master/sdfObject/sdfobject-operational_state.sdf.json

Model-name: Operational state

Proposed-name: operational_state.sdf

Description: This Resource describes the operational and job states on a device. The states can be read or set, setting indicates a desired state. A device may reject an attempt to set a state that would result in adverse operational characteristics. The Property \"machineStates\" is an array of the possible operational states. The Property \"currentMachineState\" is the current state of operation of the device. The Property \"jobStates\" is an array of the possible job states. The Property \"currentJobState\" is the currently active jobState. The Property \"runningTime\" is the ISO8601 encoded elapsed time in the current operational state. The Property \"remainingTime\" is the ISO8601 encoded time till completion of the current operational state. The Property \"progressPercentage\" is the percentage completeness of the current jobState.

Ecosystem: OCF

Model-responsible: Wouter

email: <of promotor>

submit-date: 2021-03-15

# Model metadata (filled in by contributor)

namespace: <namespace>

version: <commit-hash>

# ----------------

# Pre-review analysis (done by review board secretary)

SDF-verification-passed: <true/false>

OneDM-terminology-review-passed: <true/false>

Return-to-contributor if any of the above is checked


# ----------------

# Review board section

Reviewers: list of (assigned) reviewers

## Reviewer_1:     # One per reviewer

date: date

GitHub_issues: link to GH issues if filed

opinion: No_objections, Objection

comments: comment

Review_board_decision: <back to contributor w comments/spin up \
    convergence activity/to community for last call>

Review_board_date: <date>

# ----------------

# Last call

LC_Start_date: <date>

LC_End_date: <date + 2 weeks>

LC_objections_raised: <list>

LC_Comments: <need some way to feedback comments>

# ----------------

# Adoption decision

Review_board_adoption_decision: <tbd>

Review_board_adoption_decision_date: <date>

# ----------------

# Adoption

Link_to_adopted_model_in_OneDM_repo: <url>

Check_here_when_done: <X>

# Secretary archives this file in adopted models repo to maintain bit trail