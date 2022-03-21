# gh-dashboard

A clean reimplementation of the ucsb-cs-github-linker using:
* React frontend
* Restful API backend (implemented for now in Spring Boot)

# Roadmap

* Implement GitHub OAuth
* Initial admins from configuration
* Designate any user as admin or instructor
* Create a course and link it to a GitHub organization
* Upload a course roster
  - Required: first name, last name, studnet id, student email
  - Optional: github id, section
* Ability to add any user to a course as an instructor, TA, or student.

* Ability to define teams; initially just team name.
* Ability to two-way sync teams with Github 
  - teams on GitHub that are not defined in linker are added to the linker
  - teams on linker that are not defined in GitHub are added to GitHub
  - initially this is just team names
* Add ability to upload CSV roster to put students on teams, using student ids or student emails as keys
* Update two way team sync to sync team memberships.

