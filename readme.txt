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
  This is located inside the gitrepo under FP 
    


