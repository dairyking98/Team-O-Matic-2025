# Gantt Chart - Battery Swapping Prototype (First Prototype)

**Project:** Team-O-Matic Battery Swapping System  
**Focus:** Boom Crane with Hydraulic Actuation Mechanism  
**Timeline:** 6 Weeks (November 6 - December 19, 2025)  
**Final Deliverable:** First Prototype Demonstration - December 19, 2025  
**Date Created:** October 2025  
**Last Updated:** November 2025

---

## Project Overview

This Gantt chart outlines the development timeline for the battery swapping subsystem prototype, focusing on the most challenging aspect: the mechanical swapping mechanism using boom cranes with hydraulic actuation. The prototype will demonstrate the core functionality of removing an old battery and inserting a new one using a democratized, accessible approach.

### Key Objectives
- **Swap Time:** < 90 seconds (target: < 2 minutes)
- **Reliability:** 100% success rate during demonstration
- **Budget:** ≤ $200
- **Size:** < 4ft³ (scaled model)
- **Safety:** < 48V, compliant with SFSU lab guidelines

---

## Timeline Overview

| Week | Dates | Phase | Key Deliverables |
|------|-------|-------|------------------|
| **Week 1** | Nov 6-12 | Design & Planning | Conceptual design, initial CAD models, component research |
| **Week 2** | Nov 13-19 | Design Finalization & Procurement | CAD complete, BOM finalized, orders placed |
| **Week 3** | Nov 20-26 | Procurement & Initial Setup | Components received, lab setup, component testing |
| **Week 4** | Nov 27 - Dec 3 | Fabrication | Base structure, boom crane fabrication begins |
| **Week 5** | Dec 4-10 | Assembly & Integration | Mechanical assembly, hydraulic integration, sensor installation |
| **Week 6** | Dec 11-19 | Testing, Refinement & Documentation | System testing, optimization, documentation, final demonstration prep |

---

## Detailed Task Breakdown

### Week 1: Design & Planning (Nov 6-12)

#### Conceptual Design & Research
- **Owner:** Mohammed (Lead), Leonard (Support)
- **Tasks:**
  - Research existing boom crane mechanisms
  - Research existing battery swapping systems
  - Analyze hydraulic actuation requirements
  - Define battery interface specifications (connector type, mounting points)
  - Create initial concept sketches (3-5 variations)
  - Identify critical design constraints
  - Team brainstorming sessions
- **Deliverable:** Design concept document with sketches, research summary

#### Detailed CAD Design (Week 1 continued)
- **Owner:** Mohammed (Primary), Leonard (Review & Input)
- **Tasks:**
  - Design boom crane structure (SolidWorks)
  - Design battery mounting/release mechanism
  - Design hydraulic actuator mounting points
  - Design base platform/structure
  - Design battery mounting interface on vehicle mockup
  - Create assembly drawings with dimensions
  - Perform basic stress analysis on critical components
  - Iterate on design based on team feedback
- **Deliverable:** Complete CAD assembly with all components, manufacturing drawings

### Week 2: Design Finalization & Procurement (Nov 13-19)

#### Component Selection, BOM & Design Review
- **Owner:** Ben (Lead Component Selection), Sam (Support), Mohammed (Design Review Lead), All Team Members
- **Tasks:**
  - Research and select hydraulic components (cylinders, valves, pump)
  - Select microcontroller and sensors (position, force, limit switches)
  - Select structural materials (aluminum, steel, or composite)
  - Identify battery mockup materials
  - Create detailed BOM with costs
  - Verify budget compliance (≤ $200)
  - Identify backup vendors
  - Team design review meeting
  - Validate design against requirements
  - Identify potential risks and mitigation strategies
  - Finalize fabrication sequence
  - Assign specific fabrication tasks
- **Deliverable:** Finalized BOM with vendor information, design review document, updated timeline

#### Component Procurement (Week 2 continued)
- **Owner:** Ben (Lead), Sam (Support)
- **Tasks:**
  - Place orders for all BOM items
  - Track shipping and delivery
  - Verify component specifications upon arrival
  - Identify any substitutions needed
  - Document any component issues
  - Prepare lab space and tools
