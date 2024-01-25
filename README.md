# trueArt
# Create a Custom Object
In this step, you create a custom object called Book with one custom field called Price.
## Prerequisites
A Salesforce account in a sandbox Professional, Enterprise, Performance, or Unlimited Edition org, or an account in a Developer org.

For more information about creating a sandbox org, see “Sandbox Types and Templates” in the Salesforce Help. To sign up for a free Developer org, see the Developer Edition Environment Sign Up Page.

## Steps

1. Log in to your sandbox or Developer org.
2. From your management settings for custom objects, if you’re using Salesforce Classic, click **New Custom Object**, or if you’re using Lightning Experience, select **Create | Custom Object**.
3. Enter Book for the label.
4. Enter Books for the plural label.
5. Click **Save**.
   
Ta dah! You’ve now created your first custom object. Now let’s create a custom field.

1. In the Custom Fields & Relationships section of the Book detail page, click **New**.
2. Select Number for the data type and click *Next*.
3. Enter Price for the field label.
4. Enter 16 in the length text box.
5. Enter 2 in the decimal places text box, and click *Next*.
6. Click Next to accept the default values for field-level security.
7. Click *Save*.

   
You’ve just created a custom object called Book, and added a custom field to that custom object. Custom objects already have some standard fields, like Name and CreatedBy, and allow you to add other fields that are more specific to your implementation. For this tutorial, the Price field is part of our Book object and it is accessed by the Apex class you will write in the next step.
