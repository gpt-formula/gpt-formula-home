# Setup Guide

Welcome to ChatGPT Formula (FREE)! Follow these steps to get started with our Google Workspace Marketplace addon.

## Step 1: Install the Addon

1. Visit the [Google Workspace Marketplace](https://workspace.google.com/marketplace).
2. Search for "ChatGPT Formula".
3. Click on "Install" and follow the prompts to authorize the addon.

## Step 2: Configure Your Settings

1. In Google Sheets, navigate to the **Add-ons** menu.
2. Click on **ChatGPT Settings**.
3. Set your ChatGPT API Key. (Note: The addon requires this key to function properly.)

## Step 3: Using ChatGPT Formula

1. **Enter Your Data**: Start by entering your dataset into Google Sheets as usual. For example, you might have a list of customer names and their respective countries.

2. **Utilize ChatGPT Formula Functions**: Use the ChatGPT Formula functions directly within Google Sheets to enhance your data analysis. For instance, you can use `GPT()` to generate summaries of customer feedback or `GPT_MULTI()` to batch process customer data with their preferences.

   **Example**: Suppose you have a column of customer names in column A and their countries in column B. You can use the following formula in Google Sheets:
   ```excel
   =GPT_MULTI("Customer names and countries")
