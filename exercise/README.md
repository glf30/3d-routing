# React Router Assignment

Utilizing this Users data from this API (https://jsonplaceholder.typicode.com/users), complete the following routes utilizing React Router.

To access an individual user use https://jsonplaceholder.typicode.com/users/${id}

### 1. Home Page (`/`)

* Display a welcome message
* Add links to the **User List** page

---

### 2. User List Page (`/users`)

* Fetch a list of users
* Display each user’s **username** in a list
* Each username should be a clickable link that navigates to the **User Info Page** (`/users/:id`)

---

### 3. User Info Page (`/users/:id`)

* Read the dynamic `id` value from the URL
* Fetch data for a single user using that `id`
* Display the following information:

  * ID from the URL
  * Name
  * Email
  * Company catchphrase
* There should be a way to link back to the UserList page

---

### 5. 404 Page (`*`)

* Display a clear “Page Not Found” message
* This page should render for any URL that does not match an existing route
