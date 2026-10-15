# Accounts Management

**Accounts Management** displays all user accounts on ASUS Control Center, and allows you to add, edit, or delete accounts. ASUS Control Center comes with a default Administrator account with Admin role privileges, and a User account with Viewer role privileges.

To access **Accounts Management**, you can use the following methods:

- Click ![Account menu icon](../../IMG/icon-account_01.png) in the left menu, then click on **Accounts Management**.
- Click ![Account Information icon](../../IMG/icon-account-info_01.png) (**Account Information**) in the top right corner, then select **Settings**.

![Accounts Management page showing the Account Management list with the default Administrator and User accounts and the Add button](../../IMG/7-2_p10-1_accounts-page.png)

## Adding a new account

You can add new accounts and apply customized roles to them, allowing you to and control the functions and information each account can access with ease. For example, assigning an account with Software User role which is customized to only allow users with this role access to ASUS Control Center software related functions, or creating an account with BIOS User role which is customized to only allow users access to ASUS Control Center BIOS related functions.

> **NOTE:** For more details on role privileges, please refer to the **Role Privilege Management** section.

1. Click on **Add**.

    ![Add button highlighted in the Account Management list](../../IMG/7-2_p11-1_account-add-button.png)

2. Enter the username, password, and email of the new account.
3. Select a role in the **Role Name** field.

    > **NOTE:** For more details on adding new roles, please refer to **Add Role** under the **Role Privilege Management** section.

4. Enter a brief description for the account.
5. (optional) Check or uncheck **Enable the account** in the **Active** field to enable or disable the newly created account.
6. Click on **Save** once you have finished.

    ![Add New Account pop-up with the username, password, email, role name, description, and Active fields highlighted, and the Save button highlighted](../../IMG/7-2_p12-1_account-add-dialog.png)

7. Your newly created account should appear in the **Account Management** list.

    ![Newly created account highlighted in the Account Management list](../../IMG/7-2_p13-1_account-added.png)

    Logging in to ASUS Control Center using different accounts with different roles assigned will affect the items the account can gain access to, depending on the permissions assigned to the role selected. For example, logging in an account which you have set to a role with access only to Software related functions will result in the following screenshot.

    ![ASUS Control Center Device Information page as seen by an account whose role only allows software related functions](../../IMG/7-2_p13-2_account-limited-view.png)

## Editing an account

1. Click on the account you wish to edit.

    ![Account highlighted in the Account Management list](../../IMG/7-2_p14-1_account-edit-select.png)

2. You can edit the **Password**, **Email**, **Role Name**, **Description**, and **Active** fields. Once you have finished editing click on **Save** to save the changes made.

    ![Edit Account pop-up with the password, email, role name, description, and Active fields highlighted, and the Save button highlighted](../../IMG/7-2_p14-2_account-edit-dialog.png)

## Deleting an account

> **NOTE:** The default **Administrator** and **User** accounts cannot be deleted.

1. Click on the account you wish to delete.

    ![Account highlighted in the Account Management list](../../IMG/7-2_p15-1_account-delete-select.png)

2. Click on **Delete**, then click on **Delete** again on the confirmation pop-up to delete the account.

    ![Delete Account confirmation pop-up with the Delete button, shown above the Edit Account pop-up with its Delete button highlighted](../../IMG/7-2_p15-2_account-delete-confirm.png)

## Enabling multi-factor authentication (MFA)

> **NOTE:** It is only possible to enable or disable MFA for currently logged in account.

1. Click on the currently logged in account.

    ![Currently logged in account highlighted in the Account Management list, which now includes an MFA column](../../IMG/7-2_p16-1_mfa-enable-select.png)

2. Enable the **MFA** option, then scan the QR code using an authenticator app and enter the 6-digit passcode to verify the multi-factor authentication setup.

    ![Edit Account pop-up with the MFA option enabled, showing a QR code and a field for the 6-digit passcode](../../IMG/7-2_p16-2_mfa-enable-qr.png)

3. Once MFA is enabled, the MFA field will show when MFA was enabled for this account. Click **Save**.

    ![Edit Account pop-up with the MFA field showing the date and time MFA was enabled, and the Save button highlighted](../../IMG/7-2_p16-3_mfa-enabled-save.png)

4. Click on the currently logged in account again.

    ![Currently logged in account highlighted in the Account Management list](../../IMG/7-2_p17-1_mfa-reselect-account.png)

5. Enter the 6-digit passcode from the authenticator app, then click **Verify**.

    ![MFA pop-up on the login page asking for the 6-digit passcode from the authenticator app, with the Verify button](../../IMG/7-2_p17-2_mfa-verify.png)

## Disabling multi-factor authentication (MFA)

> **NOTE:**
>
> - It is only possible to enable or disable MFA for the currently logged in account.
> - Only the default Administrator account can view the MFA status of other accounts.

1. Click on the currently logged in account.

    ![Currently logged in account highlighted in the Account Management list](../../IMG/7-2_p18-1_mfa-disable-select.png)

2. Disable the **MFA** option.

    ![Edit Account pop-up with the MFA option highlighted and turned off](../../IMG/7-2_p18-2_mfa-disable.png)
