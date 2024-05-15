# First time setup information

Welcome to the City of Stockton Office of Performance & Data Analytics Github! Before you begin, make sure you have the following installed on your system:

- Git (Download and install from [https://git-scm.com/](https://git-scm.com/) - usually comes preinstalled on Mac)
- A coding editor of your choice

## Initial Configuration Steps

### Step 1: Configure HTTP SSL backend

To configure Git with `http.sslBackend` set to `schannel`, run the following command in your terminal:

```bash
git config --global http.sslBackend schannel
```

### Step 2: Set Git user email and Username

If prompted, set your Git user email / username to your work email address / name using the following command. The global flag changes your git config across all repositories for the machine.

```bash
git config user.email "your-email@stocktonca.gov" --global
git config user.name "First Last" --global
```

Replace `"your-email@stocktonca.gov"` and `"First Last"` accordingly. 

### Optional: Set pip.ini config

If using python, you will need to edit the pip.ini to allow package installation. Add the following lines to your pip.ini, or create it if necessary:

```bash
[global]
trusted-host = pypi.python.org
               pypi.org
               files.pythonhosted.org
```

[View documentation](https://pip.pypa.io/en/stable/topics/configuration/) for locating your pip.ini.

## Cloning a Repository

Use the following command to clone a repository:
```bash
git clone https://github.com/organization/repository.git
```
Replace `https://github.com/organization/repository.git` with the HTTPS link to the repository you are trying to clone

## Contributing

1. Fork the repository you want to contribute to
2. Clone the forked repository to your local machine
3. Create a new branch for your changes:
   ```bash
   git checkout -b dev/name/my-feature
   ```
4. Make changes and commit them:
   ```bash
   git add your_file(s)
   git commit -m "your_message"
   ```
   Replace `your_file(s)` and `"your_message"` accordingly
5. Push your changes to your fork:
   ```bash
   git push origin dev/name/my-feature
   ```
6. Open a pull request on the original repository and fill out the template accordingly

## Additional Help

If you have any questions or need further assistance, please contact <liam.roh@stocktonca.gov> or another admin for support.

Thanks!
