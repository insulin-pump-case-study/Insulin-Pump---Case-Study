# Waterfall Model - Insulin Pump Case Study

## 1. Overview

**Waterfall Model** ß₧éß₧║ß₧çß₧╢ Software Process Model ß₧èßƒéß₧¢ß₧óß₧ùß₧╖ß₧£ß₧îßƒÆß₧ì System ß₧Åß₧╢ß₧ÿß₧¢ßƒåß₧èß₧╢ß₧ößƒïß₧çßƒåß₧áß₧╢ß₧ôß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒùßƒö
ß₧Üß₧╢ß₧¢ßƒï Phase ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧ëßƒÆß₧àß₧ößƒïß₧ÿß₧╗ß₧ôß₧ôß₧╣ß₧äß₧æßƒà Phase ß₧öß₧ôßƒÆß₧æß₧╢ß₧ößƒïßƒö

Main phases:
1. Requirements
2. Design
3. Implementation and Unit Testing
4. Integration and System Testing
5. Operation and Maintenance

Waterfall ß₧ÿß₧╢ß₧ô Structure ß₧àßƒÆß₧öß₧╢ß₧ƒßƒï ß₧äß₧╢ß₧Öß₧ƒßƒÆß₧Üß₧╜ß₧¢ Plan, Manage ß₧ôß₧╖ß₧ä Reviewßƒö ß₧ƒß₧ÿßƒÆß₧Üß₧╢ß₧ößƒï **Insulin Pump** ß₧èßƒéß₧¢ß₧çß₧╢ safety-critical system ß₧£ß₧╢ß₧çß₧╜ß₧Öß₧▒ßƒÆß₧Ö Team ß₧ÆßƒÆß₧£ß₧╛ß₧Çß₧╢ß₧Ü ß₧ôß₧╖ß₧äß₧Üß₧ÇßƒÆß₧ƒß₧╢ Documentation ß₧öß₧╢ß₧ôß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒö

---

## 2. Why Use Waterfall for Insulin Pump?

Insulin Pump ß₧çß₧╢ Medical Device ß₧èßƒéß₧¢ß₧ÿß₧╢ß₧ô Software ß₧éßƒÆß₧Üß₧ößƒïß₧éßƒÆß₧Üß₧äß₧Çß₧╢ß₧Üß₧òßƒÆß₧Åß₧¢ßƒï Insulinßƒö ß₧öß₧╛ Software ß₧ÿß₧╢ß₧ô Error ß₧óß₧╢ß₧àß₧ößƒëßƒçß₧ûß₧╢ß₧¢ßƒïß₧èß₧¢ßƒï Patient Safetyßƒö

ß₧èß₧╝ß₧àßƒÆß₧ôßƒüßƒç System ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧Çß₧╢ß₧Ü:
- Clear and testable Requirements
- Careful Design
- Step-by-step Development
- Systematic Testing
- Good Documentation
- Controlled Changes

Waterfall ß₧çß₧╜ß₧Öß₧▒ßƒÆß₧Öß₧Çß₧╢ß₧Üß₧äß₧╢ß₧Üß₧ÿß₧╢ß₧ôß₧¢ßƒåß₧èß₧╢ß₧ößƒïß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒö ß₧ößƒëß₧╗ß₧ôßƒÆß₧Åßƒé Safety-critical system ß₧ÇßƒÅß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧ÿß₧╢ß₧ô **Verification, Validation, Risk Management ß₧ôß₧╖ß₧ä Traceability** ß₧òß₧äß₧èßƒéß₧Üßƒö

---

## 3. How Waterfall Is Applied

### 3.1 Requirements

ß₧ÇßƒÆß₧ôß₧╗ß₧ä Phase ß₧ôßƒüßƒç Team ß₧Çßƒåß₧Äß₧Åßƒïß₧Éß₧╢ Insulin Pump ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧ÆßƒÆß₧£ß₧╛ß₧óßƒÆß₧£ß₧╕ß₧üßƒÆß₧¢ßƒçßƒö Requirements ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧ƒß₧Üß₧ƒßƒüß₧Üß₧▒ßƒÆß₧Ö Clear ß₧ôß₧╖ß₧ä Testableßƒö

