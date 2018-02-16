Installation links/commands:

MacOS:
install xcode by running:
	xcode-select --install

install homebrew by running:
	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

install postgres by running: 
	brew install postgres

install pgcli by running: 
	brew install pgcli

initialize postgres by running: 
	brew services start postgresql

begin pgcli/postgres by running: 
	pgcli postgres



Windows:
go to https://www.postgresql.org/download/windows/
download installer
follow instructions: keep all options as default. Create password.
go to folder containing PostgresSQL. 
Run "PSQL"
Press enter several times then enter password.



First SQL command:
 
create table gtdb1(eventid bigint not null, iyear bigint not null, imonth bigint not null, iday bigint not null, country bigint not null, country_txt text not null, region_txt text not null, provstate text, city text, latitude decimal, longitude decimal, summary text, attacktype1_txt text, targtype1_txt text, targsubtype1_txt text, gname text, motive text, weaptype1_txt text, weapdetail text, nkill bigint, propvalue bigint);
