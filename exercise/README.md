# React Router Assignment

## Pages / Components to Implement

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
* Add a **Back** or **Home** button using either a link or programmatic navigation

---

### 4. Posts by User Page (`/users/:id/posts`)

* Display data related to the selected user (for example, posts created by that user)
* Show a list of titles or summaries
* Add a **Back to User Info** button
* Include a link to this page from the **User Info Page**

This page should feel like a continuation of the user detail view (detail → related detail), without requiring nested route layouts.

---

### 5. 404 Page (`*`)

* Display a clear “Page Not Found” message
* This page should render for any URL that does not match an existing route