Examples:
- System shall read Blood Glucose data from Sensor.
- System shall calculate Insulin Dose.
- System shall control Insulin Delivery.
- System shall detect abnormal conditions.
- System shall generate an Alarm when a serious problem occurs.
- System shall prevent an unsafe Dose.

Requirements ß₧ÇßƒÆß₧ôß₧╗ß₧ä Case Study ß₧ÿß₧╢ß₧ôß₧èß₧╝ß₧àß₧çß₧╢ **SRS-FR-01 to SRS-FR-07, SRS-SR-01, SRS-SR-02 ß₧ôß₧╖ß₧ä SRS-NFR-03**ßƒö

**Deliverables:** URD, SRS, Functional Requirements, Safety Requirements ß₧ôß₧╖ß₧ä Traceability Recordßƒö

### 3.2 Design

ß₧ÇßƒÆß₧ôß₧╗ß₧ä Phase ß₧ôßƒüßƒç Requirements ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧╢ß₧ôß₧öß₧ÿßƒÆß₧¢ßƒéß₧äß₧æßƒàß₧çß₧╢ System ß₧ôß₧╖ß₧ä Software Designßƒö Design ß₧öß₧äßƒÆß₧áß₧╢ß₧ëß₧ûß₧╕ Components, Interfaces ß₧ôß₧╖ß₧ä Data Flowßƒö

```text
Sensor / Patient Data
        |
Sensor Data Check
        |
Blood Glucose Calculation
        |
Insulin Dose Calculation
        |
Safety Check
        |
Pump Control
        |
Insulin Delivery
```

**Deliverables:** System Architecture, Software Design, Interfaces ß₧ôß₧╖ß₧ä Data-flow Diagramßƒö

### 3.3 Implementation and Unit Testing

Developer ß₧ƒß₧Üß₧ƒßƒüß₧Ü Code ß₧Åß₧╢ß₧ÿ Design ß₧èßƒéß₧¢ß₧öß₧╢ß₧ô Approveßƒö Component ß₧ôß₧╕ß₧ÿß₧╜ß₧Ößƒùß₧ÅßƒÆß₧Üß₧╝ß₧£ Test ß₧èß₧╢ß₧àßƒïß₧èßƒäß₧Öß₧íßƒéß₧Çßƒö

Examples:
- Test Dose Calculation
- Test Sensor Data Check
- Test Safety Check
- Test Alarm Function
- Test Pump Control

**Deliverables:** Source Code, Unit Test Cases ß₧ôß₧╖ß₧ä Unit Test Resultsßƒö

### 3.4 Integration and System Testing

ß₧öß₧ôßƒÆß₧æß₧╢ß₧ößƒïß₧ûß₧╕ Components ß₧ôß₧╕ß₧ÿß₧╜ß₧Ößƒù Test ß₧öß₧╢ß₧ôß₧¢ßƒÆß₧ó ß₧£ß₧╢ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧╢ß₧ô Combine ß₧áß₧╛ß₧Ö Test ß₧çß₧╢ß₧ÿß₧╜ß₧Öß₧éßƒÆß₧ôß₧╢ßƒö

```text
Sensor
   +
Dose Calculation
   +
Safety Check
   +
Pump Control
        |
Complete Insulin Pump System
        |
System Testing
```

Testing ß₧ÅßƒÆß₧Üß₧╝ß₧£ Check ß₧Éß₧╢ System ß₧ÆßƒÆß₧£ß₧╛ß₧Åß₧╢ß₧ÿ Requirements ß₧¼ß₧óß₧Åßƒï ß₧áß₧╛ß₧Öß₧ÅßƒÆß₧Üß₧╝ß₧£ Check Safety, Error Conditions ß₧ôß₧╖ß₧ä Performance ß₧òß₧äß₧èßƒéß₧Üßƒö

**Deliverables:** Integration Test Cases, System Test Cases, Test Report ß₧ôß₧╖ß₧ä Requirements-to-Test Traceabilityßƒö

### 3.5 Operation and Maintenance

ß₧öß₧ôßƒÆß₧æß₧╢ß₧ößƒïß₧ûß₧╕ System Pass Testing ß₧áß₧╛ß₧Öß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧╢ß₧ô Release ß₧£ß₧╢ß₧àß₧╝ß₧¢ß₧æßƒà Operation ß₧ôß₧╖ß₧ä Maintenanceßƒö

