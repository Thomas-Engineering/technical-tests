# User Story

**As an** Administrator<br> 
**So that** I do not get an extremely long and overwhelming view when there are potentially hundreds of candidates<br>
**I want** to be able to page through long lists of candidates 


## Acceptance Criteria

**Given** that there are <=10 candidates<br>
**When** I view the summary page<br>
**Then** I should still see the pagination but it should be disabled out and only show 1 page available

#

**Given** that there are >10 candidates<br>
**When** I view the summary page<br> 
**Then** I want to see no more than 10 candidates per page of pagination

#

**Given** that there are >10 candidates<br>
**When** I view the summary page<br> 
**Then** I want to see how many pages of candidates there are in the pagination