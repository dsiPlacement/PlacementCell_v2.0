##Company

- Registration
  - Input Elements
    - Email
    - Username
  - Check if email already registered(use API to check)
  - Check if username exists and reply back(use API to check)
  - Allow username and email to be same
  - Send mail with temporary link that is deleted after password is set
- Temporary link to define password
  - Input Elements
    - Password
    - Confirm Password
  - Check if password and confirm password are equal and register user
  - Redirect to `Profile` to setup profile
- Login
  - Input Elements
    - Username
    - Password
  - Send data to server and wait for reply
    - If reply is `Success` redirect to `Post Recruitment`
    - If reply is `Failure` redirect to Login(same page) and display error
- Profile
  - Input Elements
    - Company name
    - Company logo (image)
    - Organisation size (number)[number of employees]
    - Payscale  (number)
    - Glassdoor link
    - Website link
    - LinkedIn link
    - Facebook link
    - Basic details or more details about what they do (text area)[optional as website link is enough]
    - Past details on recruitment from DSI (v2.0)
- Post new recruitment details
  - Input Elements and Process
    1. Select eligibility criteria
      - Provide percentage (0 means none)
      - Provide Backlogs
        - Active
        - Total (Active + Old)
      - Departments
        - BE and MTech
          - (All or Specify branches)
    2. Add job profile
      - Must be a Editor box(CK Editor or something similar)
    3. Post job profile which reaches required students

- For any doubts on this , raise a issue with the Heading containing `FEATURES_COMPANY.md`