Maintenance ß₧óß₧╢ß₧àß₧ÿß₧╢ß₧ô:
- Fix Software Bugs
- Fix Defects
- Update System when approved
- Update Documentation
- Update Requirements and Tests when needed

ß₧ƒß₧ÿßƒÆß₧Üß₧╢ß₧ößƒï Medical Device ß₧Çß₧╢ß₧Üß₧òßƒÆß₧¢ß₧╢ß₧ƒßƒïß₧ößƒÆß₧Åß₧╝ß₧Ü ß₧ÅßƒÆß₧Üß₧╝ß₧£ Control ß₧ôß₧╖ß₧ä Test ß₧ÿß₧╗ß₧ôß₧ûßƒüß₧¢ Releaseßƒö

**Deliverables:** Maintenance Records, Updated Documents, Change Records ß₧ôß₧╖ß₧ä Regression Test Resultsßƒö

---

## 4. Example: Insulin Dose Safety

ß₧àßƒåß₧Äß₧╗ß₧àß₧ƒßƒåß₧üß₧╢ß₧ôßƒïß₧ÿß₧╜ß₧Öß₧éß₧║ System ß₧ÿß₧╖ß₧ôß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧òßƒÆß₧Åß₧¢ßƒï Insulin Dose ß₧èßƒéß₧¢ß₧ÿß₧╖ß₧ôß₧ÿß₧╢ß₧ôß₧ƒß₧╗ß₧£ß₧ÅßƒÆß₧Éß₧╖ß₧ùß₧╢ß₧ûßƒö

Example:

```text
Maximum Safe Dose = 10 units
Calculated Dose   = 15 units
```

System ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧ÆßƒÆß₧£ß₧╛ **Safety Check** ß₧ÿß₧╗ß₧ôß₧ûßƒüß₧¢ Delivery:

```text
Calculated Dose
       |
Safety Check
       |
15 > 10
       |
Prevent Unsafe Delivery
       |
Generate Alarm
```

ß₧ôßƒüßƒçß₧ÿß₧╢ß₧ôß₧ôßƒÉß₧Öß₧Éß₧╢ System ß₧ÅßƒÆß₧Üß₧╝ß₧£ Stop ß₧Çß₧╢ß₧Üß₧òßƒÆß₧Åß₧¢ßƒï Dose ß₧èßƒéß₧¢ß₧¢ß₧╛ß₧ƒ Limit ß₧ôß₧╖ß₧äß₧öß₧äßƒÆß₧áß₧╢ß₧ë Alarmßƒö ß₧£ß₧╢ß₧çß₧╜ß₧Ö Prevent Unsafe State ß₧ôß₧╖ß₧äß₧Çß₧╢ß₧Üß₧ûß₧╢ß₧Ü Patient Safetyßƒö

---

## 5. Key Strengths

### 5.1 Clear Structure

ß₧Üß₧╢ß₧¢ßƒï Phase ß₧ÿß₧╢ß₧ôß₧Çß₧╢ß₧Üß₧äß₧╢ß₧Üß₧àßƒÆß₧öß₧╢ß₧ƒßƒïß₧¢ß₧╢ß₧ƒßƒï ß₧èß₧╝ß₧àßƒÆß₧ôßƒüßƒç Team ß₧äß₧╢ß₧Öß₧èß₧╣ß₧äß₧Éß₧╢ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧ÆßƒÆß₧£ß₧╛ß₧óßƒÆß₧£ß₧╕ß₧ÿß₧╗ß₧ô ß₧ôß₧╖ß₧äß₧óßƒÆß₧£ß₧╕ß₧ÇßƒÆß₧Üßƒäß₧Ößƒö

### 5.2 Clear Requirements

Requirements ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧╢ß₧ôß₧Çßƒåß₧Äß₧Åßƒïß₧ÿß₧╗ß₧ô Coding ß₧áß₧╛ß₧Öß₧óß₧╢ß₧à Review ß₧ÿß₧╗ß₧ôß₧àß₧╝ß₧¢ Phase ß₧öß₧ôßƒÆß₧æß₧╢ß₧ößƒïßƒö

### 5.3 Good Documentation

