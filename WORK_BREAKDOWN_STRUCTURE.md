# Work Breakdown Structure (WBS)
## Battery Swapping Prototype - 4-Week Deliverable

**Project:** Team-O-Matic Battery Swapping System  
**Focus:** Boom Crane with Hydraulic Actuation Mechanism  
**Date Created:** October 2025

---

## WBS Overview

This Work Breakdown Structure decomposes the battery swapping prototype project into manageable work packages organized by major phases and subsystems. Each work package includes deliverables, responsible team members, and estimated effort.

---

## Level 1: Project Phases

```
1.0 Design & Planning
2.0 Procurement & Fabrication
3.0 Integration & Control
4.0 Testing & Documentation
```

---

## Level 2: Major Subsystems & Activities

### 1.0 Design & Planning

#### 1.1 Conceptual Design & Research
- **WBS Code:** 1.1
- **Owner:** Mohammed (Lead), Leonard (Support)
- **Duration:** 2 days
- **Deliverables:**
  - Design concept document
  - Concept sketches (3-5 variations)
  - Research summary on boom crane mechanisms
  - Hydraulic actuation requirements document
  - Battery interface specifications
- **Tasks:**
  - 1.1.1 Research existing battery swapping systems
  - 1.1.2 Research boom crane mechanisms and applications
  - 1.1.3 Analyze hydraulic actuation requirements
  - 1.1.4 Define battery interface specifications (connector, mounting)
  - 1.1.5 Create initial concept sketches
  - 1.1.6 Identify design constraints and limitations
  - 1.1.7 Document design concept

#### 1.2 Detailed CAD Design
- **WBS Code:** 1.2
- **Owner:** Mohammed (Primary), Leonard (Review)
- **Duration:** 3 days
- **Deliverables:**
  - Complete CAD assembly (SolidWorks)
  - Individual component drawings
  - Assembly drawings with dimensions
  - Basic stress analysis report
- **Tasks:**
  - 1.2.1 Design boom crane structure (base, arms, joints)
  - 1.2.2 Design battery gripper/release mechanism
  - 1.2.3 Design hydraulic actuator mounting points
  - 1.2.4 Design base platform/structure
  - 1.2.5 Design battery mounting interface on vehicle mockup
  - 1.2.6 Create assembly drawings
  - 1.2.7 Perform basic stress analysis on critical components
  - 1.2.8 Generate manufacturing drawings

#### 1.3 Component Selection & BOM
- **WBS Code:** 1.3
- **Owner:** Ben (Lead), Sam (Support)
- **Duration:** 3 days
- **Deliverables:**
  - Finalized Bill of Materials (BOM)
  - Component specifications document
  - Vendor information and pricing
  - Budget analysis (≤ $200)
- **Tasks:**
  - 1.3.1 Research and select hydraulic components
    - 1.3.1.1 Hydraulic cylinders (size, stroke length)
    - 1.3.1.2 Control valves (solenoid type)
    - 1.3.1.3 Hydraulic pump (manual or electric < 48V)
    - 1.3.1.4 Reservoir and fittings
  - 1.3.2 Select microcontroller and sensors
    - 1.3.2.1 Microcontroller (Arduino or similar)
    - 1.3.2.2 Position sensors (potentiometers/encoders)
    - 1.3.2.3 Limit switches
    - 1.3.2.4 Force sensors (if budget allows)
    - 1.3.2.5 Battery detection sensors
  - 1.3.3 Select structural materials
    - 1.3.3.1 Base platform material (aluminum/steel)
    - 1.3.3.2 Boom arm material
    - 1.3.3.3 Fasteners and hardware
  - 1.3.4 Select battery mockup materials
  - 1.3.5 Create detailed BOM with costs
  - 1.3.6 Verify budget compliance
  - 1.3.7 Identify backup vendors

#### 1.4 Design Review & Planning
- **WBS Code:** 1.4
- **Owner:** All Team Members
- **Duration:** 1 day
- **Deliverables:**
  - Design review document
  - Updated project timeline
  - Risk assessment document
  - Fabrication sequence plan
