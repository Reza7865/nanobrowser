# What Nanobrowser Can Do

Nanobrowser is an open-source AI web automation tool that operates directly within your browser. Below are its key features and capabilities:

## 1. Multi-agent Web Automation

Nanobrowser employs a system of specialized AI agents to automate web tasks:

- **Planner**: Develops strategies for task completion
- **Navigator**: Engages with web pages
- **Validator**: Verifies task completion accuracy

## 2. Example Use Cases

Automate various web tasks using natural language commands, such as:

### Research & Information Gathering
- "Visit TechCrunch and extract the top 10 headlines from the past 24 hours"
- "Identify trending Python repositories on GitHub with the most stars"
- "Compare pricing for a specific product across multiple e-commerce sites"

### Shopping Research
- "Locate a portable Bluetooth speaker on Amazon with water resistance, priced under $50, and a minimum battery life of 10 hours"
- "Compare gaming laptop deals under $1200 across Best Buy and Newegg"

### Social Media Monitoring
- "Retrieve the latest tweets about a specific topic or hashtag"
- "Track mentions of your company or product across various platforms"

### Data Extraction
- "Extract contact information from a list of company websites"
- "Collect product specifications from multiple product pages"

## 3. How to Use Nanobrowser

### Launch the Extension
- Load the extension in Chrome, then click the Nanobrowser icon in your toolbar to open the sidebar

### Configure API Keys
- Click the Settings icon to add your preferred LLM API keys (OpenAI, Anthropic, Gemini)
- Choose different models for different agents based on performance or cost needs

### Start Automating
- Enter your request in natural language in the chat interface
- Observe as the AI agents collaborate to complete your task
- Pose follow-up questions about the completed tasks

### Model Configurations
- **For enhanced performance**: Use Claude 3.7 Sonnet for Planner/Validator and Claude 3.5 Haiku for Navigator
- **For cost efficiency**: Use Claude Haiku or GPT-4o for Planner/Validator and Gemini 2.0 Flash or GPT-4o-mini for Navigator

## 4. Development Possibilities

With the project set up locally, you can also:

### Customize the Extension
- Alter the UI or add new features by modifying the source code
- Expand functionality for specific use cases

### Contribute to the Project
- Fix bugs or implement improvements
- Submit pull requests to the main repository
- Share your custom prompts or use cases with the community

### Create Custom Agents
- Develop specialized agents for specific domains or tasks

---


Now that you've built the Nanobrowser extension, let's get it loaded into Chrome. Here's how to load the extension you've built:

## Loading the Nanobrowser Extension into Chrome

1. **Open Chrome's Extensions Page**:
   - Open Chrome browser
   - Type `chrome://extensions/` in the address bar and press Enter

2. **Enable Developer Mode**:
   - Look for the "Developer mode" toggle in the top-right corner of the extensions page
   - Make sure it's turned ON (the toggle should be blue/highlighted)

3. **Load the Unpacked Extension**:
   - Click the "Load unpacked" button that appears in the top-left after enabling Developer mode
   - Navigate to the `dist` folder in your project: `/Users/minimal/Desktop/nanobrowser/dist`
   - Select the `dist` folder and click "Open"

4. **Verify Installation**:
   - You should see "Nanobrowser" appear in your list of extensions
   - The extension icon should appear in your Chrome toolbar (you might need to click the puzzle piece icon to see all extensions and pin Nanobrowser)

5. **Configure the Extension**:
   - Click on the Nanobrowser icon in your toolbar to open the sidebar
   - Go to Settings (gear icon) to add your LLM API keys:
     - OpenAI API key
     - Anthropic API key
     - Gemini API key (if needed)
   - Configure which models to use for each agent (Planner, Navigator, Validator)

Once you've set up your API keys, you can start using Nanobrowser by typing natural language commands in the sidebar interface.

If you make changes to the code and want to update the extension, run `pnpm build` again and then click the refresh icon on the extension card in the `chrome://extensions/` page.
