# Portfolio Template

A minimal, black and white portfolio template that's easy to customize without any coding knowledge.

## Getting Started

### Step 1: Download the Files
Make sure you have all these files in the same folder:
- `index.html`
- `style.css`
- `index.js`
- `config.js`

### Step 2: Edit Your Information
Open `config.js` in any text editor (Notepad, TextEdit, or VS Code).

This is the **ONLY** file you need to edit!

## Configuration Guide

### Basic Information
```javascript
name: "Jane Doe",           // Your full name
title: "Product Designer",  // Your job title or profession
bio: "I design digital...", // A short description about yourself
```

### Your Photo
```javascript
photo: "placeholder",
```
**Options:**
- Keep it as `"placeholder"` to show your initials in a circle
- Or paste any image URL like: `"https://example.com/your-photo.jpg"`
- Or place the image in same directory: `"your-photo.jpg"`

**How to get an image URL:**
1. Upload your photo to a free image hosting site like [Imgur](https://imgur.com)
2. Right-click the image and select "Copy Image Address"
3. Paste it between the quotes

### Contact Information
```javascript
email: "jane@example.com",
website: "janedoe.com",
linkedin: "linkedin.com/in/janedoe",
twitter: "twitter.com/janedoe",
```
- Replace with your own links
- Leave blank `""` if you don't want to show a link
- Don't include `https://` - it's added automatically

### Theme
```javascript
theme: "Light",
```
**Available themes:**
- `"Light"` - Classic black and white
- `"Ivory"` - Soft cream background with dark text
- `"Eclipse"` - Dark background with light text
- `"Warm"` - Warm beige tones

Just type the theme name exactly as shown above.

### Projects

Each project has three parts:

```javascript
{
    name: "E-commerce App",
    description: "A mobile shopping experience...",
    link: "https://example.com/project1"
}
```

**To add a new project:**
1. Copy an existing project block (from `{` to `}`)
2. Paste it below the last project
3. Add a comma `,` after the previous project
4. Update the name, description, and link

**Example:**
```javascript
projects: [
    {
        name: "Project One",
        description: "First project",
        link: "https://example.com/1"
    },
    {
        name: "Project Two",
        description: "Second project",
        link: "https://example.com/2"
    },
    {
        name: "NEW PROJECT",        // ← Your new project
        description: "Description",
        link: "https://example.com/3"
    }
]
```

**To remove a project:**
- Simply delete the entire `{ }` block including the comma

### Step 3: View Your Portfolio
1. Save the `config.js` file
2. Double-click `index.html` to open it in your browser
3. That's it! Your portfolio is ready

## Tips

✅ **Always keep quotes** around text: `"your text here"`

✅ **Add commas** between items in lists (but not after the last one)

✅ **Don't edit** `index.html`, `style.css`, or `index.js` unless you know what you're doing

✅ **Refresh the page** in your browser after making changes to see updates

## Troubleshooting

**Nothing shows up?**
- Make sure all 4 files are in the same folder
- Check that you saved `config.js` after making changes

**Text looks weird?**
- Make sure all your text is inside quotes: `"like this"`
- Check that you didn't accidentally delete a quote or comma

**Projects not showing?**
- Make sure there's a comma after each project except the last one
- Check that each project has `{` at the start and `}` at the end

## Hosting Your Portfolio

Once you're happy with your portfolio, you can publish it online for free:

1. **GitHub Pages** (Free)
   - Create a GitHub account
   - Create a new repository
   - Upload all 4 files
   - Enable GitHub Pages in settings

2. **Netlify** (Free)
   - Go to [netlify.com](https://netlify.com)
   - Drag and drop your portfolio folder
   - Get a free URL instantly

3. **Vercel** (Free)
   - Go to [vercel.com](https://vercel.com)
   - Import your project
   - Deploy with one click

## Need Help?

If you get stuck:
1. Double-check the examples in this guide
2. Make sure you're only editing `config.js`
3. Try refreshing your browser after making changes
4. Compare your `config.js` with the original template

---

Made with ❤️ for everyone who wants a simple portfolio
