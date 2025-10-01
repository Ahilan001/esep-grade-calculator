# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

IDE Requirement:
GoLand by JetBrains(Recommended)

IDE Set Up: 
1. Follow installation instructions as given and open GoLand.
2. Once GoLand is installed, go to Settings.
3. Look for Go -> GOROOT.
4. In GOROOT, install the latest version of the Go SDK (ex: 1.25.1 in my case)
5. Clone project and open project in the IDE. 

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