- **Deliverable:** Orders placed, procurement tracking initiated

**Week 1-2 Milestone:** ✅ Design approved, BOM finalized, procurement initiated

---

### Week 3: Procurement & Initial Setup (Nov 20-26)

#### Component Receipt & Initial Setup
- **Owner:** All Team Members
- **Tasks:**
  - Set up lab workspace
  - Test individual components (sensors, actuators, microcontroller)
  - Verify component compatibility
  - Begin preliminary assembly planning
  - Create fabrication jigs/templates if needed
  - Safety equipment check
- **Deliverable:** All components received and verified, lab space prepared, components tested

**Week 3 Milestone:** ✅ All components acquired and verified, lab ready

---

### Week 4: Fabrication (Nov 27 - Dec 3)

#### Base Structure Fabrication
- **Owner:** Leonard (Lead), Ben (Support)
- **Tasks:**
  - Cut and prepare structural materials
  - Weld/fasten base platform
  - Install mounting points for boom crane
  - Install mounting points for hydraulic system
  - Install mounting points for control system
  - Basic assembly verification
  - Surface finishing (if needed)
- **Deliverable:** Base structure complete, assembly verification report

#### Boom Crane Fabrication (Week 4 continued)
- **Owner:** Leonard (Primary), Mohammed (Design Support)
- **Tasks:**
  - Fabricate boom crane arms (scaled model)
  - Machine pivot points
  - Install pivot points and bearings/bushings
  - Mount hydraulic actuator connection points
  - Install battery gripper/release mechanism
  - Design and fabricate gripper jaws
  - Test boom range of motion manually
  - Verify boom stability and rigidity
- **Deliverable:** Boom crane mechanism assembled, range of motion verified

#### Battery Mockup & Interface (Week 4 continued)
- **Owner:** Sam (Lead), Leonard (Fabrication Support)
- **Tasks:**
  - Design battery mockup (scaled, ~5-10 lbs)
  - Create scaled battery mockups (2 units: old and new)
  - Design and fabricate battery mounting interface
  - Design latch mechanism
  - Design alignment features
  - Install connectors (mock electrical connections)
  - Test fit with boom crane gripper
  - Verify battery can be securely held and released
- **Deliverable:** Battery mockups and interface complete, fit verification report

**Week 4 Milestone:** ✅ All mechanical components fabricated

---

### Week 5: Assembly & Integration (Dec 4-10)

#### Mechanical Assembly
- **Owner:** Leonard (Lead), All Team Members
- **Tasks:**
  - Assemble boom crane to base structure
  - Install all mechanical components
  - Verify all mechanical interfaces
  - Test manual operation of all mechanisms
  - Identify and fix any mechanical issues
  - Document assembly process
- **Deliverable:** Complete mechanical assembly, manual operation verified

#### Hydraulic System Integration (Week 5 continued)
- **Owner:** Ben (Lead), Sam (Control Support)
- **Tasks:**
  - Install hydraulic pump and reservoir
  - Mount hydraulic cylinders to boom crane
  - Install control valves and plumbing
  - Install pressure relief valves
  - Test hydraulic system manually (no automation)
  - Verify actuator range and force
  - Check for leaks and pressure issues
  - Calibrate pressure settings
- **Deliverable:** Hydraulic system operational (manual control), leak check verified

#### Sensor Installation & Control System Development (Week 5 continued)
- **Owner:** Sam (Lead Sensors & Control), Ben (Hardware Support)
- **Tasks:**
  - Install position sensors (potentiometers or encoders)
  - Install limit switches for boom positions
  - Install force sensors (if budget allows)
  - Install battery presence/detection sensors
  - Wire all sensors to microcontroller
  - Test and calibrate sensor readings
  - Set up microcontroller development environment
  - Program microcontroller for hydraulic control
  - Implement boom positioning algorithm
  - Implement battery pickup sequence
  - Implement battery placement sequence
  - Implement safety interlocks
  - Create manual override capability
  - Test individual control sequences
- **Deliverable:** All sensors installed and calibrated, control system functional with basic sequences

**Week 5 Milestone:** ✅ Hydraulic and control systems integrated

---

### Week 6: Testing, Refinement & Documentation (Dec 11-19)

