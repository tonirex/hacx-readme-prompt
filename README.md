# Hackathon README Prompt for GitHub Copilot

🚀 A ready-to-use GitHub Copilot custom prompt to generate comprehensive README files for your hackathon project submissions.

## What is this?

This repository provides a pre-built GitHub Copilot custom prompt that helps you quickly generate professional, detailed README documentation for your hackathon projects. Instead of spending precious hackathon time writing documentation, let AI help you create a comprehensive README that will impress judges and make your project shine!

## Features

✨ **Comprehensive Coverage** - Generates all essential sections for a hackathon README
📋 **Structured Format** - Follows best practices for technical documentation
🎯 **Hackathon-Optimized** - Specifically designed for hackathon project submissions
⚡ **Quick Setup** - Takes just minutes to set up and use
🤖 **AI-Powered** - Leverages GitHub Copilot to analyze your code and generate relevant content

## How to Use

### Method 1: Download and Use in Your Repository

1. **Copy the prompt file to your hackathon project:**
   ```bash
   # Navigate to your hackathon project
   cd your-hackathon-project
   
   # Create the prompts directory if it doesn't exist
   mkdir -p .github/prompts
   
   # Download the prompt file
   curl -o .github/prompts/generate-hackathon-readme.md https://raw.githubusercontent.com/tonirex/hacx-readme-prompt/main/.github/prompts/generate-hackathon-readme.md
   ```

2. **Open GitHub Copilot Chat in VS Code:**
   - Press `Ctrl+Shift+I` (Windows/Linux) or `Cmd+Shift+I` (Mac)
   - Or click the GitHub Copilot icon in the Activity Bar

3. **Reference the custom prompt:**
   - Type `#file:.github/prompts/generate-hackathon-readme.md` in the chat
   - Then add your request: "Generate a comprehensive README for this hackathon project"

4. **Review and customize:**
   - GitHub Copilot will analyze your codebase and generate a detailed README
   - Review the generated content
   - Make any necessary adjustments or add specific details

### Method 2: Manual Setup

1. **Create the directory structure:**
   ```bash
   mkdir -p .github/prompts
   ```

2. **Copy the prompt content:**
   - Download or copy the content from [`.github/prompts/generate-hackathon-readme.md`](.github/prompts/generate-hackathon-readme.md)
   - Save it in your project at `.github/prompts/generate-hackathon-readme.md`

3. **Use with GitHub Copilot:**
   - Follow steps 2-4 from Method 1 above

## What the Prompt Generates

The custom prompt will help GitHub Copilot create a README with:

- **Project Title and Description** - Clear overview of your project
- **Problem Statement** - The challenge you're addressing
- **Solution Overview** - Your innovative approach
- **Technology Stack** - All technologies used
- **Architecture** - System design and components
- **Installation Guide** - Step-by-step setup instructions
- **Usage Guide** - How to use your application
- **Demo Links** - Screenshots, videos, and live demos
- **Project Structure** - File organization
- **Key Achievements** - Hackathon accomplishments
- **Future Enhancements** - Roadmap and ideas
- **Team Information** - Credits and contributors
- **Acknowledgments** - Thanks and attributions
- **License** - Legal information

## Tips for Best Results

1. **Complete your code first** - The prompt works best when your codebase is mostly complete
2. **Add comments** - Well-commented code helps Copilot understand your project better
3. **Review and edit** - Always review the generated README and add project-specific details
4. **Add visuals** - Enhance the generated README with screenshots and diagrams
5. **Test the instructions** - Make sure installation and usage steps actually work

## Requirements

- GitHub Copilot subscription (Individual, Business, or Enterprise)
- VS Code with GitHub Copilot extension installed
- A hackathon project repository

## Example Usage

```bash
# In your hackathon project directory
mkdir -p .github/prompts
curl -o .github/prompts/generate-hackathon-readme.md https://raw.githubusercontent.com/tonirex/hacx-readme-prompt/main/.github/prompts/generate-hackathon-readme.md

# Then in VS Code:
# 1. Open GitHub Copilot Chat
# 2. Type: #file:.github/prompts/generate-hackathon-readme.md Generate a comprehensive README for this hackathon project
# 3. Review and customize the output
```

### Example Output

Want to see what a README generated with this prompt looks like? Check out our [example README](EXAMPLE.md) to see a sample output for a fictional hackathon project called "HealthTrack AI".

## Contributing

Found ways to improve the prompt? Contributions are welcome! Feel free to:
- Open an issue with suggestions
- Submit a pull request with improvements
- Share your experience using the prompt

## License

MIT License - feel free to use this in your hackathon projects!

## About

Created to help hackathon participants save time on documentation and focus on building amazing projects. Good luck with your hackathon! 🎉
