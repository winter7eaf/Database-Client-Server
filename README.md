# Database-Client-Server

Java (IntelliJ IDEA)

May 2022
- Assess JDBC and Java Networks skills

- Implement a Multi Client–Server application using the TCP protocol

- Server replies with the number of albums for that particular artist, until the user types ‘stop'

- The SQL query is an inner join executed on the database

---
For this project, use the ’Music’ database
<br> Import `music_create.sql` first and then import `music_data.sql`
<br> `\i '/your_path/music_create.sql'`
<br> `\i '/your_path/music_data.sql'`

Once imported the tables, you can list them by performing the
following command in PostgreSQL:
<br> `\dt`

---
To kill a port, click stop 'server' in compiler or run `fuser -k  8080/tcp` (replace 8080 with your port number) in the terminal<br>
Use `fuser 8080/tcp` to check if the port is running in your computer.
