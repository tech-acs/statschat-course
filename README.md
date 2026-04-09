# StatsChat course

Welcome to the StatsChat course!!! All of the course materials can be found [here](https://datasciencecampus.github.io/uneca-statschat-course/).

We will use this GitHub repo to submit exercises, review code, and ask questions. To start collaborating in the repo we need to get set up.

### Create a GitHub account

*If you already have a GitHub account you can skip these steps.*

1. Go to [GitHub](https://github.com/) and click 'Sign up' (top right)
2. Enter:
    - Your **email address**. Just use a work email address if you only intend to use GitHub for work.
    - A secure **password**. You will also need to set up at least one form of two-factor authentication to keep your account secure.
    - A **username**. There's some good advice about creating a GitHub username [here](https://happygitwithr.com/github-acct).
3. Click Create Account
4. Verify your email (check your inbox)
5. Choose Free Plan when prompted
6. [Customise your profile](https://docs.github.com/en/account-and-profile/tutorials/personalize-your-profile) (add picture, bio etc.). If you'd rather not add any personal information that is fine too.
7. Request write access to the [statschat-course](https://github.com/tech-acs/statschat-course) repo.

If you have any problems please check the [guidance](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account) on GitHub.

### Clone the `statschat-course` repo
Open up [VS Code](https://code.visualstudio.com/) and load a new terminal. If you have [Git](https://git-scm.com/) already installed on your local machine you can use Git Bash.

```bash
pwd # check your current directory
cd Projects # switch to a different directory e.g. Projects
git clone https://github.com/tech-acs/statschat-course.git # make a local copy of the repo
cd statschat-course # change your current directory to the repo
```

### Create your own branch
Create a branch with your GitHub username. For example, mine is 'rcatlord' so I would enter: 

```bash 
git checkout -b rcatlord
```

Next we need to push that branch to the `statschat-course repo`. 

```bash
git push -u origin rcatlord
```

You are now set up! You can push your work to your individual branch of the `statschat-course` repo.

---

If you have any questions please just post an [issue](https://github.com/tech-acs/statschat-course/issues).