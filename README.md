# Instagram Follower Checker

This guide will help you use a JavaScript snippet to find out who you follow on Instagram that doesn't follow you back, and who follows you that you don't follow back.

## Steps to Follow:

### 1. Sign in with your Instagram account
1. Open your browser and navigate to [Instagram](https://www.instagram.com).
2. Sign in with the account for which you need to check followers and followings.

### 2. Go to your profile page
1. Once signed in, click on your profile picture in the top right corner or go to `https://www.instagram.com/your_username/`.

### 3. Open Developer Tools
1. Right-click anywhere on the profile page and select `Inspect` (or press `Ctrl+Shift+I` on Windows/Linux or `Cmd+Option+I` on macOS).

### 4. Navigate to the Console Tab
1. In the Developer Tools panel, click on the `Console` tab.

### 5. Paste the Code
1. Open `file.js` and locate line 132.
2. Replace `your_username` with the username of the logged-in account.
3. Copy the entire code from `file.js`.
4. Paste the copied code into the Console and press `Enter`.

### 6. Wait for the Process to Complete
1. The script will take a few seconds to a minute to process, depending on the number of followers you have.
2. Once completed, you will get two separate arrays in the console:
   - `PeopleIDontFollowBack`: These are the people who are following you, but you are not following back.
   - `PeopleNotFollowingMeBack`: These are the people you are following, but they are not following you back.

### Important Note:
- Ensure you replace `your_username` with your actual Instagram username in `file.js` at line 132 before running the script.

### Explanation of Results:
- **PeopleIDontFollowBack**: List of users who are following you, but you are not following them back.
- **PeopleNotFollowingMeBack**: List of users you are following, but they are not following you back.

Feel free to use this script to manage your Instagram followings and followers efficiently!

## Disclaimer
Use this script responsibly and only on accounts you own or have permission to access. Instagram's terms of service prohibit certain automated actions, so ensure your actions comply with their guidelines.