#### System Integration & Initial Testing
- **Owner:** All Team Members, Mohammed (Lead Testing)
- **Tasks:**
  - Integrate all subsystems
  - Run first complete swap sequence (slow, manual intervention allowed)
  - Identify integration issues
  - Debug and fix problems
  - Refine control sequences
  - Document integration process
- **Deliverable:** Integrated system performs basic swap operation

#### Testing, Optimization & Safety Verification (Week 6 continued)
- **Owner:** Mohammed (Lead Testing), Ben (Lead Safety), All Team Members
- **Tasks:**
  - Perform multiple swap cycles (target: 10+ successful swaps)
  - Measure swap time (target: < 90 seconds)
  - Identify and fix reliability issues
  - Optimize control sequences for speed
  - Fine-tune hydraulic pressures and timing
  - Document any failures and solutions
  - Verify all safety systems functional
  - Check voltage compliance (< 48V)
  - Verify lockout/tagout procedures
  - Document safety features
  - Create safety checklist
  - Create test procedure document
- **Deliverable:** System achieves < 90 second swap time with 100% reliability, safety compliance verified

#### Documentation & Final Preparation (Week 6 continued)
- **Owner:** All Team Members (Assigned Sections)
- **Tasks:**
  - Write technical report (executive summary, introduction, methodology, results, conclusions)
  - Document design decisions
  - Create assembly instructions
  - Document control system architecture
  - Create presentation slides
  - Prepare demonstration script
  - Record video of system operation (if possible)
  - Create system operation manual
  - Final system testing and verification
  - Practice demonstration
  - Prepare backup plans for demo
  - Finalize presentation
  - Review all documentation
  - Prepare Q&A responses
- **Deliverable:** Complete documentation package, ready for demonstration

**Week 6 Milestone:** ✅ First Prototype complete, tested, documented, ready for demonstration on December 19, 2025

---

## Next Semester Timeline (January - June 2026)

**Note:** A detailed Gantt chart for the second semester (end of January through June 2026) will be developed after the first prototype demonstration. The second semester will focus on:
- Full-scale system development
- Enhanced features and capabilities
- Integration with charging infrastructure
- Field testing and validation
- Final deliverable and showcase preparation (June 2026)

---

## Gantt Chart Visualization

```
Task                                    | W1  | W2  | W3  | W4  | W5  | W6
                                        |Nov6 |Nov13|Nov20|Nov27|Dec4 |Dec11
                                        |Nov12|Nov19|Nov26|Dec3 |Dec10|Dec19
----------------------------------------|-----|-----|-----|-----|-----|-----
Design & Planning                       | ███ | █   |     |     |     |
  - Conceptual Design                   | ███ |     |     |     |     |
  - CAD Design                          | ███ |     |     |     |     |
  - Component Selection & BOM           |     | ███ |     |     |     |
  - Design Review                       |     | █   |     |     |     |
Procurement                             |     | ███ | ███ |     |     |
  - Order Placement                     |     | ███ |     |     |     |
  - Component Receipt & Testing         |     |     | ███ |     |     |
Fabrication                             |     |     |     | ███ |     |
  - Base Structure                      |     |     |     | ███ |     |
  - Boom Crane                          |     |     |     | ███ |     |
  - Battery Mockup                      |     |     |     | ███ |     |
Assembly & Integration                 |     |     |     |     | ███ |
  - Mechanical Assembly                 |     |     |     |     | ███ |
  - Hydraulic System                    |     |     |     |     | ███ |
  - Sensors & Control System            |     |     |     |     | ███ |
Testing & Documentation                 |     |     |     |     |     | ███
  - System Integration                  |     |     |     |     |     | ███
  - Testing & Optimization              |     |     |     |     |     | ███
  - Safety Verification                 |     |     |     |     |     | ███
  - Documentation                       |     |     |     |     |     | ███
  - Final Preparation                   |     |     |     |     |     | ███
```

---

## Critical Path Analysis