- **Tasks:**
  - 1.4.1 Team design review meeting
  - 1.4.2 Validate design against requirements
  - 1.4.3 Identify potential risks
  - 1.4.4 Develop mitigation strategies
  - 1.4.5 Finalize fabrication sequence
  - 1.4.6 Assign specific fabrication tasks
  - 1.4.7 Update project timeline

---

### 2.0 Procurement & Fabrication

#### 2.1 Component Procurement
- **WBS Code:** 2.1
- **Owner:** Ben (Lead), Sam (Support)
- **Duration:** 2 days
- **Deliverables:**
  - All components received
  - Component verification checklist
  - Procurement log
- **Tasks:**
  - 2.1.1 Place orders for all BOM items
  - 2.1.2 Track shipping and delivery
  - 2.1.3 Verify component specifications upon arrival
  - 2.1.4 Identify any substitutions needed
  - 2.1.5 Document any component issues

#### 2.2 Base Structure Fabrication
- **WBS Code:** 2.2
- **Owner:** Leonard (Lead), Ben (Support)
- **Duration:** 3 days
- **Deliverables:**
  - Completed base platform
  - Mounting points installed
  - Assembly verification report
- **Tasks:**
  - 2.2.1 Cut and prepare structural materials
  - 2.2.2 Weld/fasten base platform
  - 2.2.3 Install mounting points for boom crane
  - 2.2.4 Install mounting points for hydraulic system
  - 2.2.5 Install mounting points for control system
  - 2.2.6 Basic assembly verification
  - 2.2.7 Surface finishing (if needed)

#### 2.3 Boom Crane Fabrication
- **WBS Code:** 2.3
- **Owner:** Leonard (Primary), Mohammed (Design Support)
- **Duration:** 3 days
- **Deliverables:**
  - Completed boom crane assembly
  - Range of motion verification
  - Manual operation test report
- **Tasks:**
  - 2.3.1 Fabricate boom crane arms (scaled model)
    - 2.3.1.1 Cut boom segments to length
    - 2.3.1.2 Machine pivot points
    - 2.3.1.3 Install bearings/bushings
  - 2.3.2 Install pivot points and bearings
  - 2.3.3 Mount hydraulic actuator connection points
  - 2.3.4 Install battery gripper/release mechanism
    - 2.3.4.1 Design and fabricate gripper jaws
    - 2.3.4.2 Install actuation mechanism
    - 2.3.4.3 Test gripper engagement
  - 2.3.5 Test boom range of motion manually
  - 2.3.6 Verify boom stability and rigidity

#### 2.4 Battery Mockup & Interface
- **WBS Code:** 2.4
- **Owner:** Sam (Lead), Leonard (Fabrication Support)
- **Duration:** 3 days
- **Deliverables:**
  - Two battery mockups (old and new)
  - Battery mounting interface
  - Connector mockups installed
  - Fit verification report
- **Tasks:**
  - 2.4.1 Design battery mockup (scaled, ~5-10 lbs)
  - 2.4.2 Create battery mockups (2 units)
  - 2.4.3 Design and fabricate battery mounting interface
    - 2.4.3.1 Design latch mechanism
    - 2.4.3.2 Design alignment features
    - 2.4.3.3 Fabricate mounting bracket
  - 2.4.4 Install connectors (mock electrical connections)
  - 2.4.5 Test fit with boom crane gripper
  - 2.4.6 Verify battery can be securely held and released

---

### 3.0 Integration & Control

#### 3.1 Hydraulic System Integration
- **WBS Code:** 3.1
- **Owner:** Ben (Lead), Sam (Control Support)
- **Duration:** 3 days
- **Deliverables:**
  - Operational hydraulic system (manual control)
  - Hydraulic system test report
  - Leak check verification
