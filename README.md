# Placement Management System

This is a Web-Based Placement Management System using Certificate Authenticator.

## Features
- Student registration (one-time)
- Student profile upload (personal/educational info)
- Placement cell can invite companies for campus interviews
- Companies can filter and view student resumes
- Certificate download for placed students
- Placement scheduling
- Secure login for all users

## Project Structure
- `model/` — POJO (Entity) classes
- `repository/` — Data access layer (Spring Data JPA)
- `service/` — Business logic layer
- `controller/` — REST API endpoints
- `resources/` — Configuration files

## How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/veeresh8088-star/placemet_managament_system_tns.git
   cd placemet_managament_system_tns
   ```
2. **Build the project**
   ```bash
   mvn clean install
   ```
3. **Run the application**
   ```bash
   mvn spring-boot:run
   ```
   Or run `PlacementManagementApplication.java` from an IDE.
4. **Test the API**
   - Use Postman or curl.
   - H2 Console (for dev): `http://localhost:8080/h2-console`

## Example Endpoints
- `/api/user/login` — POST
- `/api/student/register` — POST
- `/api/student/search` — GET
- `/api/placement/schedule` — POST

## Authors
- Group Members: Name, UID, Name, UID...

---

## Next Steps
- Add authentication (JWT)
- Implement certificate upload/download
- Enhance search and filtering
