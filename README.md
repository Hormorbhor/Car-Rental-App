# Car-Rental-App
The Car Rental App is built using Power Apps, SharePoint, and Power Automate to simplify the rental process. It features an intuitive interface, a streamlined approval flow, and automated notifications. With secure SharePoint data storage, this app enhances efficiency, automates approvals, and improves customer experience for car rental businesses.

---

### Key Features
- **User-Friendly Interface**: A responsive and intuitive interface built with Power Apps that works across different devices.
- **Integrated Approval Flow**: A Power Automate workflow that ensures rental requests go through a structured approval process.
- **SharePoint Integration**: Uses SharePoint as the backend for storing rental data, such as customer details, rental history, and vehicle availability.
- **Notifications**: Automated email notifications for rental request submissions, approvals, and rejections.
- **Secure Data**: Implements data validation and security features to protect customer information.

### Technologies Used
- **Power Apps**: For building the front-end of the app, allowing users to browse available vehicles, submit rental requests, and track rental status.
- **SharePoint**: Acts as the backend to store customer, vehicle, and rental information in a secure and easily accessible manner.
- **Power Automate**: Automates the approval flow, ensuring that all rental requests are processed in a timely and efficient manner.
---

### How the Car Rental App Works

1. **User Interaction via Power Apps:**
   - The app provides a user-friendly interface where customers can browse available vehicles and input their rental preferences (e.g., rental start/end date, type of vehicle, and additional information).
   - After filling out the required fields, the customer submits the rental request.
   
2. **Data Storage via SharePoint List:**
   - Once the request is submitted, the details are saved to a SharePoint list. The list acts as the central database for managing all car rental requests.
   - The SharePoint list typically includes fields like:
     - **Customer Name**
     - **Rental Start Date**
     - **Rental End Date**
     - **Vehicle Details** (e.g., car model, registration number)
     - **Approval Status** (Pending, Approved, Rejected)
     - **Notes/Comments**
   - SharePoint serves as the backend, ensuring that all the rental information is securely stored and easily accessible for tracking.

3. **Approval Flow via Power Automate:**
   - As soon as a rental request is logged in SharePoint, a **Power Automate** flow is triggered.
   - The flow automatically sends an approval request to the rental manager (or designated approver).
   - The approver receives an email with the request details and can either **approve** or **reject** the rental request directly from their inbox or within the Power Automate interface.
   - Depending on the outcome, the SharePoint list is updated to reflect the approval status, and the customer is notified via email:
     - **Approved:** The customer receives a confirmation email with the rental details.
     - **Rejected:** The customer receives an email explaining why their request was rejected, with an option to modify and resubmit the request.

4. **Notifications and Status Updates:**
   - Power Automate ensures that all stakeholders (customers and internal staff) receive real-time updates on the status of the rental request.
   - The app also allows users to view the status of their current and past requests, making the entire process transparent and efficient.

5. **Real-Time Monitoring:**
   - The app integrates with SharePoint to allow staff to monitor vehicle availability, rental requests, and approval statuses in real time.

### Preview the App in Action

To see a demo of how the **Car Rental App** works, including the user interface, data storage, and approval flow, watch this detailed video: 

[**Watch the Car Rental App Demo**](https://drive.google.com/file/d/1VuMkLecc-SBK9mIbIX-gBSUZtA92pr3S/view?usp=drive_link)



### Customization

- **Vehicle Inventory**: Add more fields or integrate an external data source to manage the vehicle inventory more efficiently.
- **Approval Logic**: Modify the Power Automate flow to include multi-step approvals or additional validation checks.
- **Notifications**: Customize the email templates used in the notification system to include branding, detailed rental info, etc.

### Future Enhancements
- **Payment Integration**: Add a payment gateway to handle transactions directly within the app.
- **Analytics Dashboard**: Include a Power BI dashboard for tracking vehicle utilization, rental statistics, and revenue.
- **Multi-Language Support**: Enable language customization for international users.

### Contributing
Feel free to open a pull request if you'd like to contribute to the project. All contributions are welcome!
