# FieldFix — Field Service Management on Microsoft Power Platform

A complete field service management solution built on Microsoft Power Platform,
developed as a hands-on portfolio project while studying for the PL-200
(Power Platform Functional Consultant) certification.

## What it does
FieldFix manages the full lifecycle of field service operations for an HVAC/electrical
service company — customers, sites, service requests, work orders, technicians,
equipment, and parts.

## Tech stack
- Microsoft Dataverse (data platform)
- Power Apps — Model-driven app (dispatcher back-office)
- Power Apps — Canvas app (technician mobile) — in progress
- Power Pages (customer self-service portal) — in progress
- Power Automate (process automation) — in progress

## Data model
7 custom tables with 1:N and N:N relationships:
Customer, Site, Service Request, Work Order, Technician, Equipment, Part.

## Key features demonstrated
- Custom Dataverse tables and columns (including formula and rollup columns)
- Table relationships with parental and referential cascade behaviors
- Business rules (conditional field requirements based on priority)
- Role-based security (Dispatcher, Technician, Manager) with business units
- Column-level security, auditing, and duplicate detection
- Model-driven app: custom forms with tabs/sections, quick views, subgrids,
  timeline, views with dynamic date filters, charts, dashboards, and a custom page

## How to deploy
Import the unmanaged solution from the `/solutions` folder into any Dataverse environment
(make.powerapps.com → Solutions → Import).

## About
Built by Akshay Sharma as a portfolio project demonstrating Power Platform
functional consulting skills.
