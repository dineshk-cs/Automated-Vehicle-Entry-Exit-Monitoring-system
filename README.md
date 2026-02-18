# Automated-Vehicle-Entry-Exit-Monitoring-system

🚀 Project Summary

The Automated Vehicle Entry-Exit Monitoring System is an intelligent computer vision solution that automates vehicle access tracking using deep learning.

This system eliminates manual vehicle log maintenance by automatically detecting license plates, extracting vehicle numbers, and managing entry-exit records with accurate timestamp tracking and parking duration calculation and fare calculation based on type and parking duration.

It demonstrates the practical implementation of AI in real-world smart infrastructure systems.

💡 Problem Statement

Traditional vehicle entry systems rely on manual logging or RFID-based solutions, which are:

Time-consuming

Error-prone

Costly to maintain

Not scalable

This project provides a vision-based automated alternative using deep learning and OCR.

🧠 Solution Approach

The system leverages:

YOLOv8 for accurate license plate detection

EasyOCR for plate number extraction

Entry/Exit logic to determine vehicle movement

Automated timestamp logging

Duration computation based on real-time tracking

🔄 System Workflow

Vehicle image is provided as input.

YOLOv8 detects the number plate region.

The detected plate is cropped and processed.

EasyOCR extracts alphanumeric plate text.

System validates and cleans the extracted number.

If vehicle not found in records → ENTRY logged.

If vehicle already entered → EXIT logged + duration calculated.

Digital logbook updated automatically.

🛠️ Tech Stack

Python

YOLOv8 (Ultralytics) – Object Detection

EasyOCR – Optical Character Recognition

OpenCV – Image Processing

NumPy

⭐ Key Features

Real-time license plate detection

Automated entry/exit identification

Smart timestamp management

Parking duration computation

Structured digital vehicle logbook

Modular and scalable design

📊 Practical Applications

Smart Parking Infrastructure

Gated Community Access Control

College/University Vehicle Monitoring

Industrial Premises Security

Toll Booth Automation

📈 Engineering Highlights

Implemented deep learning-based object detection

Designed logical state management for entry/exit tracking

Integrated OCR pipeline with image preprocessing

Built a modular, extensible architecture

🔮 Future Improvements

Database integration (SQL/NoSQL)

Real-time CCTV stream support

Web dashboard with analytics

Cloud deployment & scalability

Multi-camera tracking system
