# University Examination Management System

## Overview

The University Examination Management System is a DBMS project designed to manage examination-related activities for a university with multiple affiliated colleges. The system stores and manages student records, subjects, examinations, examination centres, fees, and results in an organized and efficient manner.

---

## Objectives

- Manage student, college, and degree information.
- Track subject registrations and marks.
- Schedule examinations and allocate centres.
- Maintain examination fee records.
- Generate reports for academic, administrative, and finance departments.

---

## Database Entities

- University
- College
- Degree
- Student
- Subject
- College_Subject
- Student_Subject
- Exam
- Examination_Centre
- Exam_Centre_Allocation
- Exam_Fee

---

## Features

- Student Management
- Subject Management
- Examination Scheduling
- Centre Allocation
- Fee Tracking
- Result Management
- Report Generation

---

## Database Design

The database is normalized up to **Third Normal Form (3NF)** to reduce redundancy and maintain data integrity.

### Relationships
- University → College (1:M)
- College → Student (1:M)
- Degree → Student (1:M)
- College → College_Subject (1:M)
- Subject → College_Subject (1:M)
- Student → Student_Subject (1:M)
- Subject → Student_Subject (1:M)
- Subject → Exam (1:M)
- Exam → Exam_Centre_Allocation (1:M)
- Examination_Centre → Exam_Centre_Allocation (1:M)
- Student → Exam_Fee (1:1)

---

## Tools Used

- Draw.io
- Microsoft Excel
- SQL
- GitHub

---

## Project Files

- ER Diagram
- Excel Sheet
- Readme
  

---

