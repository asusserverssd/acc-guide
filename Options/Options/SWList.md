# Software List

The **Software List** allows you to view and manage rules of the installed software of all managed devices. You can use the Search Bar at the top of the page to search and filter through added software lists in the Software List.

To access **Software List**, click ![Options icon](../../IMG/icon-options_02.png) in the left menu, then click on **Software List** in the Definition block.

![Software List page showing the list of software lists and the Add button](../../IMG/8-13_p51-1_software-list-page.png)

## Adding a software list

1. Click on **Add**.

    ![Add button highlighted on the Software List page](../../IMG/8-13_p52-1_software-list-add.png)

2. Enter the **Name** and **Description** of the software list.

    ![Software List Information page with the Name and Description fields highlighted](../../IMG/8-13_p52-2_software-list-name.png)

3. Click on the slide button in the **Application Rule** block, then click on **Add Rule**.

    ![Slider in the Application Rule block and the Add Rule button highlighted](../../IMG/8-13_p53-1_application-rule-add.png)

4. You may add a rule from each filter field (**Display Name**, **Publisher**, **Version**). Please refer to the following on methods of adding each filter field.

    - Using Conditions (Display Name, Publisher, Version)
        1. Select a **Field**.
        2. Select the Operator (**Equal**, **Contain**, **Not Contain**), this will allow you to set the conditions for the keywords you enter.
        3. Enter keyword(s) or use the **Import** button to import keywords from a .csv file.
        4. Click on **Save** once you are finished adding keywords.

            ![Application Rule Editor with the Field, Operator, and Keyword fields, the Import button, and the Save button highlighted](../../IMG/8-13_p53-2_application-rule-editor.png)

    - Using Intelligent Select (Display Name)

        Intelligent Select will group softwares with slight differences in software name, publisher or version. For example the Microsoft Visual Studio Application Collection will include both Microsoft Visual Studio 2016 and Microsoft Visual Studio 2019.

        > **NOTE:** This option is only available for when **Display Name** is selected as the **Field**.

        1. Select **Display Name** as the **Field**.
        2. Select the Operator (**Equal**, **Contain**, **Not Contain**), this will allow you to set the conditions for the items selected in Intelligent List.
        3. Click on the slide button **Intelligent Select**, then click **Add From Intelligent List**.

            ![Application Rule Editor with Display Name selected as the Field, the Operator highlighted, and the Intelligent Select slider and Add From Intelligent List button highlighted](../../IMG/8-13_p54-1_intelligent-select.png)

        4. Check Application Collections to add them to the Intelligent List, then click on **Save**. You may also use the search bar to search for Application Collections.

            > **NOTE:** Click on ![List icon](../../IMG/icon-list_03.png) next to the Application Collection name to view all applications included in the Application Collection.

            ![Intelligent List window with several Application Collections checked and the Save button highlighted](../../IMG/8-13_p55-1_intelligent-list.png)

        5. Click on **Save** when you are finished.

            > **NOTE:** Click on **Clear** to clear all Application Collections added.

            ![Application Rule Editor listing the added Application Collections, with the Save button highlighted](../../IMG/8-13_p56-1_intelligent-list-save.png)

5. (optional) You may also edit or delete an application rule by clicking on the rule, then following step 4 to edit the rule, or click on **Delete** to delete the application rule.

    ![Application rule highlighted in the Application Rule block](../../IMG/8-13_p57-1_application-rule-select.png)

    ![Application Rule Editor opened to edit an existing rule, with the Delete button highlighted](../../IMG/8-13_p57-2_application-rule-delete.png)

6. Repeat step 3 to step 5 to add more Application Rules.

    > **NOTE:** You may only add one Application Rule per **Field** (**Display Name**, **Publisher**, **Version**).

7. Click on **Preview** to view the filter results based on the Applications Rules added.

    ![Preview button highlighted in the Application Rule block](../../IMG/8-13_p58-1_application-rule-preview-button.png)

    ![Preview selected application window listing the software that matches the Application Rules](../../IMG/8-13_p58-2_application-rule-preview.png)

    > **NOTE:** Adding License Information is optional, if you do not wish to add License Information, skip steps 8 to 17.

8. Click on the slide button in the **License Information** block.

    ![Slider in the License Information block highlighted](../../IMG/8-13_p59-1_license-info-toggle.png)

9. (optional) Click on the **Authorization Details** slide button to add authorization details to the License you are about to add.

    > **NOTE:** Toggling this option when there are already items in the **Authorized** list will clear the **Authorized** list.

    ![Authorization Details slider highlighted in the License Information block](../../IMG/8-13_p59-2_license-authorization-toggle.png)

