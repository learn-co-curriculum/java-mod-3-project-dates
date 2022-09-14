# Project Work Time - Dates

## Learning Goals

- Spend some time working on your project.

## Project Work Time

Now that we have learned a little more about date-time objects in Java, it's
time to apply this new knowledge to our projects!

Modify the `Reservation` class in your project to hold a date-time object of
when the passenger will be flying. Consider the following instructions:

- Modify the `Reservation` class.
  - The class should contain the following properties:
    - Name of the passenger.
    - Name of the airport.
    - Destination city.
    - Date and time of the flight.
      - Example:
        - Name of the passenger: Leslie Knope.
        - Name of the airport: Pawnee Airport.
        - Destination city: Washington DC.
        - Flight date and time: 2022-10-09 09:40
    - Should contain getter and setter methods.
    - Should contain methods to create and cancel a reservation.
- Modify the `AirportReservationDriver` class.
  - Update the method where the user can create a reservation to take in a
    date-time object.
- Tips:
  - The specific format you use to get the date and time of the flight
    reservation does not matter; however, make sure you let the user know what
    format it should be in when you ask for their input.
  - Make sure you validate the date and time that the user enters. It must be
    a real date (i.e., the passenger cannot fly out on September 31st because
    that date does not exist).
  - This should be similar to the Date lab you just completed. Refer to that as
    needed.
  - Refer to the Java documentation as needed. Below are some resources.

## Resources

- [Java 11 Date Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Date.html)
- [Java 11 Calendar Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Calendar.html)
- [Java 11 GregorianCalendar Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/GregorianCalendar.html)
- [Java 11 Month Enum](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/Month.html)
- [Java 11 LocalDate Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/LocalDate.html)
- [Java 11 LocalTime Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/LocalTime.html)
- [Java 11 LocalDateTime Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/LocalDateTime.html)
- [Java 11 DateTimeFormatter Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/format/DateTimeFormatter.html)
- [Java 11 ResolverStyle Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/format/ResolverStyle.html)
- [Java 11 ZoneId Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/ZoneId.html)
- [Java 11 ZonedDateTime Class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/time/ZonedDateTime.html)
