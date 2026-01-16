# How to Set Up Your Questions for the Wix Embed

Follow these steps to make your quiz work on your Wix site:

## 1. Create a GitHub Gist
1. Go to [GitHub Gist](https://gist.github.com/).  
2. Create a **new gist** and paste the contents of your `Questions.txt` file.  
3. Give it a descriptive name, like `Questions.txt`.  
4. Make sure it is **public**.  
5. Save the gist.

# 2. Get the RAW URL
1. After saving, open your gist and click the **"Raw"** button.  
2. Copy the URL in your browser — this is your **RAW link**.

## 3. Update Your HTML
1. Open `Main.html`.  
2. Find **line #1047**, which looks like this:

```javascript
// Original code
const questionsUrl = 'https://gist.githubusercontent.com/EddieTheDog/7a45769f81114969d6dc201e1f639fbb/raw/gistfile1.txt';

## 4. Replace the URL with your RAW gist link, like this:
// Updated code
const questionsUrl = 'YOUR_RAW_GIST_LINK_HERE';

## 5. Embed on Wix
1. Upload Main.html to your Wix site or host it online.
2. Use the Wix Embed Code feature to display the page on your site.

## 6. Test It
Open your Wix page and make sure the questions load correctly.
If it doesn’t show, check that your RAW URL is correct and that your gist is public.

