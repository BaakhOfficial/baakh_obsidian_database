>Source [here](https://www.exceldemy.com/convert-unix-timestamp-to-date-in-excel/#1_Format_Cells_to_Convert_Unix_Timestamp_to_Date)


### Format Cells to Convert Unix Timestamp to Date

We can apply **different formatting** by using the **Format Cells** options in Excel to **convert** the **Unix timestamps** into the **date format.** Let’s follow the steps below to accomplish this.

#### **Step 1: Convert the Unix Timestamps into Serial Numbers**

We have a list of **Unix timestamps** in cells **B5:B9** to **convert** them to **date**.  
![Convert Unix Timestamp to Date in Excel](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-1.png)

At first, we’ll **turn** them into **serial numbers** and then apply the **date format** to **convert** them into **Excel dates**. In cell **C5**, put the following **formula** and press **Enter.  
**

**`=(B5/86400)+DATE(1970,1,1)`**   

**![Convert Unix Timestamp to Date in Excel](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-2.png)**

---

#### **Step 2: Different Ways to Open the Format Cells Options**

**1. Keyboard Shortcuts to Open Format Cells Options**

-   **Select** cell **C5**.
-   Press **Ctrl +1** or **Alt + H + FM** to open the **Format Cells window.**

**2. Context Menu to Open Format Cells Options**

-   Select cell **C5.**
-   **Right-click** the mouse and choose **the Format Cells option.**

![](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-3.png)

**3. Open Format Cells Options Using Format Tab**

**Steps:**

-   **Select** cell **C5.**
-   Go to the **Home** tab from **Excel Ribbon.**
-   **Click** the **Format option.**
-   **Choose** the **Format Cells option.**

![](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-4.png)

---

#### **Step 3: Apply Date Format to Convert Serial Number to Excel Date**

Now that we have the **Format Cells** window **opened**,

-   From the **Number tab,** click the **Date category.**
-   Then **choose** your **preferred date format** from the list. In this example, we **chose** the **first one**.

![Convert Unix Timestamp to Date in Excel](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-5.png)

-   Now **locate** the [**Fill Handle**](https://support.microsoft.com/en-us/office/display-or-hide-the-fill-handle-80918200-9ae9-4615-93c9-13d4f1496f81) at the **bottom right corner** of cell **C5** and **drag it down** to cells **C6:C9**.

![Convert Unix Timestamp to Date in Excel](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-6.png)

-   Here are the **converted Excel dates.**

![Convert Unix Timestamp to Date in Excel](https://www.exceldemy.com/wp-content/uploads/2022/03/convert-unix-timestamp-to-date-in-excel-7.png)