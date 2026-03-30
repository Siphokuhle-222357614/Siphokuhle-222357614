# Agile Logbook – TymelessTyre

This logbook documents the Agile (Scrum) process followed during the development of TymelessTyre. It includes sprint goals, task boards, daily stand-up notes, and retrospectives.

---

## Sprint 1: Backend Foundation
**Dates:** [01–14 July 2025]

### Goal
Set up the Spring Boot backend, design the database schema, and implement basic CRUD for tyre inventory.

### Task Board
| Backlog | In Progress | Completed |
|---------|-------------|-----------|
| User authentication (JWT) | Database schema design | Spring Boot project setup |
| Appointment CRUD | Tyre entity mapping | Tyre CRUD endpoints |
| Sales reporting | - | MySQL configuration |

### Daily Stand-up Log
| Day | What I completed | What I plan to complete next | Impediments / Blockers |
|-----|------------------|------------------------------|------------------------|
| 1 | Created repository, initialized Spring Boot, added dependencies. | Design JPA entities. | None |
| 2 | Designed `Tyre`, `User`, `Appointment` entities. | Implement `TyreRepository` and service. | None |
| 3 | Implemented `TyreService` and REST controller for tyres. | Write unit tests for service layer. | Need to set up test database. |
| 4 | Wrote unit tests for `TyreService`. | Set up MySQL connection and test endpoints. | None |
| 5 | Configured MySQL, tested all tyre endpoints. | Start JWT authentication. | None |
| 6 | Added Spring Security dependency, configured basic JWT. | Implement login endpoint and token generation. | Need to understand JWT filter chain. |
| 7 | Completed login endpoint, returns JWT. | Secure tyre endpoints with role-based access. | None |

### Sprint Retrospective
**What went well:**  
- Clear requirements allowed us to complete the core CRUD quickly.  
- JPA mapping was straightforward.  

**What could be improved:**  
- Tests were written after the code – should have been test-driven from the start.  
- No CI/CD setup; manual testing was time-consuming.  

**Action items for next sprint:**  
- Write service tests before implementing controllers.  
- Set up GitHub Actions for basic build verification.  
- Secure endpoints with proper role annotations.

---

## Sprint 2: Frontend Setup & Tyre Listing
**Dates:** [e.g., 15–28 August 2025]

### Goal
Create a Vue.js frontend that can fetch and display tyre data from the backend.

### Task Board
| Backlog | In Progress | Completed |
|---------|-------------|-----------|
| Appointment UI | Vue project scaffolding | Vue project setup |
| User authentication UI | Axios configuration | Tyre listing page |
| Form for adding/editing tyres | - | API service module |

### Daily Stand-up Log
| Day | What I completed | What I plan to complete next | Impediments / Blockers |
|-----|------------------|------------------------------|------------------------|
| 8 | Created Vue project with Vue CLI, installed Vue Router, Axios. | Set up Axios base configuration. | None |
| 9 | Configured Axios with base URL, created `api.js`. | Create TyreList component. | CORS error – backend not allowing frontend origin. |
| 10 | Added CORS configuration in Spring Boot. | Fetch and display tyres in table. | None after CORS fix. |
| 11 | Built TyreList component with v-for and computed properties. | Add loading state and error handling. | None |
| 12 | Added loading spinner and error alert. | Create TyreForm component for add/edit. | None |
| 13 | Built TyreForm with v-model, validation. | Integrate TyreForm with backend POST/PUT. | None |
| 14 | Completed add/edit functionality, updated list after mutation. | Start styling with CSS. | None |

### Sprint Retrospective
**What went well:**  
- Vue's reactive system made UI updates seamless.  
- Axios interceptors simplified request/response handling.  

**What could be improved:**  
- More consistent use of Vuex/Pinia for state management; local state became messy.  
- Environment variables for API URL not yet used.  

**Action items for next sprint:**  
- Introduce Pinia for global state (user, notifications).  
- Use `.env` files for configuration.  
- Write unit tests for Vue components.

---

## Sprint 3: Authentication & User Management
**Dates:** [29 August – 11 September 2025]

### Goal
Implement user login, JWT storage, and protect routes based on roles.

### Task Board
| Backlog | In Progress | Completed |
|---------|-------------|-----------|
| Appointment UI | Login page component | JWT backend (already done) |
| Sales reporting | Pinia store for auth | Login form |
| - | Route guards | Token storage in localStorage |

### Daily Stand-up Log
| Day | What I completed | What I plan to complete next | Impediments / Blockers |
|-----|------------------|------------------------------|------------------------|
| 15 | Created Pinia store for auth, defined state and actions. | Build login page component. | None |
| 16 | Built LoginView with form, calls login API. | Store token in localStorage and redirect. | None |
| 17 | Implemented token storage, added axios interceptor to attach token. | Create protected routes with Vue Router guards. | None |
| 18 | Added route guards, redirect unauthenticated users to login. | Add role-based access to routes. | None |
| 19 | Implemented role checks (admin, staff) in route meta. | Test protected routes with different tokens. | None |
| 20 | Fixed token refresh logic. | Add logout functionality. | None |
| 21 | Added logout, clear store and localStorage. | Start building appointment module. | None |

### Sprint Retrospective
**What went well:**  
- Pinia store simplified auth state management.  
- Route guards worked smoothly.  

**What could be improved:**  
- Token expiration handling could be more user-friendly.  
- Need to handle 401 responses globally (auto logout).  

**Action items for next sprint:**  
- Add global axios response interceptor to handle 401.  
- Write more robust error messages.  
- Begin work on appointment UI.

---

## Sprint 4: Appointment Management (Ongoing / Planned)
**Dates:** [e.g., 12–25 September 2025]

### Goal
Add appointment scheduling functionality for customers and staff.

---

## Overall Reflections

Throughout the project, I learned to apply Agile principles: iterative development, daily stand-ups, and sprint retrospectives. This approach helped me adapt to changing requirements and catch issues early. The combination of Spring Boot and Vue.js proved effective for building a full-stack application with a clear separation of concerns.

*This logbook will be updated as development continues.*