### Critical Path (Must Complete On Time)
1. **Design & CAD** (Week 1) → Blocks procurement
2. **BOM Finalization** (Week 2) → Blocks procurement
3. **Component Procurement** (Week 2-3) → Blocks all fabrication
4. **Base Structure Fabrication** (Week 4) → Blocks boom crane assembly
5. **Boom Crane Fabrication** (Week 4) → Blocks integration
6. **Mechanical Assembly** (Week 5) → Blocks hydraulic integration
7. **Hydraulic System Integration** (Week 5) → Blocks sensor installation
8. **Control System Development** (Week 5) → Blocks testing
9. **System Integration** (Week 6) → Blocks optimization
10. **Testing & Optimization** (Week 6) → Blocks documentation

### Risk Mitigation
- **Procurement Delays:** Order components early (Week 4), have backup vendors identified
- **Fabrication Issues:** Build in buffer time (4 weeks for fabrication), have simplified backup design ready
- **Control System Complexity:** Start with basic sequences, iterate throughout Week 11
- **Integration Problems:** Test subsystems independently before integration (Week 5 component testing)
- **Time Constraints:** Prioritize core functionality over polish, use full semester timeline
- **Design Iterations:** Allow time for design review and iterations (Weeks 1-3)

---

## Team Member Responsibilities Summary

### Mohammed (SolidWorks + Design)
- Lead CAD design (Week 1)
- Design review and validation
- Lead testing coordination (Week 4)

### Leonard (Fabrication + 3D Modeling)
- Support CAD design
- Lead fabrication tasks (Week 2)
- Welding, metalwork, assembly

### Ben (Hardware + Control)
- Lead component selection and procurement
- Lead hydraulic system integration
- Support control system development
- Lead safety verification

### Sam (Microcontroller + DSP)
- Support component selection
- Lead sensor installation
- Lead control system programming
- Support testing and optimization

---

## Key Design Considerations for Prototype

### Boom Crane Mechanism
- **Type:** Articulated boom with 2-3 segments
- **Actuation:** Hydraulic cylinders for boom extension/retraction and rotation
- **Range:** Must reach battery position on scaled vehicle mockup
- **Payload:** Must handle scaled battery weight (~5-10 lbs for prototype)

### Battery Interface
- **Connection Type:** Quick-disconnect electrical connector (mock)
- **Mounting:** Secure latch mechanism that can be released by crane
- **Alignment:** Self-aligning features or guided insertion

### Hydraulic System
- **Power:** Manual pump or small electric pump (< 48V)
- **Control:** Solenoid valves controlled by microcontroller
- **Safety:** Pressure relief valves, manual override

### Control System
- **Microcontroller:** Arduino or similar (within budget)
- **Sensors:** Position feedback, limit switches, battery detection
- **Sequence:** 
  1. Approach battery position
  2. Engage battery gripper
  3. Release battery from vehicle
  4. Retract and move to storage position
  5. Place old battery in storage
  6. Pick up new battery
  7. Approach vehicle position
  8. Insert new battery
  9. Lock battery in place
  10. Disengage gripper
  11. Retract boom

---

## Success Criteria

### Functional Requirements
- ✅ System successfully removes old battery from vehicle mockup
- ✅ System successfully inserts new battery into vehicle mockup
- ✅ Complete swap cycle < 90 seconds
- ✅ 100% success rate (10/10 successful swaps)

### Technical Requirements
- ✅ All components within budget (≤ $200)
- ✅ System fits within size constraint (< 4ft³)
- ✅ Voltage < 48V throughout
- ✅ Safety systems functional

### Documentation Requirements
- ✅ Technical report complete
- ✅ Design documentation complete
- ✅ Presentation ready
- ✅ Demonstration script prepared

---

## Notes

- **Timeline:** November 6 - December 19, 2025 (6 weeks) for first prototype
- **Final Deliverable:** First prototype demonstration on December 19, 2025
- **Next Semester:** End of January - June 2026 for full system development and final showcase
- This accelerated timeline requires focused work and regular team meetings
- Team should meet weekly (Thursdays 8pm per team charter) to review progress
- Critical decisions should be made as a team per team charter guidelines
- All design changes must be documented per team charter decision-making process
- **Priority:** Core functionality over polish for first prototype
- **Risk Mitigation:** Parallel work streams where possible, simplified designs if needed

---

*This Gantt chart is a living document and should be updated as the project progresses. Last updated: November 2025*

