1. 
Exact process of how to compile your source code and build a runnable file
The following steps are no required to use our webapp. Simple navigate to the following link: https://seproject.site:80 to access our webapp. If you are interested 
in running it LOCALLY follow the steps below. 
    a. Open the FP directory and open it in VSCode (code .O) 
    b. Install the following packages :
	github.com/jackc/pgpassfile v1.0.0 
	github.com/jackc/pgservicefile v0.0.0-20221227161230-091c0ba34f0a 
	github.com/jordan-wright/email v4.0.1-0.20210109023952-943e75fe5223+incompatible 
	github.com/ysmood/fetchup v0.2.2 
	github.com/ysmood/goob v0.4.0 
	github.com/ysmood/gson v0.7.3 
	github.com/ysmood/leakless v0.8.0
	golang.org/x/text v0.9.0   
	github.com/alexedwards/scs/v2 v2.5.1
	github.com/go-rod/rod v0.112.9
	github.com/jackc/pgx/v5 v5.3.1
	github.com/julienschmidt/httprouter v1.3.0
	github.com/justinas/alice v1.2.0
	github.com/justinas/nosurf v1.1.1
	golang.org/x/crypto v0.8.0  
  c. Setup a psql DB named OSIPPDB_DSN_DB
  d. install citext
  e. Install the following too: https://github.com/golang-migrate/migrate
  f. migrate -path=./migrations -database=$OSIPPDB_DB_DSN up
  g. run the command go run ./cmd/web
  
describe the allowed values of all parameters that need to be entered while running your program 
  Login Fields, strings 
  Signup Fields, strings
  Form fields stating number, int 
  Form fields not stating number, string 
  comment boxes, string 
 
2.
PDF files containing the entire Report #1 and Report #2 as these were originally sumbitted, not as modified as part of Report #3.
  This is located inside the git repo named as "report 1 and 2.pdf" 

3.
Microsoft PowerPoint files containing slides you used for your first demo and those used for the final demo. 
   This is located inside the git repo named as "sepres1 ppt, sepres2 ppt" 
4. 
PDF file containing the entire Report #3 as in the printed version submitted earlier. The report should appear as a single file. 
   This is licated inside the git repo named as "report 3.pdf"
5. 
Complete project source code. 
   This is located inside the git repo, labeled as the FP directory. 
6. 
Images or button icons loaded by the program when run 
Some Icons are impoted within the html files since we use boostrap icons. Other Images and icons can be found inside the FP directory 
-
|
+----+---FP
     |
     +----+-----ui 
          |
	  +--------+-----static 
                   |
		   +-----------------images 
		   |
		   +-----------------boxicons 
7. 
Shell-scripts, CGI scripts, HTML files, and any and all other files needed to run the program
HTML / TMPL files can be found inside the git repo, directory map can be found below. Scripts are located inside the HTML. 
-
|
+----+---FP
     |
     +----+-----ui 
          |
	  +--------+-----html
8. 
Database tables and files or plain files containing example data to run the program 
We require a DB setup, PSQL and the migrations tool however database files can be found inside FP under "migrations". As stated before in order to satisfy the "no setup needed to run / test requirement" a live demo can be accessed at https://seproject.site:80/.

-
|
+----+---FP
     |
     +----+-----migrations 

9. 
Anything else that your program requires to be run? 
Packages, tools and DBs must be setup to run LOCALLY. In order for the program to be ran without any setup needed we have a live demo at https://seproject.site:80/

10.  


