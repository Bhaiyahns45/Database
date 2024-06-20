## PostgreSQL-Commands

---

To take/export the dump of database

    pg_dump -U postgres -h localhost -F c -b -v -f "C:\Users\bhaiya\Downloads\file_name.dump" db_name

To load/import the dump to database

    pg_restore -U postgres -d db_name "C:\Users\bhaiya\Downloads\file_name.dump"

    

    
