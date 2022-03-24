# Schema

User
- email (unique, used for login)
- password

UserProfile
- user_id
- first_name
- last_name
- image
- fb_profile
- twitter_profile
- linkedin_profile
- website

StudyGroups
- study_group_id 
- name
- description

Posts
- user_id (ForeignKey)
- name
- created_at
- updated_at  

Roles
- Admin
- Student
- External

# API

/users
- GET
- POST

/users/:id
- GET
- DELETE

/
