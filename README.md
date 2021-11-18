# Create a GitHub Repository
1. Go to https://github.com/ and sign in.
![image](https://user-images.githubusercontent.com/94622154/142441947-07c091e3-05e5-4474-8a30-ad2f674862db.png)
2. Press the green <kbd>New</kbd> button.
![image](https://user-images.githubusercontent.com/94622154/142442603-17c4d28c-fb11-40b0-b143-4112449861b6.png)
3. Fill out the fields.
![image](https://user-images.githubusercontent.com/94622154/142444291-39ec85d4-b0cb-4171-9282-7fd9310e0573.png)
4. <kbd>Create Repository</kbd>
5. If you created a Private Repository, then you will see something like this:
![image](https://user-images.githubusercontent.com/94622154/142445067-fbbc2ea4-5ac9-4f76-9694-e9d4f9ecba0c.png)
6. If you created a Public Repository, skip this for now.
7. In the quick setup area, make sure you have `HTTP` selected instead of `SSH`. and copy the url. (Again, for public, don't worry about this.)
8. Continue to the next section below

# Setting up a GitHub Repository

1. Go to your terminal, and type `git`.
  If you have git, then it will show you a list of commands that you can try.
  If you DON'T have git, then it will say `git is not a command`. 
    Go to https://git-scm.com/ to download it.
2. Make sure that your project has it's own folder on your computer. In other words, put all the files from your project into one folder.
  ![image](https://user-images.githubusercontent.com/94622154/142440550-2f117a3b-9ca2-4b81-bc74-2ec3cb4b7169.png)
3. Change into that folder by running `cd 'ExampleProject/'`. Make sure it's the right one.
4. Initialize the repository: `git init`
5. Add a remote: `git remote add origin 'https://github.com/AnyeAlt/ExampleRepository.git'` - This is the URL you copied earlier (If you have a public repository, then add `.git` to your project URL. Example: Project URL = https://github.com/AnyeAlt/ExampleRepository, so my Final URL would be https://github.com/AnyeAlt/ExampleRepository.git).
6. Push to the remote: `git remote set-url origin 'https://github.com/AnyeAlt/ExampleRepository.git'`. (Same url)
7. In Visual Studio Code, open your project folder.
8. Go to the third icon on the left, which is the git icon:

![image](https://user-images.githubusercontent.com/94622154/142453929-0c8cfd07-9671-439a-9203-cbf54f23d160.png)
9. Press <kbd>Initialize Repository</kbd>, and you're done!
