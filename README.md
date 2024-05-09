# First time setup information

Welcome to the City of Stockton Office of Performance & Data Analytics Github! Before you begin, make sure you have the following installed on your system:

- Git (Download and install from [https://git-scm.com/](https://git-scm.com/))
- A coding editor of your choice

## Initial Configuration Steps

### Step 1: Configure HTTP SSL Backend

To configure Git with `http.sslBackend` set to `schannel`, run the following command in your terminal:

```bash
git config --global http.sslBackend schannel
```

### Step 2: Set Git User Email

Set your Git user email to your work email address using the following command. This includes the --system flag to configure Git to always use your work email address for Git commands on this system:

```bash
git config user.email "your-email@stocktonca.gov" --system
```

Replace `"your-email@stocktonca.gov"` with your actual Stockton email address.

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
   git checkout -b name/my-feature
   ```
4. Make changes and commit them:
   ```bash
   git add your_file
   git commit -m "your_message"
   ```
   Replace `your_file` and `"your_message"` accordingly
5. Push your changes to your fork:
   ```bash
   git push origin name/my-feature
   ```
6. Open a pull request on the original repository and fill out the template accordingly

## Additional Help

If you have any questions or need further assistance, please contact <liam.roh@stocktonca.gov> or another admin for support.

Thanks!
