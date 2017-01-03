Step 1: Create a new Visualforce page with the code in Sharing.vfp. 
!! Replace Milestone1_Project__c with the object that you're working with. For instance a standard object like 'Lead' or 'Opportunity' or a custom object such as 'Custom_Object__c'. You may always find the API name in the settings of the object.

Step 2: After you create it, in the Visualforce Pages list view, Click Security next to it and ensure all profiles that need to access are added. 

Step 3: Go to the object that you want to create the Sharing button for, and under Buttons, Links, and Actions, create a new Action. The action type is Custom Visualforce and select the VF page you just made. Do not set a Standard Label Type, but give it a Label as its required. No need to edit anything else. 

Step 4: Go edit the page layout and add this new action from the Salesforce1 & Lightning Actions section. Drag it into the Salesforce1 and Lightning Experience Actions. If its not dragging in at first, hover your cursor over the section and click the wrench at the very right. 

Enjoy and spread the knowledge. 