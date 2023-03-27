# Enviornmental Variable 


1. Create a file at the root of the project 

.env

2. Inside the .env file add the text: 
- you must use `NEXT_PUBLIC` or else this wont work 

NEXT_PUBLIC_TITLE = "Digital Design and Development" 

3. On the page, in between the export and return write the variable: 
```
var title = process.env.NEXT_PUBLIC_TITLE; 
```

4. Then in between the main write 

```

{title}

```

5. make sure the `.gitignore` file has the `.env` inside 
- you want to prevent this secrete title to be shown 

## BCIT data from Digital Design and Development 
[Digital Design and Devlopment Diploma Course] 
(https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/#courses)


