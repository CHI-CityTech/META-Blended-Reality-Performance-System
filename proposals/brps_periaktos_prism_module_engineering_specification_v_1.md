# BRPS Periaktos Prism Module (PPM)
## Design Specification v1.0

**Document Title:** Periaktos Prism Module Design Specification  
**Part of:** Blended Reality Performance System (BRPS)  
**Version:** 1.0  
**Date:** February 17, 2026

---

## Overview & Status

This document establishes the **design framework** for the Periaktos Prism Module (PPM), a core deployable component within the **Blended Reality Performance System (BRPS)**. The PPM defines structural principles, interface standards, and geometric constraints while remaining open to iteration as component selections and prototyping validate assumptions. 

**This is a living document** for the development phase. Sections marked with ◆ indicate parameters to be locked during prototype fabrication.

---

## 1. System Overview

The Periaktos Prism Module (PPM) is a modular, mobile structural and media system designed for use within the Blended Reality Performance System (BRPS). The PPM integrates projection, structural framing, and optional audio mounting into a unified, repeatable unit.

The system is based on an **isosceles triangular prism geometry**, supporting a **single active projection screen per operational orientation**, with optional rotation and reconfiguration.

This document defines a **design framework** that supports multiple variants while maintaining consistent structural and interface principles.

---

## 2. Disassembly & Transport Strategy

Quick assembly, efficient packing, and modular transport are **core design drivers**. The PPM must support multiple deployment contexts: standalone operation, stacking, field transport, and storage.

### 2.1 Design Principles
- **Target assembly time:** ◆ <20 minutes from packed storage to operational (with 1 person)
- **Target transport footprint:** ◆ Fits in standard cargo van or AV trailer
- **Tool requirements:** Allen wrench set only (no power tools required for field setup)
- **Disassembly:** Reversible without tool marks or part damage

### 2.2 Modularity Strategy
PPM-S (superstructure) and PPM-B (base platform) separate completely via standardized interface bolts (T-slot compatible). Screen and projector assembly can ship as sub-units.

### 2.3 Hinge & Folding Considerations
- Hinges may be used to reduce transport width (geometry TBD during prototyping)
- Cabling must route through or around hinged sections without stress
- Hinge points must use quick-release or tool-free locking (not permanent bolts)

### 2.4 Stackability
- ◆ If geometry permits, investigate 3-unit stacking (vertical stack, interlocked bases)
- Vertical load limits and stack stability must be validated during prototype phase

---

## 3. System Architecture

The PPM consists of two independent but integrated subsystems:

### 2.1 Prism Superstructure (PPM-S)
- Isosceles triangular prism frame
- Rear-projection screen surface (Face A)
- Projector mounting system (Face B)
- Structural/service face (Face C)

### 2.2 Mobility Base Platform (PPM-B)
- Wheeled transport system
- Leveling / locking mechanism
- Ballast and stability support

The **superstructure must remain structurally stable independent of the base**.

---

## 4. Coordinate System

All measurements and drawings shall follow:

- **X-axis (Lateral):** left ↔ right across screen
- **Y-axis (Depth):** screen → projector
- **Z-axis (Vertical):** floor → ceiling

### Drawing Conventions
- **Plan View:** top-down (bird’s-eye)
- **Section View:** side cut through symmetry axis

---

## 5. Geometric Constraints

### 4.1 Isosceles Prism Requirement
- Plan footprint must be an **isosceles triangle**
- A central **symmetry axis** must be defined
- Screen must be centered on this axis

### 4.2 Projection Alignment
- Projector must be **centered laterally (X = 0)**
- Projection is primarily **top-down (positive Z offset)**

### 4.3 Prism Depth (D)
- Defined as **lens-to-screen distance along optical axis**
- Determined by:
  - screen size
  - projector throw ratio
  - mounting constraints

---

## 6. Face Definitions

### Face A — Screen Face
- Rear-projection surface
- Audience-facing plane
- Mounted within 15-series frame

### Face B — Projector Face
- Opposite Face A
- Contains projector mounting rail and adjustment system
- Provides service access

### Face C — Structural / Service Face
- Provides primary structural bracing
- Supports cable routing and optional device mounting

---

## 7. Optical System Specification

### 6.1 Keystone Policy
- **Vertical keystone correction is permitted**
- Mechanical alignment should minimize correction
- Horizontal keystone should be avoided via centered alignment

### 6.2 Throw Relationship

For planning:

D ≈ TR × W

Where:
- D = throw distance
- TR = throw ratio
- W = image width

UST systems must be evaluated per manufacturer geometry.

### 6.3 Projector Mount Requirements
- Centered mounting point
- Vertical adjustment range (Z)
- Pitch (tilt) adjustment
- Repeatable indexing position

---

## 8. Screen Variants

The PPM supports two **distinct prism frame variants**, each optimized for a different deployment context.

