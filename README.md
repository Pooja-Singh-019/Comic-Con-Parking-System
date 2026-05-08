# Comic-Con-Parking-System
This parking system ERD separates vehicles, parking spots, tickets, sessions, and payments into different entities.

A vehicle belongs to a vehicle category and can create multiple parking sessions during an event. Each parking session records the vehicle’s entry time, exit time, assigned parking spot, ticket, and payment. A parking spot belongs to a zone or level and has a spot category, such as car, bike, VIP, or EV. Vehicle categories are matched with compatible spot categories. Payments are linked to parking sessions, while reservations track spots kept aside for specific vehicles or tickets.

This design avoids putting everything into one table and supports re-entry, spot reuse, reservations, availability tracking, and payment history.
