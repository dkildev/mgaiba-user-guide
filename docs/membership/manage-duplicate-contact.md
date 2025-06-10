# Managing Duplicate Contact Creation (Merging) and Ticket Move

**Version:** 1.0  
**Last Updated:** 10 June 2025

---

## Overview

When an email is sent to **legal@mgaiba.org.au**, a ticket is automatically created in **Zoho Desk**. However, this process can sometimes result in the creation of duplicate contacts in both **Zoho Desk** and **Zoho CRM**.

This duplication typically occurs when existing contacts in Zoho CRM or Zoho Desk do not have an associated email address. As a result, Zoho cannot match the incoming email to the correct existing contact and creates a new one.

---

## Purpose

This guide outlines the correct process for:

- Identifying and safely merging duplicate contacts in Zoho CRM
- Moving the associated ticket from the duplicated contact to the correct existing contact in Zoho Desk
- Removing the duplicated contact from Zoho Desk once the ticket has been moved

---

## Part 1: Merging Duplicate Contacts in Zoho CRM

<br> 1. **Search for the Contact**

   - Open Zoho CRM and search by the contact’s name.
   - If two contacts appear (typically one with an email and one without), they need to be merged.  
     ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-1.png)

<br><br> 2. **Find and Merge Duplicates**

- Open either of the contact records
- Click the three-dot menu in the top-right corner
- Select **Find and Merge Duplicates**  
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-2.png)

<br><br> 3. **Select Matching Records**

- Zoho CRM will list potential matching records under **Matching Records**
- If no matches appear, use the **Search Criteria** to find the duplicate manually  
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-3.png)

<br><br> 4. **Compare and Merge**

- **Tick both** matching contacts and click **Next**
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-4.png)

- Compare **Record 1** and **Record 2**
- Choose the correct details to retain in the merged contact
- Ensure the **email address** is included  
   ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-5.png)

- Click **Merge** and confirm by clicking **Yes, Merge Records**
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-6.png)

<br><br> 5. **Verify Merge**

- After the success message appears, search the contact name again
- Use **Advanced Search** to ensure only one contact remains
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-7.png)
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-8.png)

---

## Part 2: Moving the Ticket in Zoho Desk

<br> 1. **Identify Duplicate Contacts**

   - In Zoho Desk, search for the contact name
   - You should see two contact entries
     ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-9.png)

<br><br> 2. **Compare Creation Dates**

- Open both contact records
- Compare the **Contact Created Time** fields
- The older contact is the original; the newer one is the duplicate
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-10.png)
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-11.png)

<br><br> 3. **Reassign the Ticket**

- Open the ticket associated with the duplicated (newer) contact
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-10.png)

- Click the **Edit** button next to **Ticket Properties**
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-12.png)

- In the **Contact Name** field, search and select the older (original) contact
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-13.png)

- Confirm the **Contact Created Time** on the right-hand side is correct
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-14.png)

- Click **Save**

<br><br> 4. **Verify Ticket Move**

- Search the contact name again and open both records
- Check that the ticket has been moved to the correct contact
    - _(Note: This may take a few minutes—refresh the page if necessary.)_
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-15.png)
  ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-16.png)

---

## Part 3: Deleting the Duplicated Contact

<br> 1. **Delete the Duplicate**
   - Open the contact record for the duplicated (newer) contact
     ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-10.png)

   - Click the three-dot menu in the top-right corner and select **Delete**
     ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-17.png)

   - Confirm deletion
     ![Call-Time-Entry-Image](../assets/images/manage-duplicate-contact/mdc-18.png)


---

## Completion

You have successfully:

- Merged duplicate contacts in **Zoho CRM**
- Reassigned the ticket in **Zoho Desk**
- Removed the duplicate contact
