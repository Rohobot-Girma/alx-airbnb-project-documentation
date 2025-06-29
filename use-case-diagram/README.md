# Use Case Diagram - Airbnb Clone Backend

## Overview
This use case diagram visualizes the interactions between different actors (users) and the Airbnb Clone backend system, showing all the key functionalities and how users interact with them.

## Actors Identified

### Primary Actors
1. **Guest** - Users who book properties
2. **Host** - Users who list and manage properties
3. **Admin** - System administrators who manage the platform

### Secondary Actors
1. **Payment Gateway** - External payment processing system
2. **Email Service** - External email notification service
3. **File Storage** - External cloud storage for images

## Use Cases

### Guest Use Cases
- **Register Account** - Create a new guest account
- **Login** - Authenticate into the system
- **Search Properties** - Find available properties
- **Filter Properties** - Apply filters (price, location, amenities)
- **View Property Details** - See comprehensive property information
- **Book Property** - Reserve a property for specific dates
- **Make Payment** - Pay for the booking
- **Cancel Booking** - Cancel an existing booking
- **Write Review** - Leave review and rating after stay
- **Update Profile** - Modify personal information
- **View Booking History** - See past and current bookings

### Host Use Cases
- **Register Account** - Create a new host account
- **Login** - Authenticate into the system
- **Create Listing** - Add a new property listing
- **Edit Listing** - Modify existing property details
- **Delete Listing** - Remove property from platform
- **Manage Bookings** - View and respond to booking requests
- **Set Availability** - Update property availability calendar
- **Receive Payments** - Get paid for completed bookings
- **Respond to Reviews** - Reply to guest reviews
- **Update Profile** - Modify host profile information

### Admin Use Cases
- **Manage Users** - Monitor and manage user accounts
- **Monitor Listings** - Oversee property listings
- **Track Bookings** - Monitor all booking activities
- **View Analytics** - Access platform usage statistics
- **Handle Disputes** - Resolve conflicts between users
- **System Maintenance** - Perform system updates and maintenance

### System Use Cases
- **Send Notifications** - Automatically send email/in-app notifications
- **Process Payments** - Handle payment transactions
- **Validate Bookings** - Check for double bookings and conflicts
- **Generate Reports** - Create system reports and analytics
- **Backup Data** - Perform regular data backups

## Relationships
- **Include Relationships**: Show when one use case includes another
- **Extend Relationships**: Show optional extensions to use cases
- **Association Lines**: Connect actors to their relevant use cases

## Diagram Structure
The use case diagram should be organized with:
- Actors on the left and right sides
- Use cases in the center, grouped by functionality
- Clear boundaries showing system scope
- Proper notation for include/extend relationships

This diagram provides a comprehensive view of all system interactions and helps developers understand the complete scope of the Airbnb Clone backend. 