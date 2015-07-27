# Survey Module #

This module introduces a new question type for surveys. It consists of a 5-star scala and  
a description to both sides of the scala.  

This question type changes the way the result is calculated. The OTRS-standard counts the responses to each  
answer and divides 100% with that amount. This question-type introduces 5 answers (0%, 25%, 50%, 75%, 100%)  
which are created for each question of this type.  The calculation then is:  
SUM += $CurrentVoteCounter * $CurrentAnswerPercentage  
RESULT = $SUM / $TotalResponses  

A question of this type is complete iff two descriptions (left + right) are configured.  Changes to the  
question will only update answer 1 + 5 (as they hold the description values). When trying to delete one  
of the answers, all are deleted automatically.  

This module contains:  
*   Three modified templates (for each the perl and .tt file)  
    Edit  
    Zoom  
    Public  
* A .css file for representation    

  