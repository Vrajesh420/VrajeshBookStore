﻿2023-10-31
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


2023-11-06
1554
Started part-2 

1556
Reviewed Appsettings.json
ran add-migration AddDefaultIdentityMigration command in VrajeshBooks.Dataaccess

1558
added first migration 20231104214339_AddDefault
second migration 20231104214646_addCategory.cs it was empty
final all thing added to migration 20231104214752_review.cs

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

1917
added a space in category.js foe delete button.
modified and tested.

2023-11-17

1130
Cloned the project and added the CoverType.cs model in models project with ID and Name in it.
1145
Created the New CoverTypeRepository and ICoverTypeRepository and updated the CoverTypeRepository from the CategoryRepository
1149
Updated the ICoverTypeRepository like the ICategoryRepository and fix the errors by using quick actions
1154
Added the CoverType to IUnitOfWork and UnitOfWork as per the given one and push to git hub
1211
Pushed CoverType To the DataBase and created the migration - 20231117171028_AddedCoverType
1541
Created new New controller, index, and Upsert view along with coverType.js
1548
Created new migration - 20231117204821_addProductToDb
1607
Added the migration - 20231117210501_addValidationToProduct
1617
Added ProductRepositry and IProductRepository and Updated the ApplicationDbContext
1621
Added the product to UnitOWork and IUnitWork
1821
Started section 2 Created new ProductController.cs and added new code for all action
1917
Added new View Model to Product , Installed package Microsoft.AspNetCore.Mvc.ViewFeatures and solved errors by adding references.
Commented out Upsert method.
1924
Modified API call include category and covertype properties.
1928
Added Index view to Product in admin area.
Created product.js pasted code from category.js to product.js
1932
Added link of product to _layout.cshtml 
Tested Application, worked perfectly
2023-21-11
0922
Started Section-3
0924
Created Upsert view in Product folder in Admin Area
0926
Created account on tiny.cloud and copied script from it and pasted it to script of Upsert, Added other required script
0928
Uncommented Upsert method from ProductController.cs and added httppost method
0930
Added images folder in wwwroot and subfolder products in it.
0931
Changed my theme to Journal because font color was not good in output.
I forgot to change Category list to Cover Type list , so I modified it in this step
0932
Tested Application, worked well.
Section 3 completed
2023-11-28
0818
Cloned repository and started part-4, Added httppost and httpdelete method in productcontroller in admin area
0821
Modified Product.cs in Models project to update foreign key of CoverType. Run migration 20231128132127_updateForeignKeyCoverType.cs and updated database
0830
Added IUnitOfWork to HomeController.cs in customer area.
0836
Updated Index View of customer area to show book catalogue
0846
I created images and products folder in wwwroot in part3 section3, but it was not displaying so i deleted and created again
0848
Added RazorRuntimeCompilation method in startup.cs 
0852
Modified product.js to change column name of category and listprice.
0854
Tested Application by adding images, product catalogue is showing on index page of customer area successfully.
0856
Part-4 Completed
2023-12-05
1448
forgot to update README.txt after adding 3 book poster , modified README.md too.