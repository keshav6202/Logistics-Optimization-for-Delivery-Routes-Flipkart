Logistics Optimization for Delivery Routes – Flipkart
Project Overview:
Flipkart, one of India’s largest e-commerce giants, delivers millions of orders every day across
metros, Tier-2, and Tier-3 cities through its logistics arm, Ekart Logistics.
The logistics network includes regional fulfillment centers, sorting hubs, and last-mile delivery
partners across India.
As order volumes rise - especially during sales and festive seasons - delays, route
inefficiencies, and traffic disruptions can significantly affect both customer satisfaction and
operational costs.
Currently, Flipkart’s logistics team faces challenges in:
● Identifying the root causes of delivery delays (e.g., congestion, hub processing issues).
● Optimizing delivery routes for faster, more cost-efficient fulfillment.
● Improving shipment efficiency and agent performance using data-driven insights.
The logistics data, stored in relational databases - can be analyzed using SQL to extract
meaningful patterns and performance metrics. These insights can help Flipkart improve route
planning, reduce delivery delays, and enhance warehouse and agent efficiency.
Project Objective:
Build a SQL-driven Logistics analytics system to analyze delays, optimize routes, and enhance
shipment efficiency by leveraging queries, aggregations. The project aims to answer key
business questions, uncover inefficiencies, and recommend actionable improvements based on
data analysis.
(If you're unfamiliar with any concepts or domain-specific terms, feel free to take the help
of Google or AI tools like ChatGPT or Gemini to understand them better and apply them
effectively in your project.)
Dataset Description
The dataset will include the following key tables:
(Please download the hyperlinked datasets)
1.Orders Table
Orders dataset contains order-level delivery details, including warehouse, route, agent, delivery
dates, status, and order value. It is used to analyze delivery performance, agent efficiency, and
order value trends across regions.
2. Routes Table
Routes dataset contains route-level transportation details, including start and end locations,
distance, travel time, and delay information. It helps analyze route efficiency, traffic impact, and
overall travel performance across different delivery routes.
3. Warehouses Table
Warehouse dataset provides warehouse-level information, including warehouse ID, name, city,
processing capacity, and average processing time. It is used to evaluate warehouse
performance, operational capacity, and efficiency across different locations.
4. Delivery Agents Table
Delivery dataset contains delivery agent performance details, including their ID, name,
assigned route, average speed (in km/h), delivery efficiency (in %), and years of experience. It
can be used to analyze agent productivity and route performance trends.
5. Shipment Tracking Table
Shipping dataset includes key details such as shipment ID, route, delivery speed, efficiency, and
agent experience. It is useful for analyzing shipping performance, optimizing routes, and
improving overall delivery operations.
Tasks to be Performed
(Please refrain from using AI to perform the tasks mentioned below, as it will only
provide generic solutions.)
Task 1: Data Cleaning & Preparation (10 Marks)
● Identify and delete duplicate Order_ID records.
● Replace null Traffic_Delay_Min with the average delay for that route.
● Convert all date columns into YYYY-MM-DD format using SQL functions.
● Ensure that no Actual_Delivery_Date is before Order_Date (flag such records).
Task 2: Delivery Delay Analysis (10 Marks)
● Calculate delivery delay (in days) for each order
● Find Top 10 delayed routes based on average delay days.
● Use window functions to rank all orders by delay within each warehouse.
Task 3: Route Optimization Insights (20 Marks)
● For each route, calculate:
○ Average delivery time (in days).
○ Average traffic delay.
○ Distance-to-time efficiency ratio: Distance_KM / Average_Travel_Time_Min.
● Identify 3 routes with the worst efficiency ratio.
● Find routes with >20% delayed shipments.
● Recommend potential routes for optimization.
Task 4: Warehouse Performance (10 Marks)
● Find the top 3 warehouses with the highest average processing time.
● Calculate total vs. delayed shipments for each warehouse.
● Use CTEs to find bottleneck warehouses where processing time > global average.
● Rank warehouses based on on-time delivery percentage.
Task 5: Delivery Agent Performance (10 Marks)
● Rank agents (per route) by on-time delivery percentage
● Find agents with on-time % < 80%.
● Compare average speed of top 5 vs bottom 5 agents using subqueries.
● Suggest training or workload balancing strategies for low performers
Task 6: Shipment Tracking Analytics (10 Marks)
● For each order, list the last checkpoint and time.
● Find the most common delay reasons (excluding None).
● Identify orders with >2 delayed checkpoints
Task 7: Advanced KPI Reporting (10 Marks)
Calculate KPIs using SQL queries:
Average Delivery Delay per Region (Start_Location).
On-Time Delivery % = (Total On-Time Deliveries / Total Deliveries) * 100.
Average Traffic Delay per Route.
Task 8: PPT Presentation (10 Marks)
PPT Submission
● Present your analysis and findings by copying all the queries and result tables from the
previous steps into a PowerPoint presentation.
● Copy and Paste SQL queries and its corresponding results for the tasks 1 to 7.
● Ensure that the tables are formatted clearly, and the queries are concise. Use charts,
graphs, or tables to make your data more digestible.
Task 9 :Video Submission (10 Marks)
Record a video explaining the project for a maximum of 5-9 mins. This should include project
understanding analysis and explanation of outcomes. Upload in drive and share the drivelink in
the ppt.(10 marks)
(The summary should be in your own words and must not be generated using AI. Please
don’t write a script and read it aloud. Also, screenshare and show the key findings. Marks
will be deducted for failing to do so.)
Note:
● Submit your PPT and SQL script after zipping those in a folder.
● Plagiarism will result in a penalty, including possible project disqualification.
● The project will be evaluated based on the quality of analysis and visualizations,
depth of insights, feasibility of recommendations, clarity of explanations, and
adherence to instructions and deliverables.
● If the student sets their own criteria, they need to clearly mention and explain it.
Marks will be given according to the specified criteria if they are acceptable.
● Remember to keep your face clearly visible in the video.
Submission Guidelines:
● Save the PPT, SQL Script in a folder and then convert it into a zipped (.zip) folder.
(Please note, the drivelink for the video created should also be added in the
Ppt itself.)
● Upload the zipped folder on your respective dashboard.
● Failure to comply with submission guidelines will result in no grading/0 marks.
How to ZIP a PDF file:
● Put all of the documents you want to compress (or just one) into a new folder.
● Right click on that folder.
● Select the “Compress to ZIP file” option and then click “Compressed (Zipped) folder.”
● A new .ZIP file will be created that contains your document(s).


In order to submit the projects please follow the following steps:
1. Click on “ Your progress View details” after logging into your dashboard.
2. Next, click on the tab for the specific child course for which you want to
download the problem statement. Then, scroll down to find the "Course Project"
section.
3. Now, click on the three dots on the right-hand side of the "Course Project" tab to
select "Download Problem Statement."
4. Please follow the guidelines (screenshot is shared below) provided in the project
to ensure correct submissions. Then, click on "Upload Project Solution" to submit
your work.
