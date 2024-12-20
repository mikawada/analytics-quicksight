# Visualizing Data with Amazon QuickSight

<p align="center">
<img src="Screenshots/step%206.png" alt="Preview" width="500"/>
</p>

## Description
In this beginner-friendly project, I stored files in S3 and used QuickSight to analyze data and create a dashboard that provides a comprehensive overview of Netflix show trends.
(_Guided project by NextWork_)

## Tools and Services Used
- Amazon S3
- Amazon QuickSight

## Cost and Time
- Cost: $0 (eligible for free tier)
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

Once connected, I was able to view all the variables within my dataset in the left pane: </br>
<img src="Screenshots/step%204_1.png" alt="Step 4" width="200"/> </br>

### Step 5: Create Dashboard

Step 5 is the core of this project and where users can get creative with their visualizations.

I began with something simple by dragging the **"release_year"** field into the Y-axis, and QuickSight automatically generated a horizontal bar chart: </br>
<img src="Screenshots/step%205_1.png" alt="Step 5" width="600"/> </br>

From there, I experimented with the visual, changing its type and adding other elements. I also adjusted the number format to remove commas from the years. After some modifications, I ended up with something like this: </br>
<img src="Screenshots/step%205_3.png" alt="Step 5" width="600"/> </br>

Next, I explored relationships between different variables and created a few more visuals to gain a better understanding of the data. After refining the visuals and adding some finishing touches, such as realigning and renaming titles, I ended up with a more comprehensive dashboard: </br> 
<img src="Screenshots/step%206.png" alt="Step 6" width="600"/> </br>

### Step 6: Publish & Export Dashboard

As the final step, I named the dashboard and published it. Before closing my account and exiting QuickSight, I made sure to export the dashboard as a PDF for easy access and to have a local copy.

Note: Be sure to terminate your QuickSight account and delete your S3 bucket afterwards to avoid any unexpected charges!

## Conclusion

This quick and easy project provided a great introduction to Amazon QuickSight, helping me understand its integration with other AWS products and how its interface compares to tools like Tableau and Power BI. I highly recommend this project to AWS beginners as a stepping stone before tackling more complex tasks.
