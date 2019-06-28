# Domain structural model

## Candidate classes

Selection of candidate objects in the problem domain to be represented as classes based on the noun phrases from the _[Initial problem statement](./initial_problem_statement.md)_.

Table 1. Selection of objects as candidate classes

| Candidate                   | Decision                                                                                       |
| --------------------------- | ---------------------------------------------------------------------------------------------- |
| Absence                     | Keep as _Absence_.                                                                             |
| Activity                    | This is a generic term, so reject.                                                             |
| Analysis                    | Reject, as for activity.                                                                       |
| Annual appraisal            | Keep as _Appraisal_.                                                                           |
| Annual paid holiday         | Keep as _Holiday_.                                                                             |
| Assessment                  | Keep as _Assessment_.                                                                          |
| Assumption                  | Reject, as for activity.                                                                       |
| Audit                       | Reject, as for activity.                                                                       |
| Basic salary                | Since this is just part of what employee is paid as a salary, use as an attribute of _Salary_. |
| Business purpose            | Reject, as for activity.                                                                       |
| Case                        | Reject, as for activity.                                                                       |
| Certification               | Keep as _SicknessCertificate_                                                                  |
| Company                     | Use as an attribute of _ManagingDirector_.                                                     |
| Company pension scheme      | Keep as _PensionScheme_.                                                                       |
| Company policy              | Keep as _Policy_.                                                                              |
| Company's property          | Reject, as for activity.                                                                       |
| Contractual obligation      | Reject, as for activity.                                                                       |
| Control                     | Reject, as for activity.                                                                       |
| Data                        | Reject, as for activity.                                                                       |
| Data record                 | Reject, as for activity.                                                                       |
| Date of return to work      | Use as an attribute of _Absence_.                                                              |
| Department                  | Use as an attribute of _DepartmentHead_.                                                       |
| Department head             | Type of _Manager_, so keep as _DepartmentHead_.                                                |
| Disciplinary action         | Keep as _DisciplinaryAction_.                                                                  |
| Doctor                      | Not part of the domain.                                                                        |
| Duty                        | Reject, as for activity.                                                                       |
| Electronic device           | Reject, as for activity.                                                                       |
| Employee                    | Keep as _Employee_.                                                                            |
| Employee's performance      | Use as an attribute of _Appraisal_.                                                            |
| Employer                    | Use as an attribute of _EmploymentContract_.                                                   |
| Employment                  | Reject, as for activity.                                                                       |
| Employment contract         | Keep as _EmploymentContract_.                                                                  |
| End of probation assessment | Could be a special type of _Assessment_, but since there is no other type, so reject.          |
| Extended probation          | Use as an attribute of _Probation_.                                                            |
| Head of department          | Reject, as synonym for department head.                                                        |
| Hourly rate                 | Use as an attribute of _Salary_.                                                               |
| Human resources             | Reject, as for activity.                                                                       |
| Integrated computer system  | Not part of the domain.                                                                        |
| Laptop                      | Not part of the domain.                                                                        |
| Length of notice            | Use as an attribute of _EmploymentContract_.                                                   |
| Letter of alphabet          | Use as an attribute of _Team_.                                                                 |
| Line manager                | Use as an attribute of _Employee_.                                                             |
| Located                     |                                                                                                |
| Management                  | Reject, as for activity.                                                                       |
| Manager                     | Type of _Employee_, so keep as _Manager_.                                                      |
| Managerial contract         | Keep as _ManagerialContract_.                                                                  |
| Managing director           | Type of _Manager_, so keep as _ManagingDirector_.                                              |
| Means                       |                                                                                                |
| Member of staff             | Synonym for staff member, so reject.                                                           |
| Minimum term of employment  | In this context it is covered by notice, so reject.                                            |
| Mobile phone                | Not part of the domain.                                                                        |
| Model company               | Not part of the domain.                                                                        |
| Next year                   |                                                                                                |
| Notice                      |                                                                                                |
| Number of hours per week    |                                                                                                |
| Objective                   | Use as an attribute of _Appraisal_.                                                            |
| Oneself                     | Reject, as for activity.                                                                       |
| Overtime                    | Use as an attribute of _Salary_.                                                               |
| Part of domain              | Reject, as for activity.                                                                       |
| Party                       | Reject, as for activity.                                                                       |
| Payroll                     |                                                                                                |
| Period                      | Reject, as for activity.                                                                       |
| Period guaranteed by law    | Reject, as for activity.                                                                       |
| Person                      | Keep as _Person_.                                                                              |
| Personal data               | Reject, as for activity.                                                                       |
| Personnel                   | Reject, as for activity.                                                                       |
| Probation                   | Keep as _Probation_.                                                                           |
| Probationary period         | Reject, as synonym for probation.                                                              |
| Process                     | Reject, as for activity.                                                                       |
| Professional development    |                                                                                                |
| Professional training       |                                                                                                |
| Progress                    |                                                                                                |
| Project                     |                                                                                                |
| Prove                       |                                                                                                |
| Quarter                     |                                                                                                |
| Record of devices           |                                                                                                |
| Regular employee            | Synonym for staff member, so reject.                                                           |
| Return                      |                                                                                                |
| Rule                        |                                                                                                |
| Section                     | Use as an attribute of _SectionCoordinator_.                                                   |
| Section coordinator         | Type of _Manager_, so keep as _SectionCoordinator_.                                            |
| Shift allowance             | Use as an attribute of _Salary_.                                                               |
| Sick pay                    | Use as an attribute of _Salary_.                                                               |
| Spreadsheet                 |                                                                                                |
| Staff                       |                                                                                                |
| Staff management            |                                                                                                |
| Staff Management System     |                                                                                                |
| Staff member                | Type of _Employee_, so keep as _StaffMember_.                                                  |
| Subordinate                 | Reject, as for activity.                                                                       |
| System                      |                                                                                                |
| Team                        | Use as an attribute of _StaffMember_ that holds the role of a team leader.                     |
| Team leader                 | A role held by _StaffMember_.                                                                  |
| Time                        | Reject, as for activity.                                                                       |
| Time frame                  |                                                                                                |
| Tool                        | Reject, as for activity.                                                                       |
| Training                    | Keep as _Training_.                                                                            |
| Unique name                 |                                                                                                |
| Work                        | Reject, as for activity.                                                                       |
| Work permit                 | Keep as _WorkPermit_.                                                                          |
