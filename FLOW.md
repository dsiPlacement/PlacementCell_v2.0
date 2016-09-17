##FLOW

### Defines how the entire flow of the user interaction happens

- Home page
  - Provides link to redirect whether as Student or Company
  - Redirect to `Login (Company)` or `Login (Student)`

- Registration page  (Company)
  - Redirects to `Profile`
- Login page  (Company)
  - Redirect to `Registration (Company)` if new
  - Redirect to `Post recruitment` if login successful
- Profile page  (Company)
  - Redirect to `Post recruitment` after complete setup
- Post recruitment page (Company)
  - Main page so no redirect
  - Redirect to `Home` if logout

- Registration page (Student)
  - Redirects to `Profile (Student)`
- Login page (Students)
  - Redirect to `Registration (Student)` if new
  - Redirect to `Dashboard` if existing and login successful
- Profile page (Student)
  - Redirect to `Dashboard` after complete setup
- Dashboard (student) (implement after design is frozen)
  - Main page so no redirect
  - Redirect to `Home` if logout