ß₧Üß₧╢ß₧¢ßƒï Phase ß₧ÿß₧╢ß₧ô Documents ß₧ôß₧╖ß₧ä Deliverables ß₧èßƒéß₧¢ß₧óß₧╢ß₧à Review ß₧ôß₧╖ß₧ä Trace ß₧öß₧╢ß₧ôßƒö

### 5.4 Systematic Testing

Testing ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧öß₧╢ß₧ô Plan ß₧çß₧╢ß₧ÿß₧╗ß₧ô ß₧áß₧╛ß₧Öß₧óß₧╢ß₧à Link ß₧çß₧╢ß₧ÿß₧╜ß₧Ö Requirementsßƒö

### 5.5 Easy to Manage

Process ß₧èßƒéß₧¢ß₧ÿß₧╢ß₧ôß₧¢ßƒåß₧èß₧╢ß₧ößƒïß₧àßƒÆß₧öß₧╢ß₧ƒßƒï ß₧ÆßƒÆß₧£ß₧╛ß₧▒ßƒÆß₧Ö Project Planning ß₧ôß₧╖ß₧ä Progress Tracking ß₧äß₧╢ß₧Öß₧ƒßƒÆß₧Üß₧╜ß₧¢ßƒö

---

## 6. Limitations

### 6.1 Difficult to Change Requirements

ß₧öß₧╛ Requirements ß₧òßƒÆß₧¢ß₧╢ß₧ƒßƒïß₧ößƒÆß₧Åß₧╝ß₧Üß₧ôßƒàß₧ûßƒüß₧¢ Development ß₧öß₧╢ß₧ôß₧àß₧╢ß₧ößƒïß₧òßƒÆß₧Åß₧╛ß₧ÿ ß₧£ß₧╢ß₧óß₧╢ß₧àß₧ÆßƒÆß₧£ß₧╛ß₧▒ßƒÆß₧Öß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧Çßƒé Design, Code ß₧ôß₧╖ß₧ä Tests ß₧ÿßƒÆß₧Åß₧äß₧æßƒÇß₧Åßƒö

Example:

```text
Original Requirement
Maximum Dose = 10 units
        |
Design
        |
Implementation
        |
New Requirement
Maximum Dose = 8 units
```

ß₧Çß₧╢ß₧Üß₧òßƒÆß₧¢ß₧╢ß₧ƒßƒïß₧ößƒÆß₧Åß₧╝ß₧Üß₧ößƒéß₧öß₧ôßƒüßƒçß₧óß₧╢ß₧àß₧öß₧äßƒÆß₧Çß₧╛ß₧Å **Rework** ß₧ôß₧╖ß₧äß₧àßƒåß₧Äß₧╢ß₧Öß₧ûßƒüß₧¢ß₧öß₧ôßƒÆß₧Éßƒéß₧ÿßƒö

### 6.2 Feedback Can Come Late

User ß₧óß₧╢ß₧àß₧ÿß₧╖ß₧ôß₧âß₧╛ß₧ë Complete System ß₧Üß₧áß₧╝ß₧Åß₧èß₧¢ßƒïß₧àß₧╗ß₧ä Developmentßƒö ß₧èß₧╝ß₧àßƒÆß₧ôßƒüßƒç Problem ß₧üßƒÆß₧¢ßƒçß₧óß₧╢ß₧àß₧Üß₧Çß₧âß₧╛ß₧ëß₧Öß₧║ß₧Åßƒö

### 6.3 Late Changes Can Be Expensive

ß₧öß₧╛ Requirement ß₧òßƒÆß₧¢ß₧╢ß₧ƒßƒïß₧ößƒÆß₧Åß₧╝ß₧Üß₧Öß₧║ß₧Å ß₧óß₧╢ß₧àß₧ÅßƒÆß₧Üß₧╝ß₧£ Update Design, Code ß₧ôß₧╖ß₧ä Test Cases ß₧çß₧╢ß₧àßƒÆß₧Üß₧╛ß₧ôßƒö

---

## 7. Waterfall and V-Model

**V-Model** ß₧ÿß₧╢ß₧ôß₧éßƒåß₧ôß₧╖ß₧Åß₧ƒßƒÆß₧Üß₧èßƒÇß₧ä Waterfall ß₧ûßƒÆß₧Üßƒäßƒçß₧æß₧╢ßƒåß₧äß₧ûß₧╕ß₧Üß₧ÿß₧╢ß₧ô Planned ß₧ôß₧╖ß₧ä Structured Processßƒö