### 8.1 Variant P — Portrait (Height-Dominant)
- **Aspect ratio focus:** 9:16 (portrait/vertical)
- **Application:** Tall, narrow image for audience standing/close viewing
- **Screen geometry:** Taller than wide; minimal masking required
- **Prism footprint:** ◆ Base width and apex angle optimized for portrait content
- **Shared interface:** PPM-B base platform (same mounting footprint)

### 8.2 Variant W — Wide (Width-Dominant / Landscape)
- **Aspect ratio focus:** 16:9 or wider (landscape/horizontal)
- **Application:** Panoramic viewing; wider audience spread
- **Screen geometry:** Wider than tall; bottom masking typical
- **Prism footprint:** ◆ Base width and apex angle optimized for wide content
- **Shared interface:** PPM-B base platform (same mounting footprint)

### 8.3 Variant Strategy
- **Separate SKUs:** P and W are distinct product variants with different frame geometries
- **Shared subsystems:** Both variants use:
  - Same PPM-B (Mobility Base Platform) interface standard
  - Compatible T-slot extrusion profiles (15-series core system)
  - Same projector mount interface (centerline, pitch adjustment)
  - Same optical alignment principles
- **Prototype validation:** Specific prism angles, base widths, and depth values (D) determined during Phase 1 of prototyping
- **Future scaling:** Additional variants (ultra-wide, square, etc.) may be added if BRPS requirements expand

---

## 9. Structural System

### 9.1 Materials

