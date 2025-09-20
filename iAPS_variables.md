# iAPS Build

## Actions Secrets and Variables → Repository Secrets

### [Apple Developer API Keys](https://appstoreconnect.apple.com/access/integrations/api)

- `FASTLANE_ISSUER_ID`
- `FASTLANE_KEY`
- `FASTLANE_KEY_ID`

### [GitHub Personal Access Token (`GH_PAT`)](https://github.com/settings/tokens/new)

Log into your GitHub account to create a personal access token, which you will save as `GH_PAT`.

#### Steps to Create a New Personal Access Token
1. Enter a name for your token, e.g., **FastLane Access Token**  
2. Change the **Expiration** selection to **No expiration**  
3. Select the **workflow** permission scope (the `repo` scope will be automatically selected)  
   - This step enables automatic building  
4. Click **Generate token**  
5. Copy the token and record it. It will be used below as `GH_PAT`

> To skip the detailed instructions, click on **Make up a Password**.

---

### Additional Secrets
- [`TEAMID`](https://developer.apple.com/account#MembershipDetailsCard) 
- `MATCH_PASSWORD`  
