<div align="center">
	<p><b><i>Let's Contribute To Open-source</i></b></p>
</div>


Hosted by DigitalOcean for the 8th year in a row, Hacktoberfest encourages participation in giving back to the open source community by completing pull requests, participating in events, and donating to open source projects.

<br>

### _Completing the Challenge_

If you have previously never contributed to any open-source software then these steps will help you get started:

1. Go to Hacktoberfest [official website](https://hacktoberfest.digitalocean.com/) and sign in there using your GitHub.
2. I am assuming you have git installed and setup in your computer. If it isn't, download and install it from [here](https://git-scm.com/downloads).
3. Fork this repository by clicking on the top right corner where it is written `Fork`.
4. Once it is forked, clone the repository in your computer. For this, copy the URL in the address bar, and use the following command:

```sh
git clone url_you_just_copied
```

4. Open this cloned repository in your preferred code editor. Also, open a terminal in this directory.
5. Now type in the following command in the terminal and replace `username` with your GitHub username.

```sh
git checkout -b username
```

6. Create a markdown file inside the `profiles` directory and name it `username.md`. Replace the `username` with your GitHub username. For instance, my GitHub username is `msaaddev`, so I have created a file with name `msaaddev.md`.
7. Now copy the following and paste it inside the file you just created. Add your information as well. You can also take a look at my [file](https://github.com/msaaddev/Hacktoberfest/blob/main/profiles/msaaddev.md) for example.

```md
Name: Here goes your name

Username: Here goes your GitHub username

Favorite Language: Here goes your fav programming language
```

8. Once you have done all this, commit your changes to GitHub. You can do this with the following commands. Make sure you execute them in the precise order one after another in your terminal.

```sh
# copy and paste the following in the terminal
git add .

# copy and paste the following in the terminal after you have executed the previous command
git commit -m "hacktoberfest contribution"

# copy and paste the following in the terminal after you have executed the previous command
git push -u origin your_github_username
```

9. Now open the forked repository on your GitHub. You will see a yellow box at the top telling you that some changes are pushed. You will also see a button called `Compare & pull request`. Click on it.
10. Now add a title, some description and voila! You have opened a pull request in this repository.
11. Also star this repository. 😉

_You need to open **four** valid pull requests in order to complete the challenge. If you have performed the above steps, you have already opened one pull request. And you need only three more._

<br>

> Note: Those repositories who have `hacktoberfest` as a label are considered for Hacktoberfest challenge only.
