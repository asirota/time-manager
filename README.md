# TimeAdder

TimeAdder allows the user to add time to a date. Located in TimeAdder.java, the `AddMinutes` method takes in a time and an integer representing the number of minutes to be added, and returns the new time after adding on the specified minutes. Here is the documentation for each file in this repository.

## TimeAdder.java
TimeAdder.java contains the `AddMinutes` method as well as a `main` function for user input. When the `main` is run, the user is prompted to enter a date in the form of "[H]H:MM {AM|PM}", followed by the number of minutes to be added. `AddMinutes` checks that the user has input valid data, such that the user followed the correct form of the date and entered valid numbers for each entry. If the user does input invalid data, then they are prompted to enter new data until it is deemed to be valid.

### `AddMinutes`
**Inputs:** String holding the time in the form of "[H]H:MM {AM|PM}", and a signed integer holding the number of minutes to be added.

**Outputs:** String holding the new time in the form of "[H]H:MM {AM|PM}".

## TimeAddertest.java
TimeAddertest.java consists of a main function that checks each test case defined in Tests.csv by using an `assert` for each case.

## Testresults.csv
Testresults.csv contains each test case, as well as the corresponding results achieved by `AddMinutes` and the manual calculation.

## blueprint 2.json
blueprint 2.json is an [Integromat](https://integromat.com) scenario that demonstrates equivalent functionality. It is a different approach to accomplishing visually what is normally done in code. 
