# Algorithm: School Attendance Tracking

1. Start.
2. Declare numStudents, totalDays, daysPresent, i (Integer), rate (Real), studentName, status (String), goodCount, riskCount, criticalCount (Integer).
3. Set goodCount, riskCount and criticalCount to 0.
4. Ask for and read numStudents.
5. Ask for and read totalDays.
6. Repeat for i = 1 to numStudents:
   6.1 Ask for and read studentName.
   6.2 Ask for and read daysPresent.
   6.3 Calculate rate = daysPresent * 100 / totalDays.
   6.4 If rate >= 90, set status = "Good" and add 1 to goodCount.
   6.5 Otherwise, if rate >= 75, set status = "At risk" and add 1 to riskCount.
   6.6 Otherwise, set status = "Critical" and add 1 to criticalCount.
   6.7 Display studentName, rate and status.
7. After the loop, display goodCount, riskCount and criticalCount.
8. End.
