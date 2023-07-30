This Java program, "TimeConversionByCountry," allows users to convert the current local time to the corresponding time in a different country based on the provided time zones. It begins by taking user input for the local time zone (e.g., "Asia/Kolkata," "America/New_York") and the country's time zone (e.g., "Europe/London," "Asia/Tokyo").

Using the input time zones, the program retrieves the current local time using the LocalDateTime class and the ZoneId of the local time zone. It then converts this local time to the corresponding time in the country's time zone by utilizing the withZoneSameInstant method. This method preserves the instant, only adjusting the time zone, effectively converting the LocalDateTime object to the desired country's time.

The program uses the DateTimeFormatter class to format the LocalDateTime objects into strings with the pattern "yyyy-MM-dd HH:mm:ss". It then prints the converted local and country times along with their respective time zones.
