I am using Render's Free Tier PostgreSQL 

When installing strapi, and when it ask for the HOST : 

this is my external databse url , found on render : 
```postgres://doctorappdb_user:edn3y8TldGNG9q0VTTOzpzdqKLtTBlDe@dpg-cpi323ect0pc73flg1b0-a.oregon-postgres.render.com/doctorappdb```

Given the provided External Database URL, you can parse it into the necessary components for the .env file:

DATABASE_HOST: dpg-cpi323ect0pc73flg1b0-a.oregon-postgres.render.com
DATABASE_PORT: The default PostgreSQL port, which is 5432 (since it's not explicitly specified in the URL, we use the default port).
DATABASE_NAME: doctorappdb
DATABASE_USERNAME: doctorappdb_user
DATABASE_PASSWORD: edn3y8TldGNG9q0VTTOzpzdqKLtTBlDe

Images in strapi, were not previewing, see the *middleware.js*

//------------------------------------------------------------------------------------------

goto : ```https://next-appoint-strapi-backend.onrender.com/admin/auth/login```
use "temp" account 