- **Tasks:**
  - 3.1.1 Install hydraulic pump and reservoir
  - 3.1.2 Mount hydraulic cylinders to boom crane
    - 3.1.2.1 Install boom extension/retraction cylinder
    - 3.1.2.2 Install boom rotation cylinder (if applicable)
    - 3.1.2.3 Install gripper actuation cylinder
  - 3.1.3 Install control valves and plumbing
    - 3.1.3.1 Install solenoid valves
    - 3.1.3.2 Connect hydraulic lines
    - 3.1.3.3 Install pressure relief valves
  - 3.1.4 Test hydraulic system manually (no automation)
  - 3.1.5 Verify actuator range and force
  - 3.1.6 Check for leaks and pressure issues
  - 3.1.7 Calibrate pressure settings

#### 3.2 Sensor Installation
- **WBS Code:** 3.2
- **Owner:** Sam (Lead), Ben (Support)
- **Duration:** 3 days
- **Deliverables:**
  - All sensors installed
  - Sensor calibration data
  - Sensor wiring diagram
- **Tasks:**
  - 3.2.1 Install position sensors
    - 3.2.1.1 Install boom position sensors (potentiometers/encoders)
    - 3.2.1.2 Install gripper position sensor
  - 3.2.2 Install limit switches
    - 3.2.2.1 Install boom travel limit switches
    - 3.2.2.2 Install gripper open/close limit switches
  - 3.2.3 Install force sensors (if budget allows)
  - 3.2.4 Install battery presence/detection sensors
  - 3.2.5 Wire all sensors to microcontroller
  - 3.2.6 Test sensor readings
  - 3.2.7 Calibrate sensors

#### 3.3 Control System Development
- **WBS Code:** 3.3
- **Owner:** Sam (Primary), Ben (Hardware Support)
- **Duration:** 3 days
- **Deliverables:**
  - Functional control system
  - Control system code
  - Control sequence documentation
- **Tasks:**
  - 3.3.1 Set up microcontroller development environment
  - 3.3.2 Program microcontroller for hydraulic control
    - 3.3.2.1 Implement valve control functions
    - 3.3.2.2 Implement sensor reading functions
    - 3.3.2.3 Implement safety interlock functions
  - 3.3.3 Implement boom positioning algorithm
    - 3.3.3.1 Develop position control logic
    - 3.3.3.2 Implement PID or simple control algorithm
  - 3.3.4 Implement battery pickup sequence
    - 3.3.4.1 Approach battery position
    - 3.3.4.2 Engage battery gripper
    - 3.3.4.3 Release battery from vehicle
  - 3.3.5 Implement battery placement sequence
    - 3.3.5.1 Approach vehicle position
    - 3.3.5.2 Insert new battery
    - 3.3.5.3 Lock battery in place
    - 3.3.5.4 Disengage gripper
  - 3.3.6 Implement safety interlocks
    - 3.3.6.1 Emergency stop functionality
    - 3.3.6.2 Position limit checking
    - 3.3.6.3 Battery detection verification
  - 3.3.7 Create manual override capability
  - 3.3.8 Test individual control sequences
  - 3.3.9 Debug and refine control code

#### 3.4 System Integration & Initial Testing
- **WBS Code:** 3.4
- **Owner:** All Team Members
- **Duration:** 2 days
- **Deliverables:**
  - Integrated system
  - Initial test results
  - Integration issues log
- **Tasks:**
  - 3.4.1 Integrate all subsystems
  - 3.4.2 Run first complete swap sequence (slow, manual intervention allowed)
  - 3.4.3 Identify integration issues
  - 3.4.4 Debug and fix problems
  - 3.4.5 Refine control sequences
  - 3.4.6 Document integration process

---

### 4.0 Testing & Documentation

#### 4.1 Testing & Optimization
- **WBS Code:** 4.1
- **Owner:** Mohammed (Lead Testing), All Team Members
- **Duration:** 3 days
- **Deliverables:**
  - Test results report
  - Performance metrics (swap time, reliability)
  - Optimization log
