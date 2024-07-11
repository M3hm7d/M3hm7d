- 👋 Hi, I’m @M3hm7d
- somethings i have learned from 3 years experinece , please note that this exploit is for understanding how sqli works and don't forget the sqli cheat-sheets from pentesetmonkey.net
- a small exploit that exploits the blind sqli in the pages that have parameters , i mean query like (https://doman-sql/a-web-page?id=) the vulnerable query is id=
- to crafting payloads visit the cheat-sheets from pentestmonkey.net to read about sql command and queries (good luck with crafting payloads)
- before starting exploit edit the .sh file and remove the "/* */" with ctrl+f you can find it , and replace the "(the-query)" with the parameter for example it's id in the above-mentioned example
- replace the URL variable with the url and the page with out the query , the id in our case , replace th $truestring variable with the error when you have to exploit it manually such as "login failed" or "the username or password is incorrect" and so on


- Usage : bash blind.sqli.injection.exploiter v3.sh (an intger from 1-20) (the sql command between double qoutes) note : your reference will be the ( pentesetmonkey.net ) sql injections cheat-sheets for crafting payloads
- if it's not working make it executable with ("chmod +x blind.sqli.injection.exploiter v3.sh")
- why because the compiler reads the bash command as (execute the v3.sh file and the blind.sqli.injection.exploiter)
