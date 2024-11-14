# Visualizing Data with Amazon QuickSight

<p align="center">
<img src="Screenshots/step%206.png" alt="Preview" width="500"/>
</p>

## Description
In this beginner-friendly project, I used S3 to store my CSV file for analysis and JSON file for data processing. Then, I used QuickSight to analyze the data and create a dashboard that provides a comprehensive overview of Netflix show trends.

## Tools and Services Used
- Amazon S3
- Amazon QuickSight

## Cost and Time
- Cost: $0
- Time: 45-60 minutes

## Key Procedures
1. Download necessary files (CSV, JSON)
2. Upload files into an S3 bucket
3. Create an account on QuickSight
4. Connect the dataset (in S3) to QuickSight
5. Create graphs/charts and compile in a dashboard
6. Publish and export the dashboard

## Step-by-Step Walkthrough
### Step 1: Download Files

First, I downloaded the necessary files:
- [netflix_titles.csv](Files/netflix_titles.csv) (Source: Kaggle)
- [manifest.json](Files/manifest.json) (Source: NextWork)

The JSON file used for data import had the following simple structure: </br>
<img src="Screenshots/step%201.png" alt="Step 1" width="600"/>

### Step 2: Upload Files to S3

Then, I uploaded these files to a new S3 bucket: </br>
<img src="Screenshots/step%202.png" alt="Step 2" width="600"/> </br>
Note: I used the S3 URL for my CSV file in the JSON file from Step 1 to specify the file location

### Step 3: Create QuickSight Account

Next, I navigated to QuickSight via the management console and proceeded to create an account: </br>
<img src="Screenshots/step%203.png" alt="Step 3" width="600"/> </br>
Note: I made sure to allow access to S3 and specified the S3 bucket I've created when setting up my account

### Step 4: Connect Dataset

I then connected my dataset to QuickSight by selecting "New Dataset" and providing the S3 URL of my JSON file when prompted to upload a manifest file: </br>
<img src="Screenshots/step%204.png" alt="Step 4" width="600"/> </br>

Once connected, I was able to view all the variables within my dataset in the left pane so that I can start making visualizations.

### Step 5: Create Dashboard
XXX

### Step 6: Publish & Export Dashboard
XXX

## Conclusion
