# Final Project Retrospective

## Team Members
- Student 1: Luis Maverick Gabriel (Luis)
- Student 2: Rafael Nico Maniquiz (Rick)

## 1. How did you divide the work between you and your partner?
_(Who worked on which features? How was the work assigned or negotiated?)_
- The add products and filter products are made by Rick, while the display products an d user management features are created by Luis.
The negotiation and work assignment was straight forward. We just grouped the work that has similar features.

## 2. What Git strategies or commands helped you most during the project?
_(E.g., branching, rebasing, frequent commits, etc.)_
- Branching allowed us to isolate the parts that we wanted to work on and just merge them to the whole project later on.
Frequent commits also allowed us to track changes to see where issues arised. An example of it is on how we accidentally removed a function—we were able to track down when it happened and fix it.

## 3. Describe a merge conflict you encountered. What caused it and how did you resolve it?
_(Include any lessons learned or techniques used to resolve the issue.)_
- For the first merge conflict, Rick made the ProductHandler class have the ability to add products to the product list and merged it to main. Luis pulled a pre-merged ProductHandler version into his branch when he started working in the user management system, in which he added a checkpoint in the add_product method in ProductHandler to check if the user adding the product was a seller. We resolved the conflict by retaining Luis’ addition.
- For the second merge conflict. Rick wanted to remove the filter_products method from the ProductHandler class and instead place it in the product_view.pseudo as a stand alone function. The conflict emerged since Luis has already merged a version of his display product feature with the display_products function. The conflict was resolved by integrating the filter_products function into the display_products functions—retaining both functionalities.

## 4. What were the biggest challenges you faced as a team?
_(This can include communication, Git usage, or coordination.)_
- There were some challenges with communication while we were working on the project. There was an instance when we inserted a function in the wrong file but luckily we were able to spot our mistakes immediately and were able to fix it. Another is during the planning phase, there were times where we cannot fully explain our thoughts leading to confusion and miscommunication but we were able to pull through in the end and finish the project. 
## 5. What did you learn about using Git in a collaborative setting?
_(Any insights or habits you’d apply in future projects?)_
- Using git is a great way to collaborate on projects since everything that we commit or push to the projects are recorded so we are able to immediately spot mistakes and get updates on everyone’s progress. Overall this improved how we were able to execute the project and how we communicated and fixed our mistakes.

## 6. How would you improve your workflow next time?
_(Think about technical habits and teamwork practices.)_
- Utilizing efficient communication channels together with github cam greatly improve our workflow. For example, having to notify our team immediately about our pull requests and if issues arise. Another thing that we can improve is providing a much more detailed description of our commit messages and pull requests, this can help our teammates immediately understand what we are trying to do.

## 7. Optional: Any feedback on the activity?
_(What worked well? What was confusing or could be improved?)_
- The activity went well and we learned a lot.
