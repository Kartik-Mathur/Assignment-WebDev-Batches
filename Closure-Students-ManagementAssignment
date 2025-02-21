# **Student Management System**

## **Overview**
This project is a simple **Student Management System** implemented in JavaScript using closures. The system allows you to:
- Retrieve students by section
- Calculate the average marks of a section
- Add a new student
- Update a student's marks

---

## **Features**
### ✅ `getStudents(section)`
Retrieves an array of students belonging to the specified section.

### ✅ `getAvg(section)`
Returns the **average marks** of students in the given section.
- If there are no students in the section, it returns `0`.

### ✅ `addStudent(name, marks, section)`
Adds a new student to the system.
- **Parameters:**
  - `name` (string) – Name of the student
  - `marks` (number) – Marks of the student (defaults to `0` if not provided)
  - `section` (string) – Section of the student

### ✅ `updateMarks(name, marks)`
Updates the **marks** of an existing student.
- If the student is **not found**, the function does nothing.

---

## **Usage**
### **1️⃣ Initialize the Student Manager**
```javascript
const manager = studentManager();
```

### **2️⃣ Retrieve Students by Section**
```javascript
console.log(manager.getStudents("ECE"));
```
**Expected Output:**
```javascript
[
    { name: 'Vandana', marks: 100, section: "ECE" },
    { name: 'Reyanshi', marks: 99, section: "ECE" }
]
```

### **3️⃣ Calculate Average Marks for a Section**
```javascript
console.log(manager.getAvg("ECE"));
```
**Expected Output:**
```javascript
99.5
```

### **4️⃣ Add a New Student**
```javascript
manager.addStudent("Amit", 85, "IT");
console.log(manager.getStudents("IT"));
```
**Expected Output:**
```javascript
[
    { name: 'Deepika', marks: 98, section: "IT" },
    { name: 'Naman', marks: 50, section: "IT" },
    { name: 'Amit', marks: 85, section: "IT" }
]
```

### **5️⃣ Update Marks of an Existing Student**
```javascript
manager.updateMarks("Vandana", 95);
console.log(manager.getStudents("ECE"));
```
**Expected Output:**
```javascript
[
    { name: 'Vandana', marks: 95, section: "ECE" },
    { name: 'Reyanshi', marks: 99, section: "ECE" }
]
```

---