10. Click on **Assign License**.

    ![Assign License button highlighted in the License Information block](../../IMG/8-13_p60-1_license-assign.png)

11. Enter a **Description** for the License.
12. Select the **License Type**.

    > **NOTE:**
    >
    > - **One Time Purchase**: Softwares that are a one time purchase and require no other subscription fees.
    > - **Subscription**: Softwares that require a periodic subscription fee.

    ![License Rule Editor with the Description field and the License Type options highlighted](../../IMG/8-13_p60-2_license-description-type.png)

13. Select if the License is a **Server-based Floating License**. A floating license is a licensing approach in which a limited number of licenses for the software is shared among users, and only allows a user to use the software is a license is available.
14. Set the amount of licenses available for this software.
15. Set the **Due Date** for the License if you selected **Subscription** as the **License Type**.

    > **NOTE:** This option is only available when **Subscription** is selected as the **License Type**.

    ![License Rule Editor with the Server-based Floating License, License Amount, and Due Date fields highlighted](../../IMG/8-13_p61-1_license-floating-amount-due.png)

16. Select the Authorization Details from the drop down menu.

    > **NOTE:**
    >
    > - This option is only available if **Authorization Details** was enabled.
    > - The drop down menu consists of existing metadata items. For more information on adding, editing or deleting metadata, please refer to the **Metadata Management** section.

17. Add keyword tags to the **Authorization Details** selected to help provide more information on the **Authorization Details** item selected. You may also Import multiple keywords using a .csv file by clicking on Import, selecting the .csv file you wish to import, and then selecting the field in the .csv file you would like to import.

    > **NOTE:**
    >
    > - This option is only available if **Authorization Details** was enabled.
    > - Click on **Clear** to clear all Application Collections added.

18. Click on **Save** once you are finished.

    ![License Rule Editor with the Authorization Details drop-down and keyword tags highlighted, and the Save button highlighted](../../IMG/8-13_p62-1_license-authorization-save.png)

19. (optional) You may also edit or delete a License by clicking on the License, then follow step 8 to 17 to edit the License, or click on **Delete** to delete the application rule.

    ![License highlighted in the License Information block](../../IMG/8-13_p63-1_license-select.png)

    ![License Rule Editor opened to edit an existing license, with the Delete button highlighted](../../IMG/8-13_p63-2_license-delete.png)

20. (optional) Click on the slide button in the **Process Management** block, then click **Add Rule**.

    ![Process Management slider and Add Rule button highlighted](../../IMG/8-13_p64-1_process-rule-add.png)

21. Enter the **Process Name** and **Hash Value** of the process, then click **Save**.

    > **NOTE:** To get the hash value of a process, refer to **Application Usage Analysis** under the **Software Report** section of the **Report** chapter.

    ![Process Rule Editor with the Process Name and Hash Value fields and the Save button highlighted](../../IMG/8-13_p64-2_process-rule-editor.png)

22. Click on **Add** once you have finished editing the software list.

    ![Add button highlighted on the Software List Information page](../../IMG/8-13_p65-1_software-list-finish.png)

    Your newly added software list should appear in the main Software List screen. For more information on applying the software list, please refer to the **Trust Software Asset** or **Focus Software Asset** sections.

    ![Software List page showing the newly added software list](../../IMG/8-13_p65-2_software-list-added.png)

## Editing a software list

1. Click on the software list you would like to edit from the **Software List**.

    ![Software list highlighted in the Software List](../../IMG/8-13_p66-1_software-list-edit-select.png)

2. You can edit the items in the Information, Application Rule and License Information blocks. For more information on the items in these blocks please refer to the **Adding a software list** section.

    > **NOTE:** You can see the date and time of the last time this software list was updated in the top right corner.

    ![Software List Information page with the Information, Application Rule, and License Information blocks highlighted](../../IMG/8-13_p66-2_software-list-edit-blocks.png)

3. Click on **Save** once you are finished editing the software list.

    ![Save button highlighted on the Software List Information page](../../IMG/8-13_p67-1_software-list-edit-save.png)

## Deleting a software list

1. Click on the software list you would like to delete from the **Software List**.

    ![Software list highlighted in the Software List](../../IMG/8-13_p67-2_software-list-delete-select.png)

2. Click on **Delete** to delete the software list.

    ![Delete button highlighted on the Software List Information page](../../IMG/8-13_p68-1_software-list-delete.png)
