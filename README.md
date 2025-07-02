# Complaint Dashboard – Salesforce LWC Project

A Lightning Web Component (LWC)-based Complaint Ticket Dashboard with update actions and ticket history.

## 🎯 Features
- Dashboard view of tickets (fields: Priority, Module, Location, Status, SLA Time, Ageing)
- Buttons for "Update Ticket" and "View History"
- Modal popup for updating complaints
- Dynamic Apex-driven data fetching
- Statuses: In Progress, Approved Required, Forward, More Info, On Hold, Resolved
- Priorities: Low, Medium, High
- Resolver Teams: Level One, Level Two

## 🧱 Components
- `<c-ticketDashboardWrapper>`: Wraps view and modals
- `<c-dashboardView>`: Main dashboard table UI
- `<c-updateTicketForm>`: Form for inline ticket updates
- `<c-ticketHistoryModal>`: Shows all ticket update records

## 🔌 Apex Integration
- Get ticket records
- Update ticket status
- Fetch ticket transaction history

## 📸 Screenshots
![Dashboard](screenshots/dashboard_view.png)
![Update Modal](screenshots/update_modal.png)

## 💡 Technologies Used
- Apex
- LWC
- Lightning App Builder
- SOQL
- Custom Metadata

## 📜 Trailhead Profile
[Visit My Trailhead Profile](https://www.salesforce.com/trailblazer/rmane70)
