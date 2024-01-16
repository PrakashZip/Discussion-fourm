# Java Discussion Forum  -by [@prakashZip](https://github.com/prakashZip)

## Overview

This Java Discussion Forum project is designed to provide a platform for user discussions with features including user creation, login validation, question and answer functionalities, and the ability to post replies.

## Features

- **User Creation:**
  - Admin can create new users with different roles (Admin, Moderator, User).
  - User login validation and approval.

- **Question Upload:**
  - Users can ask questions, and these questions can be searched by a unique question number.
  
- **Answer Upload:**
  - Users can upload answers to specific questions.

- **Reply Functionality:**
  - Users can add replies or queries to answers.

- **Role-Based Access:**
  - Different roles (Admin, Moderator, User) have different menu options and capabilities.

## How to Run on Your Local Machine

1. **Requirements:**
   - Java Development Kit (JDK) installed on your machine.
   - Git installed to clone the repository.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/PrakashZip/Discussion-fourm.git
   cd Discussion-fourm
   ```

3. **Compile and Run:**
   ```bash
   javac com/forum/main/DiscussionForum.java
   java com.forum.main.DiscussionForum
   ```

4. **Follow the Console Instructions:**
   - Create an admin user during the initial setup.
   - Log in and explore the features based on your role.

## Practical Use Case

This Discussion Forum project is suitable for scenarios where a community or organization needs an organized platform for discussions. It can be customized and extended to fit specific use cases such as educational forums, technical support, or general discussions.

## Exceptions

- Input validations are implemented, but incorrect inputs may still cause unexpected behavior. Ensure correct inputs during interactions.

- Exception handling is designed to cover common scenarios, but additional testing and improvements may be needed.

## Contributors

- Satya Prakash Sahoo
- [satyaprakash.od@gmail.com](mailto:satyaprakash.od@gmail.com)

Feel free to contribute by forking the repository and submitting pull requests.

---

This template covers the basic sections you might want in a README file. Customize it based on your project's specific details and any additional information you'd like to provide.
