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
| Company                     | Not part of the domain.                                                                        |
| Company pension scheme      | Keep as _PensionScheme_.                                                                       |
| Company policy              | Keep as _Policy_.                                                                              |
| Company's property          | Reject, as for activity.                                                                       |
| Contractual obligation      | Reject, as for activity.                                                                       |
| Control                     | Reject, as for activity.                                                                       |
| Data                        | Reject, as for activity.                                                                       |
| Data record                 | Reject, as for activity.                                                                       |
| Date of return to work      | Use as an attribute of _Absence_.                                                              |
| Department                  | Use as an attribute of _Employee_.                                                             |
| Department head             | Type of _Employee_, so keep as _DepartmentHead_.                                               |
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
| Line manager                |                                                                                                |
| Located                     |                                                                                                |
| Management                  |                                                                                                |
| Manager                     |                                                                                                |
| Managerial contract         |                                                                                                |
| Managing director           |                                                                                                |
| Means                       |                                                                                                |
| Member of staff             |                                                                                                |
| Minimum term of employment  |                                                                                                |
| Mobile phone                |                                                                                                |
| Model company               |                                                                                                |
| Next year                   |                                                                                                |
| Notice                      |                                                                                                |
| Number of hours per week    |                                                                                                |
| Objective                   | Use as an attribute of _Appraisal_.                                                            |
| Oneself                     |                                                                                                |
| Overtime                    | Use as an attribute of _Salary_.                                                               |
| Part of domain              |                                                                                                |
| Party                       |                                                                                                |
| Payroll                     |                                                                                                |
| Period                      |                                                                                                |
| Period guaranteed by law    |                                                                                                |
| Person                      |                                                                                                |
| Personal data               |                                                                                                |
| Personnel                   |                                                                                                |
| Probation                   | Keep as _Probation_.                                                                           |
| Probationary period         | Reject, as synonym for probation.                                                              |
| Process                     |                                                                                                |
| Professional development    |                                                                                                |
| Professional training       |                                                                                                |
| Progress                    |                                                                                                |
| Project                     |                                                                                                |
| Prove                       |                                                                                                |
| Quarter                     |                                                                                                |
| Record of devices           |                                                                                                |
| Regular employee            |                                                                                                |
| Return                      |                                                                                                |
| Rule                        |                                                                                                |
| Section                     |                                                                                                |
| Section coordinator         | Type of _Employee_, so keep as _SectionCoordinator_.                                           |
| Shift allowance             | Use as an attribute of _Salary_.                                                               |
| Sick pay                    |                                                                                                |
| Spreadsheet                 |                                                                                                |
| Staff                       |                                                                                                |
| Staff management            |                                                                                                |
| Staff Management System     |                                                                                                |
| Staff member                | Type of _Employee_, so keep as _StaffMember_.                                                  |
| Subordinate                 |                                                                                                |
| System                      |                                                                                                |
| System                      |                                                                                                |
| Team                        | Use as an attribute of _Employee_.                                                             |
| Team leader                 | Type of _Employee_, so keep as _TeamLeader_.                                                   |
| Time                        |                                                                                                |
| Time frame                  |                                                                                                |
| Tool                        |                                                                                                |
| Training                    |                                                                                                |
| Unique name                 |                                                                                                |
| Work                        |                                                                                                |
| Work permit                 |                                                                                                |
