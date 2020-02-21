# User Story

As an 
    Administrator
I want 
    To be able to search for candidates by their name
So that 
    When there are potentially 100s of candidates, I can easily reduce the size of the list and find the specific person I want more easily

# Acceptance Criteria

## AC1

Given
    That there are >1 candidates
When
    I start typing into the "search people" box
Then
    1 second later the list view should update with the results
    
## AC2

Given
    That there are >1 candidates
When
    I type 3 or more characters
Then
    If the string I type in the box is present in any candidate's name, then show those cards in the list view

## AC2

Given
    That there are >1 candidates
When
    I type 3 or more characters, pause and type again
Then
    The search should not execute more than every 1.5 seconds

## AC3

Given
    That there has been an assessment filter applied
When
    I perform a search (as per above)
Then
    The results returned should respect the filter