| | | |
|-|-|-|
| | | |
| | | |
|Add usecase (Basic Flow)| | |
| | | |
|Steps|Actions|Expected Result|
|Select Project|1. User logs in to the Workflow system. 2. User navigates to the list of projects. 3. User selects the desired project from the list.|The user successfully logs in and selects the desired project.|
|Select Workflow|1. User navigates to the selected project's page. 2. User accesses the list of workflows associated with the project. 3. User selects the workflow in which they want to add the use case.|The selected workflow is displayed along with its stages and substages/tasks.|
|Initiate Use Case Addition|User clicks on the "Add Usecase" button within the selected workflow.|The system opens a form to gather basic use case details.|
|Enter Basic Use Case Details|1. User enters the name of the use case in the designated field. 2. User provides a description for the use case. 3. Optionally, user assigns a priority to the use case. 4. User clicks on the "Save" button to submit the use case details.|The entered information is accurately captured in the form, and the use case details are saved successfully.|
|Associate with Workflow|The system automatically associates the newly added use case with the stages and substages/tasks of the selected workflow.|The use case is seamlessly integrated into the workflow structure.|
|Assign Tasks|1. User reviews the workflow stages and substages/tasks. 2. User assigns relevant tasks to the selected resources based on the requirements of the newly added use case.|Tasks are successfully assigned to resources based on the use case requirements.|
| | | |
|Add usecase (Alternate Flow)| | |
| | | |
|Steps|Actions|Expected Result|
|User initiates the addition of a new use case within the selected workflow.|1. User navigates to the project overview page. 2. User selects the desired project from the list. 3. User selects the workflow where they want to add the use case. 4. User clicks on the "Add Usecase" button within the selected workflow.|The system presents a form to gather basic use case details.|
|User fills in the necessary details for the new use case.|1. User enters the name of the use case. 2. User provides a description of the use case. 3. User selects the priority level for the use case (optional).|All required fields are filled with valid information.|
|User decides to cancel the use case addition process.|User clicks on the "Cancel" button.|The system prompts the user with a confirmation dialog to confirm the cancellation action.|
|User confirms the cancellation action.|User clicks on the "Yes" or "Confirm" button to confirm the cancellation.|The system cancels the use case addition process and returns the user to the previous screen without saving any entered information.|
|User decides to continue with the use case addition process.|User clicks on the "No" or "Cancel" button to decline the cancellation.|The system retains the entered information and allows the user to continue with the use case addition process.|
|User encounters an unexpected error while cancelling the use case addition process.|User clicks on the "Cancel" button.|The system fails to cancel the use case addition process and displays an error message informing the user about the issue.|
|User retries the cancellation action after encountering an error.|User clicks on the "Cancel" button again.|The system successfully cancels the use case addition process without any errors and returns the user to the previous screen.|