- **Waterfall** ß₧òßƒÆß₧Åßƒäß₧Åß₧¢ß₧╛ Development Steps ß₧Åß₧╢ß₧ÿß₧¢ßƒåß₧èß₧╢ß₧ößƒïßƒö
- **V-Model** ß₧òßƒÆß₧Åßƒäß₧Åß₧¢ß₧╛ Development ß₧ôß₧╖ß₧ä Testing ß₧èßƒéß₧¢ß₧ùßƒÆß₧çß₧╢ß₧ößƒïß₧éßƒÆß₧ôß₧╢ßƒö

Example:

```text
Requirements Specification  <->  Acceptance Testing
System Specification       <->  System Testing
Architecture Design        <->  Integration Testing
Detailed Design            <->  Unit Testing
             \              /
              Implementation
```

ß₧ƒß₧ÿßƒÆß₧Üß₧╢ß₧ößƒï Insulin Pump, V-Model ß₧óß₧╢ß₧àß₧çß₧╜ß₧Öß₧öß₧ôßƒÆß₧Éßƒéß₧ÿ **Testing ß₧ôß₧╖ß₧ä Traceability** ß₧æßƒàß₧ÇßƒÆß₧ôß₧╗ß₧ä Waterfall Processßƒö

---

## 8. Waterfall Phase Summary

| Phase | Main Activity | Main Deliverable |
|---|---|---|
| Requirements | ß₧Çßƒåß₧Äß₧Åßƒï System ß₧ôß₧╖ß₧ä Safety Needs | URD / SRS |
| Design | ß₧ÜßƒÇß₧öß₧àßƒå Architecture ß₧ôß₧╖ß₧ä Software Modules | Design Documents |
| Implementation | ß₧ƒß₧Üß₧ƒßƒüß₧Ü ß₧ôß₧╖ß₧ä Develop Code | Source Code |
| Testing | Test ß₧ôß₧╖ß₧ä Verify System | Test Cases / Test Report |
| Operation & Maintenance | Run, Fix ß₧ôß₧╖ß₧ä Update System | Maintenance Records |

---

## 9. Summary

**Waterfall Model** ß₧éß₧║ß₧çß₧╢ Process Model ß₧èßƒéß₧¢ß₧ÿß₧╢ß₧ôß₧¢ßƒåß₧èß₧╢ß₧ößƒïß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒû

```text
Requirements
     |
Design
     |
Implementation
     |
Testing
     |
Operation & Maintenance
```

ß₧ƒß₧ÿßƒÆß₧Üß₧╢ß₧ößƒï **Insulin Pump Case Study**, Waterfall ß₧çß₧╜ß₧Ö Team ß₧ÜßƒÇß₧öß₧àßƒå Requirements, Design, Coding, Testing ß₧ôß₧╖ß₧ä Documentation ß₧▒ßƒÆß₧Öß₧ÿß₧╢ß₧ô Order ß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒö

ß₧èßƒäß₧Öß₧ƒß₧╢ß₧Ü Insulin Pump ß₧çß₧╢ **Safety-critical Medical System**, Team ß₧ÅßƒÆß₧Üß₧╝ß₧£ß₧Öß₧Çß₧àß₧╖ß₧ÅßƒÆß₧Åß₧æß₧╗ß₧Çß₧èß₧╢ß₧Çßƒïß₧¢ß₧╛ Safety, Verification, Validation, Risk Management ß₧ôß₧╖ß₧ä Requirements Traceabilityßƒö

**V-Model** ß₧óß₧╢ß₧àß₧ößƒÆß₧Üß₧╛ß₧çß₧╢ß₧ÿß₧╜ß₧Ö Waterfall ß₧èß₧╛ß₧ÿßƒÆß₧öß₧╕ß₧ÆßƒÆß₧£ß₧╛ß₧▒ßƒÆß₧Ö Testing ß₧ôß₧╖ß₧ä Traceability ß₧Çß₧╢ß₧ôßƒïß₧Åßƒéß₧àßƒÆß₧öß₧╢ß₧ƒßƒïßƒö

## 10. References

- Sommerville, I. *Software Engineering*, 10th Edition.
- Software Process Models and Activities, Chapter 2.
- Insulin Pump Case Study - Safety and Software Requirements.
