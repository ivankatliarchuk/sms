# Domain structural model

## Candidate classes

Table 1. Tangible objects as candidate classes

| Candidate          | Represent as class?                                                                |
| ------------------ | ---------------------------------------------------------------------------------- |
| Electronic devices | No. May record as an attribute, so to known whether the employee should have some. |
| Laptop             | No. Similar argument to that of electronic devices.                                |
| Mobile phone       | No. Similar argument to that of electronic devices.                                |
| Devices            | No. Synonym for electronic devices.                                                |
| Computer system    | Not part of the domain.                                                            |

Table 2. Roles as candidate classes

| Candidate              | Represent as class?                                     |
| ---------------------- | ------------------------------------------------------- |
| Member of staff        | Yes. Specialisation of _Employee_.                      |
| Person                 | No. Synonym for employee.                               |
| Head of the department | No. Should be recorded as an attribute.                 |
| Section coordinator    | No. Similar argument to that of head of the department. |
| Team leader            | No. Similar argument to that of head of the department. |
| Managing director      | No. Similar argument to that of head of the department. |
| Employee               | Yes.                                                    |
| Employer               | No. Synonym for company.                                |
| Doctor                 | Not part of the domain.                                 |
| Line manager           | No. Similar argument to that of head of the department. |
| Manager                | Yes. Specialisation of _Employee_.                      |
| Subordinate            | No. Synonym of member of staff.                         |
