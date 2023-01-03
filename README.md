# TestCases

Below are some Test Case Samples that I wrote while working on previous projects.

------------------------------

**Description:** Text box functionality on Elements page

**Steps to reproduce:**

1. Go to https://demoqa.com/
2. Maximize the page
3. Click on "Elements"
4. Click on "Text Box"
5. Add "Eliza Popa" into "Full Name" field
6. Add "example@gmail.com" into "Email" field
7. Click on "Submit" button

**Expected results:** The new data should be successfully saved

**Environment:** Google Chrome

------------------------------

**Description:** Check box functionality on Elements page

**Steps to reproduce:**

1. Go to https://demoqa.com/elements
2. Click on "Radio button"
3. Click on "Yes" option

**Expected results:** A new message: "You have selected Yes" should appear below the labels

**Environment:** Google Chrome

------------------------------

**Description:** Adding a new employee on Web Tables / Elements page without completing all the fields

**Steps to reproduce:**

1. Go to https://demoqa.com/elements
2. Click on "Web Tables"
3. Click on "Add" button
4. Add "Eliza" into "First Name" field
5. Add "Popa" into "Last Name" field
6. Add "example@gmail.com" into "Email" field
7. Add "32" into "Age" field
8. Click on "Submit" button

**Expected results:** All new data should be successfully saved 

**Actual results:** The blank fields have become red, as if they were mandatory, but without being mentioned by that symbol * (bug added into BugReports)

**Environment:** Safari



