### The Timesheet Application was created by the following team members:

Ashuashenafi Maru
Bilen Worku
Kim Levin

#### Division of Work
Ashuashenafi Maru - Security, index.html, login.html
Bilen Worku - Controller, timesheet.html, registration.html
Kim Levin - Database, base.html, list.html - Project Manager

Table Names:

#### Employee
Long Id
String username
String lastName
String firstName
String email
Address address - optional
Double payrate
Manager manager
Set<TimeSheet> timesheets

#### Manager
Long Id
Set<Employee> teamMembers

#### Timesheet
Id 
String dayOfWeek
Date TimeIn
Date TimeOut
Double regularPay
Double regOT
Double holiday
Double holidayPay
Double holidayOT
Double leaveNoPay
Double compTimeEarned
Double compTimeUsed
Double annualLeave
Integer rejectCode
String rejectMsg
Boolean enabled
Employee employee
Boolean approved 

#### Role
Id
String name
Set<Employee> employees
  
#### Pages

index.html
login.html
timesheet.html
registration.html
base.html
list.html
