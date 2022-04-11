# yocket_assignment
This repository  contains all the jupyter notebook related to the yocket assessment for QA automation job role

the basic idea was to use selenium and with python to autoamte the webactions of traversing all through finding a best cost effcient university for a completely random inputs 


## Setting up the environment 
pip install -U selenium
pip install jupyter lab / jupyter notebook

#### start the jupyter lab / jupyter notebook through command prompt

Read the https://github.com/lone-lobo/yocket_assignment/blob/main/Automation%20Testing%20Assignment%20(1).pdf for the problem description


## Thought process 
 1. automate each page individually 
 2. check if we have chat_box popped up during steps
 3. random inputs for all pages
 4. handle the exceptions while navigating through different pages
 5. sort by cost at the final page and retrieve the first result
 6. stitch all pieces together while handling handling server response through explicit waits
 7. check if we are on proper page before moving to next
 8. handle zero result output , for random inputs if no matching university found 

