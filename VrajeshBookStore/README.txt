2023-10-31
0844
created a new project and to individual account and tested the application
0845
added READ.md and README.txt file 
0847
removed this line from startup.cs (options => options.SignIn.RequireConfirmedAccount = true)
0849
added breakpoint in HomeController.cs on line 22 and 27 for home and privacy page.
0850
selected Darkley and downloaded theme from bootswatch.com
0852
renamed the old bootstrap with the name of bootstrap_old.css and added the new bootstrap.css 
0854
changed the existing site.css with given styles.
0855
removed .min from layout.cshtml from line 7, made changes in nav-light to nav-dark and 
bg-light to bg-primary on line 12 in layout.cshtml, removed text dark from line 22 and 25 
from layout.cshtml, changed line 39 text-muted to text-white-50 and bg-primary in as file and 
lastly removed text-dark from line 9,20,23 from loginpartial.cshtml
0901
from blackboard in css_js.txt pasted the all css link and js link in layout file.
0903
added the code for dropdown menu and tested it the project to if any error.
0905
Created 3 new project with the name of VrajeshBook.DataAccess , VrajeshBook.Models , VrajeshBook.Utility
0906
Moved the Data folder from the main folder and pasted it in DataAccess project.
0908
installed the given packages and deleted the Migration folder in DataAccess and Modify the namespace.
0909
Deleted default Class1.cs file in all project.
0910
Moved the Models in VrajeshBooks.Models. 
0915
Added the project reference from original project to .DataAccess and .Models.
0917
Renamed the Models folder to ViewModels and changed the namespace and run the project.
0920
Removed the using statment in startup.cs and again run the project successfully.
0922
In the Utility project, create a static details class called SD.cs
0925
In the DataAccess project add project references t o Models and Utility
0928
Add a ‘Customers’ area to Areas and Move the HomeController.cs to the Area > Customer >
Controller folder and delete Data and Models.
0930
Move Views > Home and modify the HomeController namespace
0932
Copy _ViewImport and _ViewStart to Customer Area
0933
Modify the _ViewStart.cshtml to reflect the new path
0935
Add a new Admin area in Areas
0938
Add the proper view files and delete the Data and Models folder
0941
Delete the Controllers folder
0943
Did the last commit

2023-11-04
1744
started the new part 2 cloned the project.
1748
created new file Category.cs



2023-11-06
1554
Started part-2 

1556
Reviewed Appsettings.json
ran add-migration AddDefaultIdentityMigration command in VrajeshBooks.Dataaccess

1559
Reviewed files in sql statements,syntax 

1600
Updated Database
Reviewed updated Database in sql server

1637
Created new folder in .DataAccess named Respository and IRepository and modiified the code accordingly

1642
Added new CategoryRespository and ICategoryRepository in folders and commit to github

1650
Added  new SP_Call.cs and ISP_Call.cs in respository folder

1705
Created new IUnitOfWork and UnitOfWork.cs and added the code in it.

1722
Created new layout and add navigation to category page and added javascript file and navigate to category for review

1750
Added the parital view that was given in the slides and run the successfully with addition
and updation functionality run correctly