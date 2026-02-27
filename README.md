# si_le04_ex06_rest_endpoint_naming
[exercise description](https://github.com/arturomorarioja-ek/SD_System_Integration_F2026/blob/main/Lesson04/06%20REST%20API%20endpoint%20naming.md)


| **Verb**      | **Path**      |   **Notes**    |
| :------------- | :------------- | :------------- |
| GET | /cvs{?last-name, language} | Full list of CVs or a collection of CVs by Language or Last Name |
| POST | /cvs | Create a new CV. CV in Request Body |
| GET | /cvs/{cvId} | Get a full CV |
| PUT | /csv/{cvId} | Replace an entire CV |
| PATCH | /csv/{cvId} | Partially update a CV |
| DELETE | /csv/{cvId} | Delete a CV |
| GET | /csv/{cvId}/personal-information | Get personal information for a CV |
| PUT | /csv/{cvId}/personal-information | Replace personal information for a CV |
| PATCH | /csv/{cvId}/personal-information | Partially update personal information for a CV |
| GET | /cvs/{cvId}/picture-file-name | Retrieve the picture file name for a CV |
| PATCH | /cvs/{cvId}/picture-file-name | Update the picture file name for a CV |
| GET | /cvs/{cvId}/degrees | Get all degrees for a CV |
| POST | /cvs/{cvId}/degrees | Add a new degree to a CV. Degree in Request Body|
| GET | /cvs/{cvId}/degrees/{degreeId} | Get one degree for a CV |
| PUT | /cvs/{cvId}/degrees/{degreeId} | Replace a degree in a CV |
| DELETE | /cvs/{cvId}/degrees/{degreeId} | Delete a degree in a CV |
| POST | /auth/sessions | User Login. Username and Password in Request Body |
| DELETE | /auth/sessions | User Logout. Bearer token in Authorization Header |

