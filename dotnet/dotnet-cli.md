
# Creational

Console: `dotnet new console -n MyProject`

NUnit project: `dotnet new nunit -n MyNunitProject`

Solution: `dotnet new sln --name MySolution`

# Build
`dotnet build`
`dotnet run`

# Test
`dotnet test -- NUnit.NumberOfTestWorkers=5`

Run subset of Tests: `dotnet test --filter Name~TestMethod1`

[Run selected unit tests
](https://docs.microsoft.com/en-us/dotnet/core/testing/selective-unit-tests?pivots=nunit)