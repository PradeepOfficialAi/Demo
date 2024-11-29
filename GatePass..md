
### **1. Purpose of the System**
The system will:
- Allow employees to register visitors, vehicles, and materials in advance.
- Streamline check-in and check-out processes.
- Ensure safety by requiring health and safety approvals.
- Provide reports and analytics to monitor access activity.

---

### **2. Core Features**
#### a. **Visitor Management**
- **Registration**: Employees should be able to request access for visitors. The employee provides information like:
  - Visitor name, contact info, and purpose of visit.
  - Date and time of visit.
  - Location and host details.
- **Automated Processes**:
  - After registration, the system will:
    1. Notify the host about the visitor.
    2. Allow the visitor to upload documents and fill out forms online.
    3. Generate a QR code for the visitor to use for check-in.
- **Health and Safety Checks**:
  - Visitors must complete a medical questionnaire and safety induction.
  - Health and safety staff will review and approve the visitor's entry based on the responses.

#### b. **Check-in and Check-out**
- Security guards will scan the visitor's QR code at the gate to check them in.
- The system will notify the host when the visitor arrives and leaves.

#### c. **Vehicle Gate Pass**
- Employees can request a pass for vehicles entering the premises.
- Information needed includes:
  - Vehicle registration details.
  - Reason for visit.
  - Required documents like the vehicle's registration and driver's license.
- **Approval Process**:
  1. Security verifies the documents.
  2. Health and Safety (HSE) inspects the vehicle if entering technical areas.
  3. Security gives final approval or rejection.

#### d. **Material Gate Pass**
- Employees can request passes for materials being brought in or taken out.
- Required information:
  - Plant and location.
  - Estimated entry and exit times.
  - Documents like the driver's license and material details.
- **Approval Process**:
  - Security checks documents and provides approval.

#### e. **Reports and Analytics**
- The system should generate reports on:
  - Peak visiting times.
  - Frequent visitors.
  - Vehicle and material access details.
- These reports should be exportable for compliance and analysis.

---

### **3. Why the System is Needed**
The customer wants to:
- Make access to their facilities **secure** and **efficient**.
- **Automate manual processes** like approvals and notifications.
- **Ensure safety** by requiring medical and safety checks.
- **Track and analyze data** to improve their operations and compliance.

---

### **4. Example Scenario**
#### Visitor Management Example
1. **Employee registers a visitor** for a meeting at the LPG plant.
   - Employee fills in the visitor's name, email, purpose, and visit date.
   - Visitor receives an email with a form to upload their ID and complete a medical questionnaire.
2. **Health and Safety (HSE)** staff reviews the medical form.
   - If the visitor answers "Yes" to any critical question (e.g., illness symptoms), HSE staff can reject the visit.
3. Once approved:
   - The visitor receives a QR code for entry.
   - Security scans the QR code on arrival and notifies the host.

#### Vehicle Access Example
1. An employee registers a truck delivering materials.
2. Security reviews the truck's registration and driver's license.
3. If the truck enters a technical area, HSE inspects it.
4. After all checks, security approves the gate pass.

---

### **5. Key Expectations from You**
- Build a web-based application in .NET C# to handle all these processes.
- Include Single Sign-On (SSO) for employees to log in securely.
- Add features for uploading documents, sending notifications, and generating QR codes.
- Ensure the system is user-friendly for employees, visitors, and security staff.
