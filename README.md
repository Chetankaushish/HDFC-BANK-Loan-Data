🔹 Step 1: Get the Data

You probably had an Excel or CSV file with loan details (customer age, income, EMI, loan amount, credit score, etc.).

In Power BI, you clicked on “Get Data” > Excel workbook.

Selected your file and loaded it into Power BI.

🔹 Step 2: Clean or Check the Data

You may have quickly gone into Transform Data (Power Query Editor) to:

Make sure column types were correct (numbers as numbers, text as text).

Maybe renamed some columns for clarity (like Credit_Score, Amount_invested_monthly, etc.).

🔹 Step 3: Add the Key Metrics (Top Cards)

Those big numbers at the top (5.51M, 142.62M, 419.73M)? You used Card visuals for those.

Selected the Card visual from the right panel.

Dragged in fields like Amount_invested_monthly, Outstanding_Debt, and Monthly_Inhand_Salary.

Power BI automatically shows the sum by default.

🔹 Step 4: Add a Gauge Chart (Top Left)

This shows the sum of age or credit score as a visual meter (showing progress towards a goal).

Clicked on the Gauge chart visual.

Dragged in the Age or Credit_Score field.

Set the min as 0M and max as 7M manually or using a formula.

This is more for visual appeal — it tells you the average/total is somewhere around 3M.

🔹 Step 5: Bar Chart – Credit Cards, Loans, Bank Accounts

This is the grouped bar chart showing total number of credit cards, loans, and bank accounts.

Clicked on Clustered Column Chart.

Dragged in:

Num_Credit_Card

Num_of_Loan

Num_Bank_Accounts

This shows how many of each are in the data — like how many total credit cards people have.

🔹 Step 6: Pie Chart – EMI by Month

Here you wanted to show how EMIs vary month by month.

Selected the Pie Chart visual.

Dragged Month to Legend and Total_EMI_per_month to Values.

Now you get a nice pie showing which month had the highest EMIs.

🔹 Step 7: Bar Chart – Annual Income by Occupation

This shows who earns how much, depending on their job.

Selected Bar Chart.

Dragged Occupation to Axis, and Annual_Income to Values.

It now shows a side-by-side comparison of income by job title.

🔹 Step 8: Waterfall Chart – SSN by Month

This chart shows how SSN numbers (likely representing customer counts or cases) increase or decrease month to month.

Selected Waterfall Chart.

Dragged Month to Axis, and SSN to Values.

It automatically shows increases in blue and decreases in red.

🎨 Design & Customization

You gave it a nice professional look:

Chose a dark purple background for the entire canvas.

Used red, blue, and white to match HDFC Bank’s theme.

Added borders, titles, and consistent font sizes to make it easy to read.

Used the “Format” options in each visual to add data labels, adjust colors, and fine-tune everything.

📊 What this dashboard tells us:

How much money is being invested and earned monthly.

Total outstanding debts.

Monthly EMI trends.

Which professions are earning more.

How many loans, cards, and accounts people hold.

How things are changing month by month.

✅ Final Thoughts

This dashboard was built using simple drag-and-drop in Power BI. The magic lies in:

Picking the right visuals for the data.

Keeping it clean and well-organized.

Using colors and formatting for clarity.
