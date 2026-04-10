# Aluminium Alloy Profile DIN Rail Drop Bracket

The **Aluminium Alloy Profile DIN Rail Drop Bracket** directly tackles advanced CoreXY cooling by providing secure, efficient mounting for enclosures like **Mercury One.1**. This design delivers reduced weight, faster assembly, and easier use.

---

## Technical Overview
* **Compatibility:** Designed specifically for super-lightweight aluminium alloy profiles where the standard `DIN-DropBracket_x4.stl` doesn't fit.
* **Fan Support:** Features a dual **5020 (50mm)** fan mounting system.
* **Mounting Configuration:** Holds two fans in a side-by-side array via a 2-parallel DIN rail configuration.
* **Fastener-Free Design:** Utilizes a high-tolerance friction-fit rail interface and an optional screw-less fan retention system.

---

## Design Optimisations

### 1. Optimised for Lightweight Alloy Profiles
The original DIN brackets are designed for steel rails with thicker tolerances. The v1.03 geometry features a revised contact patch and tensioning curve to ensure a rock-solid mount on lightweight alloys without slipping or rattling.

### 2. Dual-Fan Airflow Plenum
The "Drop" geometry creates a critical offset distance between the DIN rail and the fan intake. This acts as a built-in plenum, reducing air turbulence and enabling fans to push air more efficiently even when mounted against enclosure skirts or cable trunking.

### 3. Advanced Snap Mechanism
The bracket achieves a tight, permanent friction fit through geometric interference, maximizing surface area and eliminating the need for rail-side fasteners.
* **Vibration Resistance:** Minimises vibration-related failure points during high-speed printing.
* **Balanced Mechanical Response:** Variable-thickness sections provide spring tension for a secure "lock" while remaining slideable by hand for alignment.

---

## Material Engineering

### Mandatory Material: PETG
While enclosure parts often use ABS or ASA, this model is **intentionally engineered for PETG**.
* **Mechanical Flexibility:** Relies on the specific elastic modulus of PETG to snap onto rails and grip fans without fatiguing or snapping.
* **Electrical Insulation:** PETG prevents accidental bridging between fan housings and the metal DIN rail—a critical safety feature near live electronics.
* **Durability:** Offers an ideal balance of temperature resistance and toughness.

> ### ⚠ CRITICAL SAFETY WARNING: Avoid PETG-CF
> **PETG-CF (Carbon Fibre-reinforced) is strictly discouraged**.
> * **Conductivity Risk:** Carbon fibres can make the material semi-conductive, risking short-circuits or energising the grounded DIN rail.
> * **Brittleness:** CF reinforcement increases stiffness but reduces tensile strength; locking tabs are likely to snap during installation.

---

## Fitting Instructions

1. **Alignment:** Align the DIN rail to the bracket cutout and use firm strength to push it in slightly (0.5mm).
2. **Seating:** Place the bracket face up on a stable surface. Press down firmly with body weight and rock the rail slightly to assist with insertion until it locks in place.
3. **Optional Screwless Clip:** * Complete steps 1 and 2 with the clip first.
   * Move the clip away from the edge, then install the bracket at the rail's edge.
   * Slide the clip towards the bracket until firmly resting against it.
4. **Fan Installation:** * Route cables through the pre-cut back holes and seat them in the bottom vertical groove.
   * Press the top of the fan against the top recess, then press the bottom in until it clicks.
   * **To remove:** Pull the fan out from the **top** first.

---

## Technical Printing Specs

| Parameter | Specification |
| :--- | :--- |
| **Material** | PETG (Mandatory) |
| **Supports** | None required |
| **Orientation** | **DO NOT** rotate or re-orientate (due to seam placement) |
| **Settings** | Follow Mercury One Documentation |

---

## Change Log

### V1.04 (2026-04-10)
* Increased honeycomb fan grill height for improved laminar flow.
* Increased engrave depth of ZeroG logo.
* Released Screwless Fan Retention Clip.

### V1.03 (Initial Release)
* Addressed micro-tolerances for universal, snug fit across varied fan manufacturers.

---
*Note: No current plan to release a Steel DIN version or STEP files.*
