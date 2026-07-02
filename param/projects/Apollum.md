# Apollum

Built a hospital management system using Spring Boot with a layered architecture showcasing DDD architecture, implementing RESTful APIs for managing patients, doctors, appointments, and analytics. Leveraged Spring Data JPA and Hibernate for persistence, with PostgreSQL as the database. Focused on scalable API design, dynamic querying, and domain-driven data modeling. This was built as part of Coursera's capstone project from [IBM Java Developer Professional Certificate](https://www.coursera.org/professional-certificates/java-developer)

## Concepts I explored
- **Pagination & Sorting**: Implemented pageable APIs to efficiently handle large datasets and improve API performance.
- **Criteria API / Specifications**: Built dynamic and flexible search queries using JPA Specifications and Criteria-based filtering.
- **RESTful API Design**: Designed structured endpoints following REST principles for clean and predictable APIs.
- **Layered Architecture**: Organized code into controllers, services, repositories, and domain models for maintainability.
- **DTO Design (Java Records)**: Used immutable request/response DTOs to decouple API contracts from internal models.
- **Entity Relationship Modeling**: Modeled complex relationships using JPA annotations like OneToMany, ManyToOne, and ManyToMany.
- **ORM (Object Relational Mapping)**: Mapped Java objects to relational tables using Hibernate under JPA.
- **Transaction Management**: Ensured data consistency using @Transactional across service-layer operations.
- **Dynamic Querying & JPQL**: Wrote custom queries and projections for optimized data retrieval and analytics.
- **UUID-based Primary Keys**: Used UUIDs for scalable and distributed-friendly entity identification.
- **Indexing & Constraints**: Applied unique constraints and indexing strategies for performance and data integrity.
- **Lazy Loading & Cascading**: Optimized entity loading and managed relationships using cascade and fetch strategies.
- **Global Exception Handling**: Implemented centralized error handling using ProblemDetail for consistent API responses.
- **API Documentation (Swagger/OpenAPI)**: Documented APIs for easier testing and integration using OpenAPI tools.
- **Integration Testing**: Validated persistence and repository behavior using Spring Boot test configurations.
- **Analytics & Aggregation Queries**: Built dashboard-ready endpoints using aggregation queries and projections.
- **Enum Handling in Persistence**: Stored enums using EnumType.STRING for readability and maintainability.


**GitHub URL**: https://github.com/btwparam/apollum.git