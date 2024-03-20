**Workflow Use cases**

**Create project**

**Actors:**

User: An individual with access to the system, responsible for managing projects.

**Preconditions:**

The user has successfully logged into the application.

The user has access privileges to create new projects.

**Basic Flow:**

User Navigation:

User navigates to the Workflow Management section through the navigation bar within the application's interface.

Dashboard Display:

The system presents the Workflow Dashboard, offering an overview of all ongoing projects, including key details such as project names, statuses, and timelines.

Selecting Project Option:

From the sidebar menu within the Workflow Management section, the 

user selects the "Projects" option.

Viewing Existing Projects:

The system retrieves and displays all existing project details, including project names, descriptions, assigned resources, and current statuses.

Initiating New Project Creation:

<a name="_int_klgm5cuk"></a>Within the project view, the user clicks on the "Create Project" button to start the process of creating a new project.0

Entering Basic Project Details:

The system prompts the user to provide basic details for the new project, such as project name, description, start date, and end date.

The user fills in the required information and proceeds by clicking the "Next" button.

Managing Resource Pool:

The system presents the "Resource Pool" interface, allowing the user to add resources to the project.

The user adds necessary resources by selecting from available options or creating new ones.

After adding resources, the user proceeds by clicking the "Next" button.

Reviewing Project Details:

The system displays the "Review Screen," presenting a summary of all entered project details and assigned resources.

The user reviews the information for accuracy and completeness.

Editing or Finalizing:

If necessary, the user can choose to edit any project details by clicking on the "Edit" button, which navigates back to the respective step (e.g., "Set Up Project" or "Resource Pool").

Once satisfied with the details, the user clicks on the "Create" button to finalize the project creation process.

**Postconditions:**

A new project is successfully created within the system, incorporating the provided details, and assigned resources.

**Alternative Flows:**

If there are errors in the data input during any step:

The system prompts the user to correct the errors before proceeding.

If the user decides to cancel project creation at any stage:

The user can navigate back using the application's controls or cancel the process entirely.

If the user lacks sufficient permissions to create a project:

The system displays an error message indicating insufficient privileges, preventing further progress until appropriate permissions are granted.


`                                              `**Add Workflow**

**Actors:**

**User:** An individual with access to the system, responsible for managing projects and workflows.

**Preconditions:**

The user has successfully logged into the workflow management system.

The user has access privileges to modify project workflows.

The user has navigated to the project's overview and resources pool.

**Basic Flow:**

Accessing Overview and Resources Pool:

User navigates to the project's overview and resources pool within the workflow management system.

Selecting Workflow Addition Option:

User selects the "Add Workflow" button from the overview section or the resources pool section, depending on preference.

Choosing Workflow Creation Method:

The system presents the user with the option to either create a new workflow template or select an existing template from the catalogue.

The system presents the user with a list of available workflow templates or allows the user to create a new workflow from scratch.

The user selects the desired workflow template or opts to create a custom workflow.

Creating New Workflow Template:

User selects the "Create Template" option.

User defines stages, substages, and checklist items as necessary for the new workflow template.

User confirms the creation of the new template.

Selecting Existing Template:

User selects the desired workflow template from the catalogue of existing templates.

Reviewing and Confirming:

Users review the selected or newly created workflow template to ensure it meets the project's requirements.

User confirms the selection by clicking the "Add Workflow" button.

Workflow Addition Confirmation:

The system confirms that the selected workflow has been successfully added to the project.

User receives a confirmation message indicating the successful addition of the workflow.

**Postconditions:**

The selected workflow template is added to the project and is ready for implementation and tracking.

**Alternative Flows:**

If the user decides to add a workflow directly from the resources pool:

User navigates to the resources pool section within the overview and selects the "Add Workflow" option.

If there are errors in the workflow creation process:

The system prompts the user to rectify any errors and resubmit the workflow details.

If the user decides to cancel the workflow addition process:

User can navigate back using the application's controls or cancel the process altogether. 




`                                   `**Add Usecase to project**

**Actors:**

User: An individual with access to the system, responsible for managing projects and workflows.

**Preconditions:**

The user has successfully logged into the workflow management system.

The user has access privileges to modify project workflows.

The user has navigated to the section where workflows are managed and added.

**Basic Flow:**

Accessing Workflow Template:

User navigates to the project's workflow section and selects a workflow template from the available options.

Viewing Kanban Board:

The system displays the Kanban board corresponding to the selected workflow template.

Adding Use Case:

User clicks on the "Add Use Case" button within the Kanban board interface.

Entering Basic Details:

The system presents a form for entering basic details of the use case, such as title, description, and priority.

User fills in the required information and clicks the "Save" button.

Completing Stages:

The system prompts the user to provide additional mandatory information or proceed to the next stage of the use case creation process.

User fills in the mandatory information and clicks the "Next Stage" button to advance through all stages of use case creation.

Finalizing and Saving:

Once all stages are completed, the user confirms the details and clicks the "Save" button to finalize the use case creation process.

Confirmation:

The system confirms that the use case has been successfully added to the project.

User receives a confirmation message indicating the successful addition of the use case.

**Postconditions:**

The newly created usecase is added to the usecase Kanban board, allowing for further tracking and management within the workflow.

**Alternative Flows:**

If the user decides to cancel the usecase creation process at any stage.

User can navigate back using the application's controls or cancel the process altogether.

If there are errors in the data input during any step:

The system prompts the user to correct the errors before proceeding.

If the user decides to edit the usecase details after initial creation.

User can navigate to the usecase on the Kanban board and make necessary edits as required.




`                                     `**Assign task to user**

**Actors:**

User: An individual with access to the workflow management system, responsible for overseeing projects and assigning tasks.

**Preconditions:**

User has a valid account and is logged into the workflow management system.

<a name="_int_rukfmiux"></a>User has access privileges to view project details and assign tasks.

User has navigated to the Workflow Management section through the sidebar menu.

**Basic Flow:**

User Navigation:

<a name="_int_lvc7nsez"></a>User logs into the application and navigates to the Workflow Management section through the sidebar menu.

Project Dashboard Display:

The system presents the Project Dashboard, providing an overview of all projects accessible to the user.

Viewing Project Details:

User selects the project they wish to view details for from the list of projects displayed on the dashboard.

Accessing Project Overview:

User accesses the overview section of the selected project to review its details, progress, and any other relevant information.

Task Assignment Action:

Within the project overview, <a name="_int_bz5wku1v"></a>user clicks on the "Action" button or similar option to initiate the task assignment process.

Entering Task Details:

The system displays a pop-up form or a dedicated task assignment interface where user can enter basic details of the task to be assigned.

User fills in the required details such as task title, description, due date, priority, and the user to whom the task will be assigned.

Submitting Task Assignment:

Once all necessary details are filled in, <a name="_int_e7esnmua"></a>user clicks the "Submit" or "Assign Task" button to confirm the task assignment.

Viewing Assigned Users:

After successfully assigning the task, the system displays a screen showing all existing assigned users for the same project.

<a name="_int_rufgrbj1"></a>User can review the list of assigned users to ensure proper distribution of tasks and responsibilities.

**Postconditions:**

The task is successfully assigned to the designated user within the selected project.

<a name="_int_gwvivyfl"></a>User can view the updated project details and assigned task information in real-time.

**Alternative Flow:**

If there are no existing assigned users for the project:

<a name="_int_ninvcy02"></a>The system displays a message indicating that no users are currently assigned to tasks within the project.

<a name="_int_o25f0hi9"></a>User can proceed with assigning the task without needing to review existing assignments.

