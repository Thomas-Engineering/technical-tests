# User Story

**As an** Administrator<br>
**So that** I can easily reduce the size of the list and find the specific person I want more easily when there are potentially hundreds of candidates<br>
 **I want** to be able to search for candidates by their name 

## Acceptance Criteria

**Given** that there are >1 candidates<br>
**When** I start typing in the search box<br>
**Then** there should be a slight delay after typing before the list updates with the new results
    
#

**Given** that there are >1 candidates<br>
**When** I type >1 characters into the search box<br>
**Then** the list should update to contain only candidates with those letters in their first or last name

#

**Given** that there are >1 candidates and any assessment filters have been applied<br>
**When** I type >1 characters into the search box<br>
**Then** the results returned should consider both the search term and the filter(s)