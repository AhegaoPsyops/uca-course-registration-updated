List of Changes: 
  Model Implementation: 
    Changed the class and course classes to records to fit with domain structure. 
    Added interfaces for StudentRepository, CourseRepository, and EnrollmentRepository
  Cleanup: 
    Minor cleanup in logic of menu and saving. 
    For Enrollment and dropping, does error checking for Student ID, adds to existing CourseID error checing, and avoids errors with empty CSVs when attempting to enroll/drop when there are no classes or students. 
    