- **Tasks:**
  - 4.1.1 Perform multiple swap cycles (target: 10+ successful swaps)
  - 4.1.2 Measure swap time (target: < 90 seconds)
  - 4.1.3 Identify and fix reliability issues
  - 4.1.4 Optimize control sequences for speed
  - 4.1.5 Fine-tune hydraulic pressures and timing
  - 4.1.6 Document any failures and solutions
  - 4.1.7 Verify 100% success rate achievement
  - 4.1.8 Create test procedure document

#### 4.2 Safety & Compliance Verification
- **WBS Code:** 4.2
- **Owner:** Ben (Lead), All Team Members
- **Duration:** 2 days
- **Deliverables:**
  - Safety compliance report
  - Safety checklist
  - Lockout/tagout procedures document
- **Tasks:**
  - 4.2.1 Verify all safety systems functional
  - 4.2.2 Check voltage compliance (< 48V)
  - 4.2.3 Verify lockout/tagout procedures
  - 4.2.4 Document safety features
  - 4.2.5 Create safety checklist
  - 4.2.6 Verify compliance with SFSU lab guidelines
  - 4.2.7 Document any safety concerns and mitigations

#### 4.3 Documentation
- **WBS Code:** 4.3
- **Owner:** All Team Members (Assigned Sections)
- **Duration:** 3 days
- **Deliverables:**
  - Technical report
  - Design documentation
  - Assembly instructions
  - Control system documentation
  - Presentation slides
  - Demonstration script
- **Tasks:**
  - 4.3.1 Write technical report
    - 4.3.1.1 Executive summary
    - 4.3.1.2 Introduction and background
    - 4.3.1.3 Design methodology
    - 4.3.1.4 System description
    - 4.3.1.5 Results and performance
    - 4.3.1.6 Conclusions and future work
  - 4.3.2 Document design decisions
  - 4.3.3 Create assembly instructions
  - 4.3.4 Document control system architecture
  - 4.3.5 Create presentation slides
  - 4.3.6 Prepare demonstration script
  - 4.3.7 Record video of system operation (if possible)
  - 4.3.8 Create system operation manual

#### 4.4 Final Preparation & Rehearsal
- **WBS Code:** 4.4
- **Owner:** All Team Members
- **Duration:** 2 days
- **Deliverables:**
  - Final system verification
  - Presentation ready
  - Backup plans documented
- **Tasks:**
  - 4.4.1 Final system testing and verification
  - 4.4.2 Practice demonstration
  - 4.4.3 Prepare backup plans for demo
  - 4.4.4 Finalize presentation
  - 4.4.5 Review all documentation
  - 4.4.6 Prepare Q&A responses
  - 4.4.7 Verify all deliverables complete

---

## WBS Dictionary

### Work Package Details

| WBS Code | Work Package | Owner | Duration | Dependencies |
|----------|--------------|-------|----------|--------------|
| 1.1 | Conceptual Design & Research | Mohammed | 2 days | None |
| 1.2 | Detailed CAD Design | Mohammed | 3 days | 1.1 |
| 1.3 | Component Selection & BOM | Ben | 3 days | 1.1, 1.2 (partial) |
| 1.4 | Design Review & Planning | All | 1 day | 1.2, 1.3 |
| 2.1 | Component Procurement | Ben | 2 days | 1.4 |
| 2.2 | Base Structure Fabrication | Leonard | 3 days | 2.1 |
| 2.3 | Boom Crane Fabrication | Leonard | 3 days | 2.1, 2.2 |
| 2.4 | Battery Mockup & Interface | Sam | 3 days | 2.1 |
| 3.1 | Hydraulic System Integration | Ben | 3 days | 2.2, 2.3 |
| 3.2 | Sensor Installation | Sam | 3 days | 2.2, 2.3, 3.1 (partial) |
| 3.3 | Control System Development | Sam | 3 days | 3.2 |
| 3.4 | System Integration & Initial Testing | All | 2 days | 3.1, 3.2, 3.3, 2.4 |
| 4.1 | Testing & Optimization | Mohammed | 3 days | 3.4 |
| 4.2 | Safety & Compliance Verification | Ben | 2 days | 3.4 |
| 4.3 | Documentation | All | 3 days | 4.1, 4.2 |
| 4.4 | Final Preparation & Rehearsal | All | 2 days | 4.3 |

