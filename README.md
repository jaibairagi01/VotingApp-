<h1>Voting Application</h1>
This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.

<h1>Features</h1>
<ul>
    <li>User sign up and login with Aadhar Card Number and password</li>
    <li>User can view the list of candidates</li>                                                                                           
    <li>User can vote for a candidate (only once)</li>                                                                                    
    <li>Admin can manage candidates (add, update, delete)</li>                                                                               
    <li>Admin cannot vote</li>
</ul>

<h1>Technologies Used</h1>
<ul>
<li>Node.js</li>
<li>Express.js</li>
<li>MongoDB</li>
<li>JSON Web Tokens (JWT) for authentication</li>
</ul>

<h1>Installation</h1>

1. Clone the repository:

   git clone https://github.com/jaibairagi01/VotingApp-.git
   

<h1>API Endpoints</h1>

<h2>Authentication</h2>

<h3>Sign Up</h3>
<ul>
   <li>POST /signup: Sign up a user</li>
</ul>

<h3>Login</h3>
<ul>
   <li>POST /login: Login a user</li>
</ul>
<h2>Candidates</h2>

<h3>Get Candidates</h3>
<ul>
   <li>GET /candidates: Get the list of candidates</li>
</ul>

<h3>Add Candidates</h3>
<ul>
   <li>POST /candidates: Add a new candidate (Admin only)</li>
</ul>

<h3>Update Candidates</h3>
<ul>
   <li>PUT /candidates/:id: Update a candidate by ID (Admin only)</li>
</ul>

<h3>Delete Candidates</h3>
<ul>
   <li>DELETE /candidates/:id: Delete a candidate by ID (Admin only)</li>
</ul>


<h2>Voting</h2>

<h3>Get Vote Count</h3>
<ul>
   <li>GET /candidates/vote/count: Get the count of votes for each candidate</li>
</ul>

<h3>Vote for Candidate</h3>
<ul>
   <li>POST /candidates/vote/:id: Vote for a candidate (User only)</li>
</ul>
<h2>User Profile</h2>
<h3>Get Profile</h3>

<ul>
   <li>GET /users/profile: Get user profile information</li>
</ul>

<h3>Change Password</h3>
<ul>
   <li>PUT /users/profile/password: Change user password</li>
</ul>
