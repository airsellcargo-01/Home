# Booking vs Shipment SOP

## Purpose
Clarify the distinction between booking updates (FSU BKD) and shipment updates (FWB) in Airsell Cargo operations.

## Booking Data (FSU BKD)
- Represents a booking confirmation, not a shipment.
- Typically created before the Freight Waybill (FWB).
- Contains provisional details (e.g., pieces, weight, routing).

## Shipment Data (FWB)
- Represents the actual shipment tied to a waybill.
- Contains finalized cargo details.
- Used for operational acceptance and regulatory compliance.

## Transition Phase
- FSU BKD creates a Booking Logical Object (LO).
- BookingShipment LO holds provisional parameters (dummy values if needed).
- Linked later to actual shipment data once FWB is issued.

## Future Alignment
- Integrate rich booking data directly from airline booking engines.
- Ensure compatibility with Cargo iQ milestones and IATA ONE Record standards.

## Airsell Cargo Application
- Staff must log booking updates separately from shipment updates.
- SOP checklists updated to reflect this distinction.
- Training modules include EDI message handling and ONE Record compliance.
