# Online Banking Platform

An online banking web application that allows **_Clients_** to create and manage bank accounts, credit cards and loans, **_Bankers_** to review and handle loan and credit card applications, and **_Admins_** to manage the system and handle reported issues.

## Screenshots

![Home](https://private-user-images.githubusercontent.com/93436246/292756406-33dbe0f2-324c-46d3-b68d-ddcf542f304a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MDc5MjksIm5iZiI6MTcwMzUwNzYyOSwicGF0aCI6Ii85MzQzNjI0Ni8yOTI3NTY0MDYtMzNkYmUwZjItMzI0Yy00NmQzLWI2OGQtZGRjZjU0MmYzMDRhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjI1VDEyMzM0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWI4OTE2YjY5NzlmN2E0ZGU5YzNlMmJmZTY5NGU4NDczNDQxOGU2ZTk0MDljOWFiNTMwYTk0ZDAxNzJiZDMwN2YmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.U5JlB8PNpnmJSMRIWhPyljevuZQ4cfNaNm2T9JCTaYI)
![Client Dashboard](https://private-user-images.githubusercontent.com/93436246/292756418-bbd501ca-45bc-4929-9426-4c786e480795.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MDc5MjksIm5iZiI6MTcwMzUwNzYyOSwicGF0aCI6Ii85MzQzNjI0Ni8yOTI3NTY0MTgtYmJkNTAxY2EtNDViYy00OTI5LTk0MjYtNGM3ODZlNDgwNzk1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjI1VDEyMzM0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTcxYWU4MjdkNTA5Yjk4MzRlNTQ1OTIxYjRhMjE1M2U3MzIyYjc1ZjkwMGE5Y2YxMTNmZTdjMGFjNWI5ZGRhMzAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.dXtg4UxUyIdX_kQGMK9mUvhoBFMjajr9OVeADWxQl5E)
![Client Credit Cards](https://private-user-images.githubusercontent.com/93436246/292756409-9a9fb5f3-010b-4fc0-83af-2e9335e6ac4c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MDc5MjksIm5iZiI6MTcwMzUwNzYyOSwicGF0aCI6Ii85MzQzNjI0Ni8yOTI3NTY0MDktOWE5ZmI1ZjMtMDEwYi00ZmMwLTgzYWYtMmU5MzM1ZTZhYzRjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjI1VDEyMzM0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJiZTAxMmRlNWQ4NWNjMDg4YTRlNDBlMTBlNzM1ZjIzY2VhZTExYWZkM2E4OTcwZTZkM2NjNzhjYjk0MGNkNzImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.CazoIM89PAEGQ_eWfczdkX1sRAvaxqprfma-Bp9yzfM)
![Client Credit Card Application](https://private-user-images.githubusercontent.com/93436246/292756415-0f19ed59-3320-4e2f-86ad-400e1215b1f9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MDc5MjksIm5iZiI6MTcwMzUwNzYyOSwicGF0aCI6Ii85MzQzNjI0Ni8yOTI3NTY0MTUtMGYxOWVkNTktMzMyMC00ZTJmLTg2YWQtNDAwZTEyMTViMWY5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjI1VDEyMzM0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTRhNTAzZDg2YzIzMjhjYzk5MGZhZDk2MmNhZmY2OTdmOTZkYjQ1NTliNGFlNjIxMjRkMzgwNzI2ODJkM2JiZjImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.-X7CV5HuHmRvuw0BwQcE3nRTDgzdgJm_NnFvJQlf2yA)
![Client Voice Assistant](https://private-user-images.githubusercontent.com/93436246/292756422-3bb01665-761d-4249-bc6c-134d9814ed9a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MDc5MjksIm5iZiI6MTcwMzUwNzYyOSwicGF0aCI6Ii85MzQzNjI0Ni8yOTI3NTY0MjItM2JiMDE2NjUtNzYxZC00MjQ5LWJjNmMtMTM0ZDk4MTRlZDlhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzEyMjUlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMjI1VDEyMzM0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdmOTZjMTI4ZGQ2OGY4MjZhYWE3ZWQzZDZiZjBiOTYzZDE4NmNhM2MwY2YzNmY2ZjcyNzBlMWVhODkxZDIzM2EmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.0Mj4xrct2J2JYvDVmqeczSedFvDUhxHn2AjbusAU5_M)

## Getting Started

#### Clone the repository

To get started, clone the repository by running the following command:

```bash
git clone https://github.com/software-engineering-2023/Online-Banking-Platform.git
```

#### Login credentials

Next, navigate to the login page and login using the following credentials:

##### Client

Username: `ClientUserName`
Password: `ClientPassword`

##### Banker

Username: `BankerUsername`
Password: `BankerPassword`

##### Admin

Username: `SystemAdminUsername`
Password: `SystemAdminPassword`

## Tech Stack

- HTML
- CSS
- JavaScript
- Bootstrap
- Fontawesome
- VSCode
- Git
- GitHub

## Authors

- [@MoTammaa](https://github.com/MoTammaa)
- [@mahmoudaboueleneen](https://github.com/mahmoudaboueleneen)
- [@AbdelrahmanRewaished](https://github.com/AbdelrahmanRewaished)
- [@abdelrahmanAbouelkheir](https://github.com/abdelrahmanAbouelkheir)
- [@Ahmedsherif74](https://github.com/Ahmedsherif74)
