# python-mysql

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
<h1>Connecting MYSQL database with Python  OOP🐍  </h1>
Connecting and executing query in Mysql DB using python. all code are clean and clear with OOP concept  
<h2>Conncting to the DB</h2>
goto file <a class="btn btn-success" href="/db/DBConnection.py">DB/DBConnection.py</a>and config the connection
<code>
      def __init__(self):
        self.mydb = mysql.connect(
            host="host", # Replace with the host of your database host
            user="username",# Replace with the username of your database username
            password="password", # Replace with the password of your database password
            database="database" # Replace with the name of your database
        )
</code>
