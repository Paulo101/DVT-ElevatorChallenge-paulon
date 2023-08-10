# DVT-ElevatorChallenge-paulon

## Running the App

Please go to ElevatorChallengeDVT\ElevatorChallengeDVT\bin\Debug\net6.0
Locate the ElevatorChallengeDVT.exe file, attempt to run it (you may be prevented by security majors

alternatively
  Open the .snl using visual studio


## About the App

The challenge was completed using Visual Studio 2022
It is fully written in C# .NET 6.0

## File Structure

-- ElevatorChallengeDVT
   -- Tests
      --- ElevatorSystemUnitTests.cs (This file contains NUnit Tests Logic)
   -- Program.cs (This is the entry point of the app, contains logic for running the console app and prompting the user)

-- ElevatorLibrary (This dir is a class library that contains all the Object Orianted clasess and interfaces)
  -- Classes
     -- Elevator.cs (inherits IElevator)
     -- ElevatorSystem.cs (inherits IElevatorysystem)
  -- Interfaces
     -- IElevator.cs
     -- IElevatorysystem.cs


You may open the app using the ElevatorChallengeDVT.sln file (on visual studio).
Alternatively, you may be able to view all the code using vs code or any other code editor.

## Credits

https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit
https://codereview.stackexchange.com/questions/161431/elevator-interview-problem-oop

## Contact
--- Paulo (ngoveps@outlook.com)
