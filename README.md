# FlightPulse-Airline

Project Description:

A FlightPulse, a highly efficient and reliable Backend Application responsible for seamlessly managing multiple facets of flight operations, including flight management, booking systems, real-time notifications, and secure payment processing. It incorporates a Microservice MVC architecture, which guarantees both scalability and availability of the system.

Non-Functional Requirements:
1. To prevent conflicts and inconsistencies, the application incorporates Transaction Isolation Level, which ensures that no two users can simultaneously book the same seat.
2. To avoid unintended consequences and accidental duplicate calls during the payment process, the payment gateway implements Idempotency APIs.

High Level Design : https://asset.cloudinary.com/de8cqi7gx/f5d097ebf8878687ca4c3ca73de9c3a2


DIFFERENT MICROSERVICE:
1. FligthAndSearchService:https://github.com/sanjay-09/FlightsAndSearchRepository
2. AuthService:https://github.com/sanjay-09/Auth_Service
3. BookingService:https://github.com/sanjay-09/Booking-Service
4. ReminderService:https://github.com/sanjay-09/ReminderService1
5. API Gateway:https://github.com/sanjay-09/API_Gateway



