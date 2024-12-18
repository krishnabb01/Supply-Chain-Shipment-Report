### **🌟 Hey, What’s Up, Everyone?! 🌟**  
## 🚚 Welcome to the *Ultimate Supply Chain Shipment Report* 📦  

First things first—let’s tackle the big question:  
### **✨ What is Supply Chain? ✨**  
The *supply chain* is the amazing journey that raw materials, components, and goods take from the very start to their **final destination—YOU!** 🚀 It’s the connection of every stop along the way—**from factories 🏭 to warehouses 🏢 and finally into the hands of customers 👋.**  

## **The Supply Chain Shipment Report: Smooth Deliveries Made Simple 🚛✨**  

This report is your **secret weapon 🛠️** to understanding how products move from **Point A to Point B** and everything in between. It’s like a **report card 🎓** for suppliers, tracking their performance to make sure they:  
✅ Deliver **on time ⏰**  
✅ Ship products in **perfect condition 🏆**  
✅ Stick to **contract agreements 📜**  

Why does this matter? It helps you find the **best suppliers 🔍** for future orders and strike deals that work **in your favor 💼💰.**  

---

**Ready to dive in? Let’s get this journey started! 🚚✨**  
### **📊 Supply Chain Shipment Data Overview 🚚✨**  

Welcome to the heart of the analysis report—here’s everything you need to know about the dataset and its columns. This will help you understand the data better and see how each piece fits into the **supply chain journey**.  

---

#### **🔍 Dataset Explanation:**  
This dataset provides detailed information about **shipment orders**, including delivery performance, costs, product details, and supplier information. It’s your **roadmap 🗺️** to analyze how shipments are managed and where improvements can be made.  

---

### **📋 Column Descriptions (Simplified)**  

1. **`ID`**: Unique identification number for each shipment record.  
   - *Think of it like a shipment tracking number!* 📦  

2. **`Project Code`**: Code representing the project under which the shipment was ordered.  
   - Helps categorize the shipment into specific projects.  

3. **`PQ #`**: Pre-qualification reference number.  
   - Indicates that the product or supplier has been pre-approved.  

4. **`PO / SO #`**: Purchase Order (PO) or Sales Order (SO) number.  
   - A unique number for each order placed with a supplier. 📝  

5. **`ASN/DN #`**: Advance Shipment Notice (ASN) or Delivery Note (DN) number.  
   - This is the notice sent ahead of the delivery, confirming what’s being shipped.  

6. **`Country`**: The destination country for the shipment.  
   - *Where the product is being delivered! 🌍*  

7. **`Managed By`**: The team or group managing the shipment.  
   - Example: PMO - US. It tells you who’s overseeing the order.  

8. **`Fulfill Via`**: The method by which the shipment is fulfilled (e.g., Direct Drop).  
   - Explains how the product moves to the customer.  

9. **`Vendor INCO Term`**: International shipping terms (e.g., EXW, CIP).  
   - Defines who is responsible for shipping costs and risks.  

10. **`Shipment Mode`**: How the shipment was transported (e.g., Air ✈️, Sea 🚢).  
    - *The route your product takes to arrive!*  

11. **`Scheduled Delivery Date`**: The planned delivery date for the shipment.  
    - *When the shipment is expected to arrive.* 📅  

12. **`Delivered to Client Date`**: The actual date the shipment was delivered to the client.  
    - *When the customer received the order.*  

13. **`Delivery Recorded Date`**: The date when the delivery was officially recorded.  

14. **`Product Group`**: Broad category of the product (e.g., ARV, HRDT).  
    - This groups products into types.  

15. **`Sub Classification`**: A more detailed classification within the product group.  
    - Example: Pediatric or Adult products.  

16. **`Vendor`**: The name of the supplier/vendor providing the product.  
    - *Who shipped the goods?*  

17. **`Item Description`**: Detailed description of the product/item.  
    - Example: HIV Test Kit, Capsules, Tablets.  

18. **`Molecule/Test Type`**: The chemical composition or type of medical test involved.  
    - Example: Tenofovir, HIV Genie II.  

19. **`Brand`**: The product’s brand name.  
    - Example: Viread, Genie, Videx.  

