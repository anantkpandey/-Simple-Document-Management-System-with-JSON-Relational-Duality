# Simple Document Management System with JSON Relational Duality
# Concept: 
- A basic system to upload, store, and retrieve documents. Leveraging Oracle's JSON Relational Duality views to interact with document data both as relational tables and JSON documents.
# Java 24 Features:
- Unnamed Variables & Patterns: Used for cleaner code in loops or when handling data structures.
- String Templates: For constructing dynamic SQL queries or JSON strings more readably.
# Oracle Database 23ai Features:
- JSON Relational Duality Views: The core feature. Defined views that allowed to query and manipulate document data stored in JSON columns as if they were relational tables, and vice versa. This allows for flexible data access.
- JSON Schema Validation: Implemented validation rules for JSON documents within the database.
# Functionality:
- Upload documents (store metadata in relational columns, content as JSON).
- List documents with basic metadata.
- Retrieve a document by ID (retrieve both metadata and JSON content).
- Search documents based on metadata fields (using standard SQL).
- Potentially explore querying within the JSON content using JSON path expressions through the duality view.
