# Mobile FAQ

## Server Connection Failed?

- Check whether your network connection is working normally
- Disable network proxy tools if they interfere with SSH connections

## Connection Drops When the App Goes to the Background?

- On Android, set the app battery policy to `Unrestricted` to reduce background disconnects

## Why Did My Asset Data Disappear?

This usually happens for one of these reasons:

- Data isolation: different accounts use different datasets, so logging out or switching accounts can show a different asset list
- App removal: uninstalling the app also removes local data

## How Do I Report an Issue?

You can contact Chaterm through:

- In-app feedback: `Profile → Usage & Feedback → Issue Feedback`
- Email support: `support@chaterm.ai`

## Which AI Models Are Supported? How Do I Switch?

After signing in, go to [Profile > AI Settings > Model Selection](/docs/mobile/profile/#model-selection) to view and switch models. Supported models include flagship models from OpenAI, Gemini, and other major providers. Available models vary by subscription tier — check the app for the current list.

## Data Sync Not Working?

- Confirm you are signed in (sync is unavailable without an account)
- Check whether your network connection is working
- Go to [Profile > Data Management](/docs/mobile/profile/#data-management) and confirm the sync toggle is on
- If the issue persists, try signing out and back in, then sync again

## What Can I Use Without Signing In?

Without signing in you can add and manage local assets and open SSH connections. AI Chat and cloud data sync require a signed-in account.

## Troubleshooting Checklist

If the problem is related to connection or sign-in, confirm these first:

- The app version is the latest release
- Your current network can reach the target host
- Your account is still signed in
- The model and AI settings are configured correctly