20. **`Dosage Form`**: The form of the product (e.g., Tablet 💊, Capsule, Test Kit).  

21. **`Unit of Measure (Per Pack)`**: Number of items in one pack (e.g., 40 tests, 60 capsules).  

22. **`Line Item Quantity`**: The total quantity of items ordered.  
    - *How many units were shipped?*  

23. **`Line Item Value`**: The total cost/value of that line item.  
    - *How much the shipment cost in total.* 💰  

24. **`Pack Price`**: The price per pack of the product.  

25. **`Unit Price`**: Price of a single unit in the pack.  
    - *What does one tablet, capsule, or test cost?*  

26. **`Manufacturing Site`**: The location/site where the product was manufactured. 🏭  

27. **`First Line Designation`**: Indicates if the product is a **first-line treatment option**.  

28. **`Weight (Kilograms)`**: Total weight of the shipment in kilograms. ⚖️  

29. **`Freight Cost (USD)`**: The cost of transporting the shipment. 🚚💵  

30. **`Line Item Insurance (USD)`**: The insurance cost for that specific shipment line. 🛡️  

---

With this dataset, you now have a clear picture of all the moving parts involved in the supply chain shipment process! Let’s get ready to analyze and uncover some amazing insights 🚀📦✨.

*** 
![image](https://github.com/user-attachments/assets/1e02f9db-cf19-4d9f-ba28-c365f9ce57aa)
***

**"Best way of solving a problem is 'Divide and conquer.' That's exactly what I'm doing with this project – no need to freak out, I've got it all under control! 😄"**

### Overall Metrics:

📦 Sum of Weight (Kilograms): 36M

💰 Sum of Line Item Value: 1.57bn

🗓️ Earliest Delivery Date: 19 June 2007

🌍 Count of Countries: 43

📦 Sum of Line Item Quantity: 184M

🗓️ Latest Delivery Date: 14 September 2015

💵 Sum of Freight Cost (USD): 103.3M

🏷️ Count of Brands: 46

🏭 Count of Manufacturing Sites: 83

📦 Count of Vendors: 69

---

### Vendor Performance:
***
![image](https://github.com/user-attachments/assets/40f7e6db-bc31-4a80-bb8d-2fcd9b8e2ba1)
***

#### 🏅 Key Metrics:
**On-time Delivery Rate:** Evaluate how often vendors deliver on schedule. Timely deliveries are crucial for maintaining supply chain efficiency.

**Product Quality:** Ensure products meet quality standards upon arrival. High-quality products reduce returns and enhance customer satisfaction.

**Cost Efficiency:** Assess the cost-effectiveness of vendors. Lower costs with high-quality products are ideal.

#### Analysis Focus:
**🥇 Top Performers:** Find the vendors with the best performance in terms of on-time delivery, quality, and cost.

**🚀 Improvement Areas:** Identify vendors who need to improve. This can help in providing targeted feedback.

**🤝 Contracts:** Ensure vendors adhere to contract terms. This ensures that deals are honored and both parties benefit.

### Quality Control:
***
![image](https://github.com/user-attachments/assets/1cea41ea-eb35-4a35-80a3-9245ee4003e3)
***

#### 🔍 Key Metrics:
**Product Condition:** Check the condition of products upon delivery. Well-maintained products indicate good handling.

**Quality Standards:** Verify if products comply with established quality standards. Consistency in quality is key.

**Defect Frequency:** Track how often defects occur. Lower defect rates mean higher reliability.

#### Analysis Focus:
**❌ Defect Rates:** Identify vendors or products with high defect rates to address issues promptly.

**🛠️ Quality Improvements:** Suggest measures to enhance product quality. Continuous improvement is essential.

**📜 Compliance:** Ensure all products meet regulatory and quality standards. Compliance is non-negotiable.

### Cost Analysis:
***
![image](https://github.com/user-attachments/assets/49c14897-cbf2-4b66-8ed4-33ed699cdf0c)
***
#### 💵 Key Metrics:
**Total Shipment Costs:** Calculate the overall cost of shipments. Keeping costs in check helps maintain profitability.

**Freight Costs Breakdown:** Analyze the different components of freight costs. This helps identify areas for cost reduction.

**Insurance Costs:** Track insurance expenses to ensure they are reasonable. Insurance is crucial for mitigating risks.

#### Analysis Focus:
**🏷️ Cost Efficiency:** Compare costs across various vendors and shipment methods to find the most cost-effective solutions.

**💡 Savings Opportunities:** Identify ways to reduce costs without compromising quality. Every saved penny counts.

**📊 Budget Allocation:** See where the money is being spent and ensure it aligns with priorities.

### Product Distribution:
***
![image](https://github.com/user-attachments/assets/9d8022d4-4d79-4670-b949-cd5fe174b640)
***

#### 🌍 Key Metrics:
**Geographical Spread:** Map out where shipments are going. Knowing this helps in understanding market reach.

**Distribution Efficiency:** Check how effectively products are being distributed. Efficient distribution minimizes delays.

**Customer Reach:** Ensure that products are reaching the intended customers on time. Happy customers mean repeat business.

#### Analysis Focus:
**🏘️ Top Regions:** Identify regions with the highest shipment volumes. This helps focus on key markets.

**🚚 Delivery Routes:** Analyze the efficiency of delivery routes. Optimizing routes can save time and money.

**😊 Customer Satisfaction:** Ensure timely and accurate delivery to keep customers happy and loyal.

### Delivery Methods:
***
![image](https://github.com/user-attachments/assets/8703e46c-957d-46d8-8b78-097982447e55)
***

#### 🚚 Key Metrics:
**Shipment Modes:** Compare different shipment methods like Air, Truck, Ocean, and Air Charter.

**Fulfillment Methods:** Examine "From RDC" and "Direct Drop" methods.

#### Analysis Focus:
**🛤️ Shipment Efficiency:** Determine the most efficient shipment modes for different scenarios. This can help reduce delivery times.

**📉 Cost vs. Speed:** Balance the cost and speed of different delivery methods. Faster deliveries can be more expensive.

**📦 Method Performance:** Compare the performance of "From RDC" versus "Direct Drop" to identify the best approach for different types of products.

## Vendor Performance Dashboard 🚚
***
![image](https://github.com/user-attachments/assets/91750c83-f3e3-40ce-897b-82219df3c01e)
***

### Key Performance Indicators (KPIs):
**📦 Vendor Count: 69**

**🌍 Country Count: 43**

### Charts and Visuals:
***
**1. Sum of Line Item Value and Sum of Line Item Quantity by Vendor:**

![image](https://github.com/user-attachments/assets/d46f70bd-af7b-4f94-a6d1-3810c02e0b7e)

***What's This?*** *A bar chart showing how much value and quantity each vendor brings.*

***- Why It Matters:*** Spot your top vendors who contribute the most. 🥇

***- Suggestions:***

**-- Focus on High-Value Vendors:** Prioritize vendors that bring the most value and quantity. They're your key players!

**-- Negotiate Better Terms:** For high-value, low-quantity vendors, consider negotiating for better terms to balance cost and volume. 💼
***
**2. Count of Vendor by Shipment Mode:**

![image](https://github.com/user-attachments/assets/cf03aa23-a43e-4781-885c-479fc3c23264)

***What's This?*** *A pie chart displaying how many vendors use each shipment mode (Air, Truck, Air Charter, Ocean).*

***- Why It Matters:*** Understand which shipment methods are popular. 🚛✈️

***- Suggestions:***

**-- Optimize Shipment Modes:** If most vendors use a specific mode, explore bulk deals or discounts with logistics providers.

**-- Diversify Shipment Options:** Encourage multiple shipment modes to reduce risks and ensure timely deliveries. 📦
***
**3. Country and Vendor Map:**

![image](https://github.com/user-attachments/assets/32654a59-cd65-4796-8479-9d22208cbbdb)

***What's This?*** *A colorful map showing where your vendors are located around the world.*

***- Why It Matters:*** See the global reach of your supply chain. 🌍

***- Suggestions:***

**-- Expand Regional Coverage:** Identify regions with fewer vendors and explore new opportunities.

**-- Assess Regional Performance:** Focus on high-density regions to ensure optimized performance. 📈
***
**4. Count of Country by Vendor:**

![image](https://github.com/user-attachments/assets/46083cbf-8871-44c8-97e6-702e99296f23)

***What's This?*** *A treemap showing the number of countries each vendor operates in.*

***- Why It Matters:*** Identify vendors with the widest geographical spread. 🗺️

***- Suggestions:***

**-- Leverage Key Vendors:** Work closely with vendors that have broad geographical reach.

**-- Reduce Dependency:** Diversify your vendor base to avoid over-relying on a few key players. 🔑
***
**5. Vendor, Brand, and Molecule/Test Type Sankey Diagram:**

![image](https://github.com/user-attachments/assets/9fa4f264-6e91-4f40-8bd6-b0d0b953d07b)

***What's This?*** *A flow diagram showing connections between vendors, brands, and test types, along with costs.*

***- Why It Matters:*** Understand how goods flow from vendors to products. 🔄

***- Suggestions:***

**-- Strengthen Key Relationships:** Focus on crucial vendors for high-demand brands and test types.

**-- Optimize Freight Costs:** Look for ways to reduce freight costs by optimizing shipping methods and routes. 🚀
***
### Detailed Suggestions:

1. **Focus on High-Value Vendors:** Prioritize and strengthen partnerships with key vendors. 🌟

2. **Optimize Shipment Modes:** Look for cost-effective shipment options and encourage diverse methods. 🚛

3. **Expand Regional Coverage:** Increase presence in underrepresented areas to enhance supply chain resilience. 🌍

4. **Leverage Key Vendors:** Utilize vendors with a wide geographical reach to streamline operations. 🏆

5. **Strengthen Key Relationships:** Enhance collaborations with crucial vendors for important brands and test types. 🤝

6. **Optimize Freight Costs:** Implement strategies to cut down on freight expenses while maintaining efficiency. 💰

## Quality Control Dashboard 🔍
***
![image](https://github.com/user-attachments/assets/f41533de-65f2-45b7-95be-cabdcb5fa5fe)
***

#### **Key Metrics:**
- **Sum of Weight (Kilograms):** 36M
- **Count of Brand:** 46
- **Count of Shipment Modes:** 4
- **Count of Dosage Forms:** 17

### **Charts and Visuals:**

1. **Sum of Weight (Kilograms) by Fulfill Via:**
![image](https://github.com/user-attachments/assets/d856a00a-9ffc-45dc-9547-d7e7c2187329)

   - **What's This?** A bar chart showing the total weight of shipments categorized by fulfillment methods: "From RDC" and "Direct Drop".
   - **Why It Matters:** Helps understand which fulfillment method handles the most weight. 📦
   - **Suggestions:**
     - **Evaluate Efficiency:** Compare the efficiency of "From RDC" vs. "Direct Drop" to decide which method works best for different scenarios.
     - **Optimize Methods:** Consider improvements to the method that handles less weight to balance the load. ⚖️

3. **Sum of Freight Cost (USD), Sum of Line Item Quantity and Sum of Weight (Kilograms) by Shipment Mode:**

   ![image](https://github.com/user-attachments/assets/0cd567e4-46d2-4c4c-bf18-6be0d9a2024b)
   
   - **What's This?** A bar chart comparing different shipment modes (Air, Truck, Air Charter, Ocean) based on freight cost, item quantity, and weight.
   - **Why It Matters:** Provides insight into cost efficiency and volume distribution across shipment modes. 🚛✈️
   - **Suggestions:**
     - **Cost vs. Volume:** Analyze the cost-effectiveness of each shipment mode and adjust strategies to use the most efficient mode for different types of shipments.
     - **Balance Shipments:** Ensure that high-cost modes like Air are used judiciously for urgent shipments, while others can go by more cost-effective means. 💡

4. **Sankey Diagram:**

   ![image](https://github.com/user-attachments/assets/ee873ce6-a154-4444-a63d-a7400227386a)
   
   - **What's This?** A diagram showing the distribution of shipment weights across different modes, brands, and dosage forms.
   - **Why It Matters:** Highlights the flow and relationship between various factors in the supply chain. 🔄
   - **Suggestions:**
     - **Identify Key Flows:** Focus on the heaviest and most costly flows to find areas for optimization.
     - **Streamline Processes:** Work on streamlining the process for the most frequently shipped brands and dosage forms. 🚀

5. **World Map:**
   
   ![image](https://github.com/user-attachments/assets/c06da60f-ee3d-4e90-9ce3-f0f6f204621a)
   
   - **What's This?** A map highlighting shipment regions in North America, South America, Europe, Africa, Asia, and Australia.
   - **Why It Matters:** Shows global distribution and regional performance. 🌍
   - **Suggestions:**
     - **Regional Analysis:** Identify regions with the most shipments to focus on improving logistics in those areas.
     - **Expand Reach:** Look for opportunities to expand into regions with lower shipment volumes. 📈

### **Detailed Suggestions:**

1. **Evaluate Efficiency:** Compare and enhance fulfillment methods to balance workload. ⚖️
2. **Cost vs. Volume:** Use the most efficient shipment modes to save costs and maximize volume. 🚛
3. **Identify Key Flows:** Focus on the heaviest and costliest shipment flows for optimization. 📦
4. **Regional Analysis:** Improve logistics in regions with high shipment volumes and explore new areas for expansion. 🌍

***
### **Quality Control Dashboard** 🔍

![image](https://github.com/user-attachments/assets/7d50ebde-9552-450b-9bec-65b531be5ed4)

#### **Key Metrics:**
- **Sum of Weight (Kilograms):** 36M
- **Count of Brands:** 46
- **Count of Shipment Modes:** 4
- **Count of Dosage Forms:** 17

### **Charts and Visuals:**

1. **Sum of Weight (Kilograms) by Fulfill Via:**
   - **What's This?** A bar chart showing the total weight of shipments categorized by fulfillment methods: "From RDC" and "Direct Drop."
   - **Why It Matters:** Helps understand which fulfillment method handles the most weight. 📦
   - **Suggestions:**
     - **Evaluate Efficiency:** Compare the efficiency of "From RDC" vs. "Direct Drop" to decide which method works best for different scenarios.
     - **Optimize Methods:** Consider improvements to the method that handles less weight to balance the load. ⚖️

2. **Sum of Freight Cost (USD), Sum of Line Item Quantity and Sum of Weight (Kilograms) by Shipment Mode:**
   - **What's This?** A bar chart comparing different shipment modes (Air, Truck, Air Charter, Ocean) based on freight cost, item quantity, and weight.
   - **Why It Matters:** Provides insight into cost efficiency and volume distribution across shipment modes. 🚛✈️
   - **Suggestions:**
     - **Cost vs. Volume:** Analyze the cost-effectiveness of each shipment mode and adjust strategies to use the most efficient mode for different types of shipments.
     - **Balance Shipments:** Ensure that high-cost modes like Air are used judiciously for urgent shipments, while others can go by more cost-effective means. 💡

3. **Sankey Diagram:**
   - **What's This?** A diagram showing the distribution of shipment weights across different modes, brands, and dosage forms.
   - **Why It Matters:** Highlights the flow and relationship between various factors in the supply chain. 🔄
   - **Suggestions:**
     - **Identify Key Flows:** Focus on the heaviest and most costly flows to find areas for optimization.
     - **Streamline Processes:** Work on streamlining the process for the most frequently shipped brands and dosage forms. 🚀

4. **World Map:**
   - **What's This?** A map highlighting shipment regions in North America, South America, Europe, Africa, Asia, and Australia.
   - **Why It Matters:** Shows global distribution and regional performance. 🌍
   - **Suggestions:**
     - **Regional Analysis:** Identify regions with the most shipments to focus on improving logistics in those areas.
     - **Expand Reach:** Look for opportunities to expand into regions with lower shipment volumes. 📈

### **Detailed Suggestions:**

1. **Evaluate Efficiency:** Compare and enhance fulfillment methods to balance workload. ⚖️
2. **Cost vs. Volume:** Use the most efficient shipment modes to save costs and maximize volume. 🚛
3. **Identify Key Flows:** Focus on the heaviest and costliest shipment flows for optimization. 📦
4. **Regional Analysis:** Improve logistics in regions with high shipment volumes and explore new areas for expansion. 🌍
