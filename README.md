# FastAPI

Created Fast API application. The API will provide functionalities for CRUD (Create, Read, Update, Delete) operations for managing configurations.

Utilize PostgreSQL as the relational database management system. (Ypu can do it by creating a database on postgres and connecting it to the code.)
Employed SQLAlchemy as the Object-Relational Mapper (ORM) to interact with the database in a Pythonic way.
Also included SQLAlchemy models for above requirements
Designed FastAPI endpoints for CRUD operations on both Book and Category entities
Employed Pydantic data models (schemas) to define the request and response data structures for each endpoint, ensuring data validation and type safety.
Implemented comprehensive error handling using FastAPI's built-in exception handling mechanisms. This should include handling potential database errors, validation errors, and other application-specific exceptions.
