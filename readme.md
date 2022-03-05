Requirements
-	nodeJS installed: https://nodejs.org/it/download/
-	mysql installed (XAMPP is fine if you want to have phpMyAdmin UI to interact with the db)

Package dependency
Run the following command from cmd: npm install --save ethers

Database configuration

#1 Option
Run the following SQL command:
CREATE TABLE accounts (
    public_key varchar(255),
    private_key varchar(255)
);
#2 Option
1.	Open phpMyAdmin (URL: localhost/phpMyAdmin)
2.	Create a new database, ex. Called “marketmaking”
3.	Change DB configuration if you want more security
4.	Create a new table called “accounts” with 2 field that are called:
a.	public_key  varchar 255 length
b.	private_key  varchar 255 length
5.	Save

Start the code
1.	Open cmd prompt
2.	Run the following command: node bot.js
