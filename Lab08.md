# Lab 8 Software Drivers for an Embedded System

## Table of Contents
- [Lab 8 Software Drivers for an Embedded System](#lab-8-software-drivers-for-an-embedded-system)
  - [Table of Contents](#table-of-contents)
  - [Summary](#summary)
    - [Goals](#goals)
    - [Team Size](#team-size)
    - [Review](#review)
    - [Starter Files](#starter-files)
    - [Background](#background)
  - [Preparation](#preparation)
  - [Procedure](#procedure)
  - [Checkout](#checkout)
  - [Report](#report)
    - [Deliverables](#deliverables)
    - [Analysis and Discussion Questions](#analysis-and-discussion-questions)
  - [Grading](#grading)

## Summary

### Goals

1. Collect and test all hardware components for the project
2. Write low-level software for each I/O interface
3. Validate that overall project is possible and update the requirements document

### Team Size

The team size is 4

> “In the beginning we were a group of nine.
> 
> Three are gone, dead.
> There are six of us left.
> They are hunting us, and they won't stop until they've killed us all.
> 
> I am Number Four.
> 
> I know that I am next.”

### Review

Datasheets for all components within the system

### Starter Files

None

### Background

Normally one passes around the design cycle multiple times. However, Labs 7, 8, and 11 represent one pass around the design cycle in this class. In this lab you will create prototype hardware and software implementations. The goal is to verify your collection of chips, resistors, capacitors, and connectors will operate as intended when you get to Lab 11. Furthermore, you will write and test low-level software drivers for all I/O interfaces. The more you develop and test during this lab, the higher the probability your product in Lab 11 will function as intended.

---

## Preparation

1. Split the project into four or more subcomponents. Each student will be responsible for at least one subcomponent (including but not limited to sensors, actuators, WiFi, BLE, enclosure, power, UI/UX).TAs will judge if the project is sufficiently complicated.
2. Collect all resistors, capacitos, ships, connectors, and components you require for your project. At this point, you should have all parts needed to build the system except for the PCB.
3. Write all the header files (prototypes for public functinos for your entire system. The most efficient process is to have designed, implemented, and typed all software as part of the preparation. With this, you can build the circuits and debug while the TA is present.

---

## Procedure

1. Procure or build the enclosure for the project.
2. Write all low-level drivers required to interface with the hardware. You are not required to have the high-level software written for Lab 8. Test all your low-level device drivers and ensure you can interact with the hardware as expected.
3. Modify the requirements document to reflect any changes in your system. for example, you may find your system will have higher or lower performance than originally conceived. You may also need to modify the functionality of your system.
4. Collect preliminary performance data as appropriate. This step is especially important if your device has transducers.

---

## Checkout

Show the hardware/software prototype of your system to your TA. Explain how the prototype is different from the final product. Discuss the testing features of your design. Discuss your top three worries about finishing Lab 11 on time.

---

## Report

### Deliverables

1. Objectics (requirements document)
2. Hardware Design
   1. Modified circuit diagram (`.sch` file) as tested in Lab 8
3. Software Design
   1. Low-level drivers
4. Measurement Data
   1. Any performance data that was collected

### Analysis and Discussion Questions

None

---

## Grading

| Section | Description | Points |
|---|---|---|
| Preparation: Parts | Show all parts to the TA | 10 |
| Preparation: `.sch` File | Most recent `.sch` file | 5 |
| Preparation: Header Files | Header files for software drivers | 5 |
| Checkout: Prototype Demonstration and Quality of Design | Points will be deducted if you do not have 80% or more of the parts and connectors need for the final project | 25 |
| Checkout: Top 3 Worries | Not identifying a worry is a worry | 5 |
| Software Quality: Modularity and Organization | N/A | 10 |
| Software Quality: Readability | N/A | 10 |
| Software Quality: Functionality | N/A | 10 |
| Report: Requirements Document | Updated version of the requirements document | 10 |
| Report: Measurement Data | Perfomance data that was collected | 5 |
| Report: Modified Schematic | Identifying any modifications in the PCB that will be needed | 5 |
