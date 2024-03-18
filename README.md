<h1>Voting Application</h1>
This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.

<h1>Features</h1>
User sign up and login with Aadhar Card Number and password<br>
User can view the list of candidates<br>
User can vote for a candidate (only once)<br>
Admin can manage candidates (add, update, delete)<br>
Admin cannot vote

<h1>Technologies Used</h1>
Node.js<br>
Express.js<br>
MongoDB<br>
JSON Web Tokens (JWT) for authentication

<h1>Installation</h1>

1. Clone the repository:

   git clone https://github.com/jaibairagi01/VotingApp-.git
   

<h1>API Endpoints</h1>

<h2>Authentication</h2>

<h3>Sign Up</h3>
<ul>POST /signup: Sign up a user</ul>

Login
<ul>POST /login: Login a user</ul>
<h2>Candidates</h2>

Get Candidates
<ul>GET /candidates: Get the list of candidates</ul>

Add Candidate
<ul>POST /candidates: Add a new candidate (Admin only)</ul>

Update Candidate
<ul>PUT /candidates/:id: Update a candidate by ID (Admin only)</ul>

Delete Candidate
<ul>DELETE /candidates/:id: Delete a candidate by ID (Admin only)</ul>


<h2>Voting</h2>

Get Vote Count
<ul>GET /candidates/vote/count: Get the count of votes for each candidate</ul>

Vote for Candidate
<ul>POST /candidates/vote/:id: Vote for a candidate (User only)</ul>
<h2>User Profile</h2>
Get Profile

<ul>GET /users/profile: Get user profile information</ul>

Change Password
<ul>PUT /users/profile/password: Change user password</ul>