Primary Structure:
- 15-series (1.5") T-slot extrusion

Secondary Structure:
- 10-series (1") extrusion for bracing and accessories

### 9.2 Key Members
- Vertical columns: 15-series
- Top rail: 1530 recommended
- Bottom rail: 15-series
- Internal bracing: 10/15-series hybrid

### 9.3 Transition Interfaces
- Flat plates required between 10-series and 15-series
- Standardized hole patterns required

### 9.4 Fastening
- T-slot nuts and standard bolts
- Through-bolting for critical joints

---

## 10. Projector Mount Assembly

Must provide:
- Centerline alignment
- Adjustable pitch (downward aim)
- Vertical positioning band
- Secure locking after calibration

### Service Requirements
- Accessible controls
- Ventilation clearance
- Cable strain relief

---

## 11. Loudspeaker Integration (Optional)

### 11.1 Mounting Zones
- Screen vertical edges
- Rear/service face
- Top rail

### 11.2 Interface Standard
- VESA 75/100 preferred
- Adapter required for KH-80 (metric to VESA)

### 11.3 Safety
- Tether points required for overhead placement

---

## 12. Mobility Base Platform (PPM-B)

### 12.1 Strategic Purpose
PPM-B provides mobility, leveling, and stability while remaining independent from PPM-S. The base platform must support both wheeled transport and fixed installation modes.

### 12.2 Structural Requirements
- Independent structural frame (does not rely on PPM-S bracing)
- Designed to support full weight of PPM-S when deployed or stacked
- ◆ Load capacity: to be determined after PPM-S final weight estimate
- Footprint: isosceles triangle matching PPM-S base footprint

### 12.3 Caster & Mobility System

**Caster Selection (◆ TBD):**
- Option A: 3-point configuration (asymmetrical triangle - one caster at apex, two at base)
- Option B: 4-point configuration (standard base corners, adjustable)
- ◆ Caster capacity: minimum 2× expected loaded PPM-S weight per caster (safety factor)
- ◆ Caster type: swivel locking casters with brakes (for mobility + stacking stability)
- ◆ Wheel diameter: match to floor conditions and transport environment

**Height Considerations:**
- ◆ Base height to be minimized for transport packing (potential sub-deck storage under PPM-S)
- Service space under screen: confirm clearance for cable routing
- Dead-load height above floor when deployed

### 12.4 Leveling & Locking System

**Parked Configuration:**
- Leveling feet (screw-in jacks) at strategic points on base frame
- Locking mechanism prevents accidental wheel movement when stationary
- Option: footplate with integrated foot levelers (one unified part)

**Caster Braking:**
- Primary: foot-operated brake on each caster or master brake
- Alternative: swivel-lock casters with lever actuation

### 12.5 Interface to PPM-S
- Standardized mounting points: T-slot compatible interface plate
- ◆ Connection method: bolted (quick-release? permanent?) TBD during prototyping
- Alignment pins or bushings to ensure repeatable positioning
- Cable pass-throughs: provision for power, data, and audio routing

### 12.6 Optional: Ballast & Stability
- ◆ Internal ballast considerations if geometry is top-heavy
- Mass distribution within base to improve stability vs. stack-ability
- Anti-tip geometry validation during prototype phase

---

## 13. Hinge & Folding Strategy (Optional Feature)

If transport width is a constraint, hinged folding may be employed. This section defines principles; specific hinge placement is TBD during prototype design.

### 13.1 Hinge Candidates
- **Face C hinges inward:** Reduces lateral width; Face C acts as moving brace
- **Projector mount wing-folds:** Projector bracket folds flat alongside projector face
- **Base platform collapses:** Casters/leveling feet fold or nest

### 13.2 Hinge Design Constraints
- All hinges must support full load of PPM in both open & locked positions
- Hinges require positive locking (not gravity-dependent) to prevent accidental collapse
- Quick-release or tool-free actuation for <2 minute deployment
- Pin diameter, material, and bearing type: ◆ TBD after geometry freeze

### 13.3 Cable Routing Through Hinges
- Cabling must not be stressed by hinge motion
- Options: coiled cable harnesses with generous slack, cable trays that flex with hinges
- Power & data circuits must be isolated from mechanical flex points

### 13.4 Hinge Feasibility
- ◆ Prototype phase will determine if hinges improve transport efficiency
- Fallback: modular disassembly (bolted separation) without hinges

---

## 14. Rotation (Optional Feature)

Two modes:

### 14.1 Assisted Rotation
- Performed via base movement
- Requires indexing and locking

### 14.2 True Axis Rotation
- Requires bearing system
- Requires cable management solution

---

## 15. Transport Configurations

The PPM is designed to support multiple deployment scenarios. Each requires specific setup and footprint planning.

### 15.1 Configuration A: Standalone Operational (Single Unit)
- PPM-S mounted on PPM-B
- All casters locked, leveling feet engaged
- Screen projecting, audio active
- Footprint: ◆ TBD after geometry freeze
- Setup time: <20 minutes

### 15.2 Configuration B: Wheeled Transport
- PPM-S mounted on PPM-B
- Casters unlocked, unit mobile
- Suitable for short-distance repositioning on smooth floors
- Lockout required before projection

### 15.3 Configuration C: Stacked Storage (if feasible)
- ◆ 2–3 units stacked vertically
- Bases interlocked or nested
- PPM-S units transferred to stacking frame or secured atop each other
- Storage footprint: ◆ Single unit footprint × 0.5–0.7 height ratio (goal)
- Requires stability validation in prototype phase

### 15.4 Configuration D: Disassembled Transport
- PPM-S detached from PPM-B
- Screen frame, projector mount, and base transported separately
- Requires careful cable management to avoid tangling
- Reassembly in field (full 20-minute assembly cycle)

### 15.5 Configuration E: Hinged/Folded (if hinges adopted)
- PPM opens from folded "compact" width to operational width
- Brace locks engage; leveling feet deploy
- Transition time: <5 minutes
- Packed width: ◆ TBD (goal: <2 feet if feasible)

---

## 16. Documentation Requirements

Each unit must include:
- Plan drawing
- Section drawing
- Dimensioned geometry
- Parts list
- Mounting details
- Optical setup notes

---

## 17. Open Parameters & Decision Sequence

The following parameters must be locked during prototype phase, in this recommended sequence:

**Phase 1 (Geometry & Optics):**
1. ◆ Screen dimensions (Portrait & Wide variants)
2. ◆ Projector model/class selection (determines throw distance D)
3. ◆ Prism depth finalization (driven by projector throw ratio)

**Phase 2 (Mobility & Transport):**
4. ◆ Caster type & capacity (load testing after PPM-S weight)
5. ◆ Base platform height & footprint
6. ◆ Hinge feasibility decision (fold vs. modular disassembly)
7. ◆ Stackability validation (if pursuing Configuration C)

**Phase 3 (Integration):**
8. ◆ Cable routing strategy (harness lengths, pass-throughs)
9. ◆ Final assembly/disassembly procedure documentation
10. ◆ Assembly time validation (target: <20 min)

**Phase 4 (Configuration Options):**
11. ◆ Rotation requirement (none, assisted, true-axis) → cost/complexity trade-off
12. ◆ Audio integration strategy (mounting zones, cable routing)

---

## 18. Design Philosophy (BRPS Alignment)

The PPM is not a fixed scenic object but a **flexible, deployable media node** within BRPS. Core principles:

- **Modular:** Quick assembly/disassembly without specialized tools
- **Transportable:** Fits standard vehicle; multiple packing configs
- **Repeatable:** Standardized interfaces enable consistent assembly across units
- **Adaptable:** Supports varied spatial layouts, projector types, and audio configurations
- **Layered:** Separates structure (PPM-S), mobility (PPM-B), and media (optics/audio) concerns

The design must be validated through prototype fabrication and operator testing before finalizing engineering specifications.

---

---

**Document Status:** v1.0 (Design Specification — Living Document)
**Last Updated:** February 17, 2026
**Next Review:** Upon completion of prototype phase

**End of Specification v1.0**

