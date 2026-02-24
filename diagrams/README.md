
The process begins when a user opens a web browser and accesses the application hosted on an AWS EC2 instance. The browser sends an HTTP request to the Apache web server, which returns a web form that allows the user to submit a SQL query.

After reviewing the interface, the user enters a SQL query and submits the form. This action triggers a second HTTP request that is handled by server-side backend logic. Instead of returning a static file, Apache executes a Python-based backend process through the CGI interface and passes the user’s input to it.

The backend process connects to a relational database running on the same EC2 instance and executes the submitted SQL query. The database engine processes the request, retrieves the relevant records, and returns the results to the Python backend.

Finally, the backend formats the query results into an HTML response, typically displayed as a structured table. Apache sends this dynamically generated content back to the browser, where the user can view the results.

In this system, messages include HTTP requests, form data, SQL queries, and result sets that enable communication between the browser, web server, backend logic, and database engine.
