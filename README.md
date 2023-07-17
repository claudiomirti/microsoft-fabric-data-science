![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/a0ca5230-c69f-446f-a59a-f50a313b0835)

Microsoft Fabric is revolutionizing the way data science is done. With its comprehensive suite of tools, users can now complete end-to-end data science workflows quickly and easily. From data exploration and preparation to experimentation, modeling, and scoring, Microsoft Fabric has you covered. Plus, it allows you to serve predictive insights to BI reports, giving you the insights you need to make informed decisions. With Microsoft Fabric, data science has never been easier.

To enable everyone to start with the notebook experience, below some Notebooks that are using random/public dta and generating a SPARK table in your Lakehouse.

Use Case description regarding the different Notebooks:
- Clinical Trials: An example for someone who is working in life science/healthcare and wants to explore clinical trails data and checking different study types and also analyzing missing values.
- ESG: Environmental, Social and Governance investing is used to screen investments based on corporate policies and to encourage companies to act responsibility. With the ESG Notebook, think about analyzing the carbon footprint of different companies and regions and getting a heatmap for the pivot table. Also, imagine you can now include in your lakehouse other sources.
- Chocolate Production: Focus is on Manufacturing and where with this Notebook, you could also include event driven data from a production location. The example shows weekly production and sales. 
- Modern Finance: This example is more in the direction of a Finance department. Ongoing revenue and predictive forecasting. Imagine you could integrate SAP data or other sources and this managing on a business level.



# Prerequisites
Prepare your system for the data science experience.

- A Microsoft Fabric subscription. Or sign up for a free Microsoft Fabric (Preview) trial.https://learn.microsoft.com/en-gb/fabric/enterprise/licenses
- Sign in to Microsoft Fabric https://fabric.microsoft.com/
- An existing Microsoft Fabric lakehouse. Create a lakehouse by following the steps in Create a lakehouse in Microsoft Fabric https://learn.microsoft.com/en-gb/fabric/data-engineering/create-lakehouse

# Import notebooks
To enable YOU to start directly with the notebook experience, I have created some Notebooks that you can execute by using random/public data and generating a SPARK table in your Lakehouse.

- Switch to the Data Science experience using the experience switcher icon at the left corner of your homepage.
![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/7ca6ac64-b4a9-464e-9d42-f447b7ac2921)

- On GitHub, Download the Notebooks
![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/0ae9fa83-7ad3-40dd-b471-e5bf8f630c34)

- On the Data science experience homepage, select Import notebook and upload the notebook files
![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/de7d0c22-9476-4a05-b1f1-7245d1aa784f)

- Once the Notebooks are imported, select Go to workspace in the import dialog box.

# Attach a lakehouse to the notebooks
To demonstrate Fabric lakehouse features, this Data Science Experience require attaching a default lakehouse to the notebooks. 
1. Open the notebook for the first part 01 Ingest data into Lakehouse using Apache Spark in the workspace.
2. Select Add lakehouse in the left pane and select Existing lakehouse to open the Data hub dialog box.
3. Select the workspace and the lakehouse you intend to use with these tutorials and select Add.
4. Once a lakehouse is added, it's visible in the lakehouse pane in the notebook UI where tables and files stored in the lakehouse can be viewed.

![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/7b2699db-9767-44fa-8cf1-5d28cbcd7dad)

You should have the following view. Of course, based on your naming / Lakehouse
![image](https://github.com/claudiomirti/microsoft-fabric-data-science/assets/38947100/090d68ab-6f04-4063-9e86-1d632b16757f)

