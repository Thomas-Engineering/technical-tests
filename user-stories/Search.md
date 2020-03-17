# User Story

**As an** Administrator **I want** to be able to search for candidates by their name **so that** when there are potentially 100s of candidates, I can easily reduce the size of the list and find the specific person I want more easily

# Acceptance Criteria

## AC1

**Given** that there are >1 candidates **when** I start typing into the "search people" box **then** 1 second later the list view should update with the results
    
## AC2

**Given** that there are >1 candidates **when** I type 3 or more characters **then** if the string I type in the box is present in any candidate's name, then show those cards in the list view

## AC2

**Given** that there are >1 candidates **when** I type 3 or more characters, pause and type again **then** the search should not execute more than every 1.5 seconds

## AC3

**Given** that there has been an assessment filter applied **when** I perform a search (as per above) **then** the results returned should respect the filter