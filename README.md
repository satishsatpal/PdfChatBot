Make suitable changes in the following block of code in app.py file to add the chat history in the sql database created locally:

            try:
                connection = mysql.connector.connect(host='IP Adress',
                                  database='Name of database',
                                  user='user name',
                                  password='password',use_pure=True)

