# How to Publish a Power BI Report and Embed It into a Website

## What Is Power BI ?

<img width="1063" height="950" alt="image" src="/powerbi-article3.jpg" />
    
    - Power BI is Microsoft's tool for turning data into visual stories.

    - No one benefits from a report that is sitting on your laptop. Publishing makes it available online so that anyone, including your lecturer and team, may view it in a browser without the requirement for Power BI Desktop. Additionally, embedding takes it a step further by dropping your interactive, live report directly into a website, much like a movie player for data

### Step 1: Create a Workspace

    - Think of a workspace as a shared folder in the cloud. It's where your published report lives so others can find it.

Here's how to set one up:

    - Go to app.powerbi.com and sign in with your Microsoft account.
  
    - On the left sidebar, click the Workspaces icon (it looks like a briefcase).
  
    - Scroll to the bottom of the panel and click + Create a workspace.
  
    - Give it a clear name — something like Electronics Sales Dashboard works perfectly.
  
    - Optionally add a short description, then click Save.

<img width="1063" height="950" alt="image" src="/powerbi-saved-workspace-article3.jpeg" />


### Step 2: Publish Your Report
    - Open your .pbix file in Power BI Desktop.
  
    - Make sure you're signed in — look for your name in the top-right corner. If it says Sign In, click it and enter your Microsoft credentials.
  
    - Go to the Home tab in the ribbon and click the yellow Publish button (far right).
  
    - A dialog box appears asking where to publish. Select the workspace you just created.
  
    - 	Click Select and wait. It usually takes under a minute. When you see 'Publishing to Power BI succeeded!' — you're done!

<img width="1063" height="950" alt="image" src="/powerbi-brower-article3.jpeg" />

Click the link in the success message to open your report in the browser and confirm everything looks okay

### Step 3: Generate the Embed Code
The embed code is a small snippet of HTML that tells a web page to load your Power BI report inside it. Here's how to get it:

    - Open your published report in app.powerbi.com.
  
    - Click File (top-left) or the Share button, then hover over Embed report.
  
    - From the submenu, select Publish to web (public).
  
    - Read the warning — this makes your report viewable by anyone with the link, which is fine for an academic assignment. Click Create embed code.
  
    - A box appears with two things: a share link (for email) and an iFrame code (for websites). Copy the iFrame code.

<img width="1063" height="950" alt="image" src="/powerbi-brower-article3.jpeg" />

### Step 4: Embed the Report on a Website
    - Open your HTML file in a code editor like VS Code.
  
    - Find the spot in the <body> where you want the report to appear.
  
    - Paste your iFrame code there. Wrap it in a <div> if you want to add a heading above it.
  
    - Save the file and open it in your browser. Your live report should load right there on the page.

<img width="1063" height="950" alt="image" src="/powerbi-brower-article3.jpeg" />
On WordPress
    - Open the page editor in WordPress.
  
    - Add a Custom HTML block.
  
    - Paste your iFrame code into the block.
  
    - Click Update or Publish — done.

Uploading Your .pbix File to GitHub

    - Go to github.com and log in (or create a free account if you don't have one).
  
    - Click the + icon (top right) → New repository. Name it something like electronics-sales-powerbi. Set it to Public and click Create repository.
  
    - Inside the repo, click Add file → Upload files. Drag your .pbix file in and click Commit changes.
  
    - Create a README.md file. Add a one-line description and paste your Power BI embed link so your instructor can view the live report directly from GitHub.
  
    - Copy the repo URL from your browser (e.g. github.com/yourname/electronics-sales-powerbi) and submit it.


