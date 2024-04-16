**Review Page Use Case:**

**Main Success Scenario (Basic Flow):**

**Navigates to Review Page:**

User navigates to the Review Page for the project setup.

System displays the setup details of the project for user review.

**Validate Project Setup:**

User reviews the setup details, including Project Icon (if available), Project Name, Project Department, Project Description, Project Duration, and Resource Pool.

System ensures that all mandatory fields are filled, and the resource pool is correctly populated.

**Validate Resource Pool:**

User verifies the resource pool information, including Name, Designation, Mail-Id, and available Actions for each resource.

System confirms that the resource pool is correctly populated and relevant resources are assigned to the project.

**Search Employee:**

User may use the search functionality to find specific employees within the resource pool.

System displays search results based on the entered criteria.

**Extensions (Alternative Flows):**

a. Invalid Project Setup:

Condition: If any mandatory field is missing or contains invalid data.

System Action: System prompts the user to correct the invalid information.

User Action: User provides the required information or corrects the invalid data.

**Click on Create:**

User clicks the "Create" button to initiate project creation.

System creates a new project.

Extensions (Alternative Flows):

a. Error in Creation:

Condition: If there is an error during project creation (e.g., database connection issue, system failure).

System Action: System notifies the user about the error and suggests retrying later.

User Action: User may try to create the project again or contact support for assistance.
