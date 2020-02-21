# User Story

As an 
    Administrator
I want 
    To be able to page through very long lists of candidates
So that 
    When there are potentially 100s of candidates I do not get an extremely long and overwhelming view of them

# Acceptance Criteria

## AC1

Given
    That there are <=10 candidates
When
    I view the page
Then
    I should still see the pagination but it should be greyed out and only show 1 page available and selected

  ## AC2

Given
    That there are >10 candidates
When
    I view the page
Then
    I want to see how many pages of candidates there are (up to 3 numbers), with more (or less) represented with an elipses (...).

## AC3

Given
    That I am on the first page of candidates
When
    I view the page
Then
    I want the "First" button to be greyed out

## AC4

Given
    That I am on the last page of candidates
When
    I view the page
Then
    I want the "Last" button to be greyed out