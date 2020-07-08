# (PROPOSED) DECISIONS

## Service credits still necessary in ecosystem?
[Related Issue 9](https://github.com/stichtingsem/functional-overview/issues/9)

Service credits will **not** be necessary in the new ecosystem. The functionality of service credits will be replaced by entitlements. If there is **no** entitlement or the quantity of the entitlement is **not** sufficient there will be **no** access for the user.

## Is entitlement sufficient?
[Related Issue 10](https://github.com/stichtingsem/functional-overview/issues/10)

Entitlements will ensure access and guarantee valid and transparent transactions

1. Entitlement will be established on the highest possible level
  - Secondary Education: School level
  - Vocational education: User level
2. Entitlements should be established upfront and can be realized (near) real time to ensure access for users
3. Data for entitlement
  - Secondary Education
     - Required 
        - Sales Agent
        - School
        - Product (EAN)
        - Quantity
          - Quantity is conditional for balancing administrations within in the Ecosystem
        - Validity Period
     - Optional
        - Start date
  - Vocational Education
     - Required   
        - Sales Agent
        - User
        - Product
        - Validity Period
     - Optional
        - Start date
4. Explanation
  - Secondary Education: Entitlement is comparable with specification on organisation level
  - Vocational Education: Entitlement is comparable with specification on user level

Entitlement will be **sufficient** to ensure valid and transparent transactions

## Blended learning as base design criteria
[Related Issue 11](https://github.com/stichtingsem/functional-overview/issues/11)

- Blended learning (Combi's/LiFo) is just like (full) digital and folio products in scope of this pilot and therefore are part of the (base) design criteria
- Blended learning asks for additional requirements to partners in the ecosystem:
  - Flexibility in delivery
    - Digital components are (near) real time accessible
    - Shortage of folio components can't block the access to digital components
  - Blended learning materials (combi’s/LiFo) remain one product number (EAN)
  - Entitlements (digital) and purchase orders (folio) need to be synced periodic
  - Entitlement ensures access for users
  - Entitlement guarantees transactions for partners

## Revenue recognition
[Related issue 12](https://github.com/stichtingsem/functional-overview/issues/12)

[Related issue 13](https://github.com/stichtingsem/functional-overview/issues/13)

Revenue recognition is influenced by tax legislation, competitive propositions and commercial contracts/agreements. Partners in the ecosystem should determine their own approach to revenue recognition, but the services should ensure valid & transparent transactions and enable various transaction models

## Identity
[Related Issue 14](https://github.com/stichtingsem/functional-overview/issues/14)

- Product: EAN
- User: ECK-ID
- School: Digi Delivery ID (RIO will be evaluated on applicability)

## Bring SIS (LAS) and LML in sync
[Related issue 15](https://github.com/stichtingsem/functional-overview/issues/15)

SIS (LMS) data will be synced with LML

Boundaries:
- Target binding based on role
- School is in control of the accessibility to the entities/data within SIS

Preparation phase:
- Subjects
- Courses

Execution phase:
- Forecast (base for entitlement)

## First Time Right
[Related Issue 16](https://github.com/stichtingsem/functional-overview/issues/16)

First Time Right will **not** be a principle, but there are (additional) requirements:
- Avoidance of errors and repairs
    - Determine when data is up to date and ready for use (data quality)
- Updates (LML) will be shared (near) real time
    - It is a dynamic process and updates will prevent errors (and repairs)
    
## In Scope POC
[Related Issue 17](https://github.com/stichtingsem/functional-overview/issues/17)

### In Scope:
- VO (secondary) and MBO (vocational)
- Full Digital (100% digital)
- Blended (combi’s, LiFo)
- Folio (incl. paper vouchers)
    - Partners (SA, MP) within the eco-system have to evaluate the impact of the proposed solutions on their supply chain (forecasts/prognosis, purchase, stock, etc)
- ECK

[Related Issue 18](https://github.com/stichtingsem/functional-overview/issues/18)

### Out of scope (for now):
- Setup & Support
    - Most important next step in the SEM pilot
    - More decentralization asks for higher maturity level regarding to maintenance and fixation of stem data and identity 
      - How to guard data quality?
- Communication 
- School processes / administration (SIS, ELO, IDP)
    - Not enrolled students (0e Jaars)
- Teacher licenses (including trial licenses)
    - Additional services for teachers > prepare access locations for teacher licenses
- Kennisnet ARP administration
- Progress & Results (Part of Use Case 4.0)
- Data covenant 
- Non happy flows
- Returns
    - Return reasons: Changes LML (school), Mutations SIS (change of subjects, OKO
- NON ECK

## What is Fulfilment Update LMS
[Related Issue 19](https://github.com/stichtingsem/functional-overview/issues/19)

Update contains contains information about order confirmations, forecasts and availability

## Usage Information blended learning
[Related Issue](https://github.com/stichtingsem/functional-overview/issues/20)

Usage information blended learning (combi's, LiFo) will be shared to the market place
