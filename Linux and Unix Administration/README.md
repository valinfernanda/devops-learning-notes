This is my personal documentation on Linux and Unix Administration. The documentation is currently written in Indonesian, but if you would like an English version, 
I would be happy to translate it. The full documentation is available in a PDF located in the same folder.


Part 1:
1. User & Group Creation
● Create 3 new users: user1, user2, user3.
● Create 2 new groups: dev and ops.
● Add user1 and user2 to the dev group.
● Add user3 to the ops group.

2. Permission Management
● Create the directory /project/dev with the owner group set to dev.
● Give permissions so that only the dev group can read and write in /project/dev.
● Create the directory /project/ops with the owner group set to ops.
● Give permissions so that only the ops group can read and write in /project/ops.

3. Testing
● Log in as user1, try creating a file in /project/dev.
● Log in as user3, try accessing /project/dev (it should be denied).
● Do the same tests for the /project/ops directory.


Part 2:
1. Install and configure Nginx.
2. Create a simple index.html file containing:
<h1>Hello, this is my first website!</h1>


Testing
Access http://IP_VM and make sure the page you created appears.
