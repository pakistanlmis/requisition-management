/***************************** R E A D    M E ****************************/

For successfull running the module, kindly follow these steps:

1.Go to file : /includes/classes/Configuration.inc.php , and set your directory name in  : $system_main_path .

2. Restore this file on your mysql server : DB_RESTORE.sql

3.Go to file : /includes/classes/Configuration.inc.php , and set your DB credentials in following variables : 
				$db_host 		= '';
				$db_user 		= '';
				$db_password 	= '';
				$db_name 		= '';
				
				
4. Make sure your user is created .

5. For Creating New users , and warehouses, use the following credentials 
				User	= administrator
				Pass	= 123
				
6. Following are test users of different levels (with password = 123):

				test_district
				test_provincial
				test_central

/***************************** You Are Ready To Use ****************************/




A. If you wish to later integrate Email functionality, the configuration can be saved in : '/application/includes/classes/clsEmail.php'

B. If you wish to later integrate SMS functionality , configure it in the file: '/application/includes/classes/clsSMS.php'