---

## Resource Allocation Summary

### By Team Member

**Mohammed:**
- 1.1 Conceptual Design (Lead)
- 1.2 CAD Design (Primary)
- 4.1 Testing & Optimization (Lead)
- 4.3 Documentation (Assigned sections)

**Leonard:**
- 1.1 Conceptual Design (Support)
- 1.2 CAD Design (Review)
- 2.2 Base Structure Fabrication (Lead)
- 2.3 Boom Crane Fabrication (Primary)
- 2.4 Battery Mockup (Fabrication Support)
- 4.3 Documentation (Assigned sections)

**Ben:**
- 1.3 Component Selection & BOM (Lead)
- 2.1 Component Procurement (Lead)
- 2.2 Base Structure Fabrication (Support)
- 3.1 Hydraulic System Integration (Lead)
- 3.2 Sensor Installation (Support)
- 3.3 Control System Development (Hardware Support)
- 4.2 Safety & Compliance Verification (Lead)
- 4.3 Documentation (Assigned sections)

**Sam:**
- 1.3 Component Selection & BOM (Support)
- 2.1 Component Procurement (Support)
- 2.4 Battery Mockup & Interface (Lead)
- 3.1 Hydraulic System Integration (Control Support)
- 3.2 Sensor Installation (Lead)
- 3.3 Control System Development (Primary)
- 4.1 Testing & Optimization (Support)
- 4.3 Documentation (Assigned sections)

---

## Deliverables Checklist

### Week 1 Deliverables
- [ ] Design concept document
- [ ] Complete CAD assembly
- [ ] Finalized BOM
- [ ] Design review document

### Week 2 Deliverables
- [ ] All components received
- [ ] Base structure complete
- [ ] Boom crane mechanism assembled
- [ ] Battery mockups complete

### Week 3 Deliverables
- [ ] Hydraulic system operational
- [ ] All sensors installed and calibrated
- [ ] Control system functional
- [ ] Integrated system performs basic swap

### Week 4 Deliverables
- [ ] System achieves < 90 second swap time
- [ ] 100% reliability demonstrated
- [ ] Safety compliance verified
- [ ] Technical report complete
- [ ] Presentation ready
- [ ] Demonstration script prepared

---

## Risk Register

| Risk ID | Risk Description | Impact | Probability | Mitigation Strategy | Owner |
|---------|------------------|--------|-------------|---------------------|-------|
| R1 | Component procurement delays | High | Medium | Order early, identify backup vendors | Ben |
| R2 | Budget exceeds $200 | High | Medium | Continuous budget tracking, prioritize essential components | Ben |
| R3 | Fabrication complexity exceeds timeline | High | Medium | Build in buffer time, have simplified backup design | Leonard |
| R4 | Control system too complex for timeline | High | Medium | Start with basic sequences, iterate | Sam |
| R5 | Integration issues between subsystems | Medium | High | Test subsystems independently before integration | All |
| R6 | Hydraulic system leaks or failures | Medium | Low | Proper installation, pressure testing, backup seals | Ben |
| R7 | Swap time exceeds 90 seconds | Medium | Medium | Optimize sequences, fine-tune timing | All |
| R8 | Reliability issues during testing | High | Medium | Extensive testing, identify and fix issues early | Mohammed |

---

## Notes

- This WBS aligns with the Gantt chart timeline
- Work packages can be further decomposed as needed during execution
- Dependencies should be monitored closely to avoid delays
- Team should update progress on work packages during weekly meetings
- All deliverables should be reviewed by the team before finalization

---

*This WBS is a living document and should be updated as the project progresses. Last updated: October 2025*

