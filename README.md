# How to Add Your Token to the OracleSwap ERC20 Token List 🌐

Welcome to the OracleSwap token list repository! If you're looking to add your token to the OracleSwap Token list, follow these step-by-step instructions to make a pull request (PR).

## Prerequisites 📋

- A GitHub account.
- Your token logo in PNG or SVG format, with a size of at least 250x250 pixels.
- Some social engangement.

## Step-by-Step Guide 🛠️

### Step 1: Fork the Repository 🍴

1. Go to the [OracleSwap Token List Repository](https://github.com/oracle-swap/default-token-list).
2. Click **Fork** in the top right corner to create a copy of the repository under your account.

### Step 2: Create a Feature Branch 🔀

1. Clone your forked repository:

    ```bash
    git clone https://github.com/Oracle-Swap/default-token-list.git
    cd default-token-list
    ```

2. Create a new branch:

    ```bash
    git checkout -b add-my-token
    ```
### Step 2.1: Alternate method 🔀

1. Open your forked repository in the browser when you are logged into github by pressing the period button on your keyboard "." to open vs code browser.:

    ```Press period on keyboard to open vs code in browser
    ```

### Step 3: Add Your Token Information and Logo 📝

1. Add your token logo to the `assets/token/14/` directory. Ensure the image is at least 250x250 pixels and is named using your token's symbol or address.

2. Open `tokens.json`.
3. Add your token information in the following format:

    ```json
    {
      "name": "Wrapped FLR",
      "address": "0x6DaF228391e388B05BBc682FEA3CB1Cc3E38c44E",
      "symbol": "WFLR",
      "decimals": 18,
      "chainId": 14,
      "logoURI": "https://raw.githubusercontent.com/oracle-swap/default-token-list/main/assets/token/14/WFLR.png",
      "link": "https://flare.network/"
    }
    ```

4. Ensure the formatting is correct and save the file.

### Step 4: Commit and Push Your Changes ⬆️

1. Stage your changes and commit them:

    ```bash
    git add tokens.json
    git add assets/token/50/YOUR_LOGO.png
    git commit -m "Add new token and logo to list"
    ```

2. Push the changes to your GitHub repository:

    ```bash
    git push origin add-my-token
    ```

### Step 5: Create a Pull Request 📤
f
1. Go to your fork on GitHub.
2. Click **Pull request** > **New pull request**.
3. Set the base repository to `oracle-swap/default-token-list` and compare your feature branch.
4. Add a title and description for your pull request, then click **Create pull request**.

## Next Steps 🔄

- Your pull request will be reviewed by the repository maintainers.
- If any changes are required, you can make them on your branch and push them; the pull request will update automatically.
- Once approved, your token will be added to oracleswap erc20 token list.
