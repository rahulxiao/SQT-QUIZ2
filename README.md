# Software Quality Assurance & Testing Maturity Model (Simple Notes with Examples)

## 1. Testing Maturity Model (TMM) — Five Levels

The Testing Maturity Model (TMM) describes how advanced and organized a company's testing process is.  
It has **five levels**, from no process → fully optimized process.

---

## **Level 1 — Initial**
Testing is unplanned and done randomly.

### **Characteristics**
- Testing starts only after coding.
- No rules or structure.
- No tracking of progress.

### **Example**
A developer finishes coding and just clicks around randomly to see if things work.

---

## **Level 2 — Phase Definition**
Basic testing rules and planning begin.

### **Characteristics**
- Test goals are defined.
- Simple test strategy is created.
- Basic testing techniques are introduced.

### **Example**
Before testing, the team prepares a small plan writing:
- What to test  
- How to test  
- Who will test  

---

## **Level 3 — Integration**
Testing becomes part of the entire software development process.

### **Characteristics**
- A dedicated testing team is formed.
- Testers receive training.
- Testing happens in all SDLC phases.

### **Example**
Testers check requirements, design, and code *before* the product is completed, not just at the end.

---

## **Level 4 — Management & Measurement**
Testing is measured, tracked, and controlled using data.

### **Characteristics**
- Defect metrics are recorded.
- Testing performance is monitored.
- Organization-wide review processes are established.

### **Example**
The company tracks:
- Number of bugs  
- Testing time  
- Test case pass/fail rates  

Then uses the data to improve processes.

---

## **Level 5 — Optimization**
Continuous process improvement and defect prevention.

### **Characteristics**
- Uses collected data to prevent future defects.
- Testing processes are optimized regularly.

### **Example**
If many login bugs occur, coding guidelines are changed to prevent similar bugs in the future.

---

# 2. Software Quality Assurance (SQA)

SQA is everything done to ensure the software is correct, reliable, and high quality.

SQA activities fall into **three categories**:

---

## **1. Defect Prevention**
Avoid mistakes before they happen.

### **Activities**
- Clear requirements
- Developer training
- Tools that block incorrect input

### **Example**
A form prevents the user from entering `0` for a divisor to avoid a divide-by-zero error.

---

## **2. Defect Reduction**
Find and fix mistakes already in the software.

### **Activities**
- Code reviews
- Unit testing, integration testing, system testing

### **Example**
A team does a code inspection and finds a missing variable initialization before running the program.

---

## **3. Defect Containment**
Reduce the damage when a defect causes a failure.

### **Activities**
- Auto-save
- Error handling
- Fault-tolerance mechanisms

### **Example**
A text editor crashes but saves a backup automatically, preventing data loss.

---

# 3. How SQA Matches the Waterfall SDLC

SQA work aligns with each phase of the Waterfall software development model.

---

## **Defect Prevention → Requirements & Design Phase**
Stop defects early.

### **Example**
Team reviews requirement documents to fix unclear details before coding.

---

## **Defect Reduction → Coding & Testing Phase**
Find and remove defects.

### **Example**
Integration testing finds a problem between the login module and dashboard module; developers fix it.

---

## **Defect Containment → Release & Maintenance Phase**
Limit the effect of remaining defects.

### **Example**
An app crashes, but restores user data from an auto-save feature.

---

# End of Documentation

