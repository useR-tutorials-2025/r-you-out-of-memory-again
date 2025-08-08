# R Project Setup - Pre-Workshop Instructions

## Welcome to the R You out of Memory Short Course!

We are so glad you will be joining us!

> **Before the workshop, please complete these setup steps.** This will ensure we can dive straight into working with big data during our session. This is the first part. Read the entire thing. You will need to grab another document and add it to the project folder.

✅ Complete setup first (this document)

✅ There's a second document coming (the Quarto workshop file)

✅ The second document goes into the project they're creating

So your workflow will be:

1.  **Pre-workshop START HERE file:** Students follow the `.md` setup guide → create a project folder.

2.  **Pre-workshop Data Download file:** You are provided the data download `.qmd` file → add it to their existing project folder.

3.  **Workshop begins:** Everyone has identical setup and can immediately start the actual big data work.

4.  **Additional Workshop:** You can get the rest of the Modules at the workshop directly from the github repository.

## What You'll Accomplish

By the end of this setup, you'll have:

✅ A properly organized R Project

✅ A 9GB real-world dataset downloaded and ready

✅ All necessary packages installed

✅ A workspace ready for big data analysis

## Time Requirements

-   **Setup time:** 5-10 minutes

-   **Download time:** 8-15 minutes (depends on your internet speed)

-   **Total time:** \~20 minutes

## Pre-Workshop PART 1 (Project Folder Set-up):

### Step 1: Create Your R Project

### Inside Using RStudio

1.  Open RStudio

2.  Click **File** → **New Project**

3.  Choose **New Directory**

4.  Select **New Project**

5.  **Project directory name:** `useR2026_bigdata_shortcourse`

6.  Choose where to save it on your computer (somewhere you can easily find it!)

7.  Click **Create Project**

### Step 2: Verify Your Project Setup

Once your project is created, verify you're in the right place:

Open up a script file or QUarto file and run the following code

```{r}
# Check your current working directory
getwd() 

# List files in your project (should be empty for now) 
list.files()
```

## Pre-Workshop PART 2 (.qmd file):

You should have received a second file called **"Pre-workshop Data Download.qmd"** in the same email. Here's how to add it to your project:

### Step 3: Move the Quarto File to Your Project

**Option A: Save directly to project folder**

1.  Download the **"Pre-workshop Data Download.qmd"** file

2.  When saving, navigate to your `useR2026_bigdata_shortcourse` folder

3.  Save it there

**Option B: Move an already downloaded file**

1.  Locate the **"Pre-workshop Data Download.qmd"** file on your computer

2.  **Windows:** Cut and paste the file into your `useR2026_bigdata_shortcourse` folder

3.  **Mac:** Drag the file into your project folder using Finder

4.  **Linux:** Move the file using your file manager

### Step 4: Verify the File is in the Right Place

Open your R Project (double-click the `.Rproj` file) and run:

```{r}

# Check that your .qmd file is now in your project folder 
list.files() 
# Should show: "Pre-workshop Data Download.qmd" and "useR2026_bigdata_shortcourse.Rproj"
```

### Step 5: Open and Run the Data Download File

1.  In RStudio, open **"Pre-workshop Data Download.qmd"**

2.  Follow the instructions in that file to download the dataset

3.  **Important:** Make sure you're working in your project when you run the download!

## Final Check

After completing both parts, your project folder should contain:

```         
useR2026_bigdata_shortcourse/ 
├── useR2026_bigdata_shortcourse.Rproj 
├── Pre-workshop Data Download.qmd 
├── data/ 
│   └── seattle-library-checkouts.csv (9GB) 
└── (any other files you create)
```

Verify this with:

```{r}
# Check your complete project structure 
list.files(recursive = TRUE)
```

## Troubleshooting

**Can't find your project folder?**

-   Look for the folder named `useR2026_bigdata_shortcourse`

-   Use **File** → **Open Project** in RStudio to navigate to your `.Rproj` file

**Quarto file in wrong location?**

-   Make sure you're saving/moving it to the same folder as your `.Rproj` file

-   You will need to open and close the project within R to refresh the file listing

    -   Use **\*\*File\*\*** → **\*\*Close Project\*\***, then double-click your \`.Rproj\` file to reopen

**Questions?** Feel free to reach out to the instructors before the workshop!
