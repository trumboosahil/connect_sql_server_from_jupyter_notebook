# connect sql server from jupyter notebook

Insall pypyodbc 

!pip install pypyodbc

##mention connect string  don't forget port

(
            "Driver={SQL Server};"
            "Server=tcp:servername,1433;"
            "Database=dbname;"
            "UID=<>;" #User ID
            "PWD=<>;" #Password
            "Encrypt=True;"
            "TrustServerCertificate=False;"
            "Connection Timeout=60")
