# How to Contribute:

<p align="center">
  <img width="400" alt="RoseSecurity" src="https://github.com/RoseSecurity-Research/Red-Teaming-TTPs/assets/72598486/93b1e9a2-0798-475b-b75c-936abcd38db1">
</p>

## Intro:

Welcome to RoseSecurity!

We are thrilled to have you join our community of passionate individuals dedicated to advancing cybersecurity through open-source research. At RoseSecurity, we believe that collaboration and knowledge sharing are essential in fortifying your organization's security posture and making the digital world a safer place for all. Here are some tips and tricks that should help you get started with making your first PR request!

## Getting Started:

This guide assumes you have already added in your SSH keys (see [Adding a New SSH Key To Your GitHub Account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)) and done any custom shortcuts you wish to configure.

1. **Access the Repository**: Navigate to the RoseSecurity repository you want to fork. In this example, that will be: [https://github.com/RoseSecurity-Research/Red-Teaming-TTPs.git](https://github.com/RoseSecurity-Research/Red-Teaming-TTPs.git)
    
2. **Fork the Repository**: In the top-right corner of the repository page, click on the "Fork" button. This will create a copy of the repository under your GitHub account.
    
3. **Clone the Forked Repository**: Now you need to clone the forked repository to your local machine to start working with it. To do this, open your terminal or command prompt and navigate to the directory where you want to store the repository.

    - Run the following command to clone the repository:
    - **NOTE:** Replace "YourGitHubUsername" with your actual GitHub username.

```console
git clone https://github.com/YourGitHubUsername/Red-Teaming-TTPs.git
```

4. **Configure Remotes:** By default, the "origin" remote will be set to your forked repository. However, you might want to add the original repository as a remote so you can keep your fork up to date with any changes in the original repository. To do this, navigate to the cloned repository directory and run the following command:

```console
cd Red-Teaming-TTPs
git remote add upstream git@github.com:RoseSecurity-Research/Red-Teaming-TTPs.git
```

## Adding Awesome Contributions:

Now you can start making changes to the code or files in your local repository! Add all of the awesome tools, tips, and tricks that you'd like! Once you've made some changes or additions, use the following commands to commit your changes:

```console
git add .
git commit -m "Your commit message here"
```

After committing your changes, you need to push them to your forked repository on GitHub:

```console
git push origin main
```

If you want your changes to be merged into the original repository, you'll need to create a pull request. Go to your forked repository on GitHub (e.g., https://github.com/YourGitHubUsername/Red-Teaming-TTPs) and click on the "Pull Request" button.

GitHub will compare the changes between your fork and the original repository. If there are no conflicts, you can click "Create Pull Request" to submit your changes for review.

You can periodically sync your fork with the latest changes from the original repository. To do this, use the following commands:

```console
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```

## Thank You:

Thank you for looking into contributing to the community! Your potential involvement in our initiatives holds the promise of making a positive impact on the ever-evolving world of cybersecurity. Together, we can work towards enhancing knowledge, sharing insights, and fostering innovation within the community.

