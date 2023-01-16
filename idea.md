# GUI
let's create a CLI application first
[ ] preview scripts with filled in properties connection string, database name etc.
# CLI
## Programming Language
Let's stick to C# or Python (Rust? F#?)
## Functions / Methods
- [ ] connect to own config-database (MS SQL)
- [ ] connect to different Server
- [ ] create schema from remote server
- [ ] create a new database on remote server 
- [ ] create tables on remote server (procedures, functions, views, triggers, constraints, user types etc.) let's create those scripts by mssql tools
- [ ] fill data from source to new database -> this can be used to create a test database
- [ ] apply data type transformations
- [ ] performance tools (insert, update, select, delete) before, after data type conversion
- [ ] group databases together so that we can create ickv_21c, ickv_21c_xxx, digigs_xxx, 21c_iskv_xxx, 21c_iskv_xxx_temp (we probably need 2 strings here)
# Database
## Tables
- [ ] Connection Strings
- [ ] Connection String Alias
- [ ] Procedures with dynamic SQL for data transfer?