# Database_RealWorldProblems_MySQL

## COMBINE TWO TABLES
### TABLE: PERSON

### | Column Name | Type    |
### | PersonId    | int     |
### | FirstName   | varchar |
### | LastName    | varchar |

### PersonId is the primary key column for this table.
### TABLE: ADDRESS

### | Column Name | Type    |
### | AddressId   | int     |
### | PersonId    | int     |
### | City        | varchar |
### | State       | varchar |

### AddressId is the primary key column for this table.

## Nth  Highest Salary
### Write a SQL query to get the highest / second highest / Nth highest salary from the EMPLOYEE table

### | Id | Salary   |
### | 1  | 11100    |
### | 2  | 11200    |
### | 3  | 111300   |

### For example, given the above Employee table, the SECOND HIGHEST SALARY IS 11200. 

## COMPARISON example:
### Employees Earning More Than Their Managers

### The EMPLOYEE table holds all employees including their managers. Every employee has an Id, and there is also a column for the manager Id.

### | Id | Name  | Salary | ManagerId |
### | 1  | Joe   | 70000  | 3         |
### | 2  | Henry | 80000  | 4         |
### | 3  | Sam   | 60000  | NULL      |
### | 4  | Max   | 90000  | NULL      |


## REDUNDANCY example: Duplicate Emails
### Write a SQL query to find all duplicate emails in a table named PERSON.

### | Id | Email   |
### | 1  | a@b.com |
### | 2  | c@d.com |
### | 3  | a@b.com |


## COMPARE TUPLES AND ROW DATA example: Rising Temperature
### Given a Weather table, write a SQL query to find all dates' Ids with higher temperature compared to its previous (yesterday's) dates.

### | Id(INT) | Date(DATE) | Temperature(INT) |
### |       1 | 2015-01-01 |               10 |
### |       2 | 2015-01-02 |               25 |
### |       3 | 2015-01-03 |               20 |
### |       4 | 2015-01-04 |               30 |
