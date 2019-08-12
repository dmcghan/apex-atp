# Lab 400: Create and Modify APEX Application

## Introduction

In this lab, you will create a new application that will ustilize the database objects you created in the previous lab. You will create and modify an Interactive Report and create a Calendar page.

***To log issues***, click here to go to the [github oracle](https://github.com/oracle/learning-library/issues/new) repository issue submission form.

## Lab 400 Objectives

- Create Interactive Report and Form
- Set List of Values in Form
- Save Interactive Report
- Add a Calendar page

## Steps

### **STEP 1:** Create Interactive Report and Form

- Click **Create App from Script**
{Note: If you are back on SQL Scripts, and don’t see the “Create App from Script” button perform the following steps:1. Within the Results column, click “1” for the script you just ran. 2. Under View Results, click the magnifying glass. The results page shown above should now be displayed again}

  ![](images/Lab400/001.png)

- For Name, enter **Projects** and click **Appearance**. For Theme Style, select **Vita-Slate**.

  ![](images/Lab400/002.png)

- For Features, click **Check All**.

  ![](images/Lab400/003.png)

- Click **Create Application**.

  ![](images/Lab400/004.png)

- Your new application will be displayed in Page Designer. Click **Run Application**.

  ![](images/Lab400/005.png)

- Enter your credentials and review your new application.

  ![](images/Lab400/006.png)

- From the development environment, click **App Builder**, and then select **Create**.

  ![](images/Lab400/007.png)

- In the Create App Wizard, click **Load Blueprint** and for Projects, click **Load**. 

  ![](images/Lab400/008.png)

- Click **Add Page** and then click **Interactive Grid**.

  ![](images/Lab400/009.png)

- For Page Name, enter **Milestones**, for Table or View, select **HOL_MILESTONES** and click **Add Page**.

  ![](images/Lab400/010.png)

- Click and hold the mouse when hovering over the hamburger for the Milestones – Interactive Grid page. Move it up until the page is under Projects and release the mouse.

  ![](images/Lab400/011.png)

- For Milestones – Interactive Report with Form page, click **Edit** and then click **Delete**.

  ![](images/Lab400/012.png)

- Click **Create Application**. In Page Designer, click **Run Application**.

  ![](images/Lab400/013.png)

- In the runtime environment, click **Milestones**.

  ![](images/Lab400/014.png)

### **STEP 2:** Set List of Values in Form

- In the Developer Toolbar, click **Edit Page 6**.

  ![](images/Lab400/015.png)

- In Page Designer, under Milestones, click **Columns** and click **PROJECT_ID**.

  ![](images/Lab400/016.png)

- In the Property Editor, update the following and click Save and Run the App.
  -  Identification: Type – select **Select List**
  -  Heading: Heading – enter **Project**
  -  List of Values: Type – select **SQL Query**
  -  List of Values – SQL Query enter **select name d, id r from hol_projectsorder by 1**
  -  Display Extra Values – click **No**
  -  Display Null Value – click **No** 

  ![](images/Lab400/017.png)

### **STEP 3:** Save Interactive Report

- In the runtime environment, click **Actions**, select Columns
Uncheck Displayed for Id, Row Version, Created, Created By, Updated, and Updated By and click **Save**.

  ![](images/Lab400/018.png)

  ![](images/Lab400/019.png)

- In the runtime environment, click **Actions**, select **Report**, select **Save**.

  ![](images/Lab400/020.png)



**This completes the Lab!**

