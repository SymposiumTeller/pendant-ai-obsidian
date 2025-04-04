# Limitless Life Logs

This application processes your Limitless Life Logs and organizes them into your Obsidian vault with a clean, hierarchical structure.</br></br>

## Prerequisites

1. macOS operating system</br>
2. Node.js installed on your system</br>
   - If you don't have Node.js, download it from [https://nodejs.org/](https://nodejs.org/)</br>
3. An Obsidian vault</br>
4. A Google Gemini API key</br>
5. A Limitless API key</br></br>

## Installation

1. Unzip the `Limitless_Life_Logs.zip` file to a location of your choice</br>
2. Open Terminal</br>
3. Navigate to the unzipped folder. Copy and paste this command, replacing the path with your actual path:</br>
   ```bash
   cd /path/to/unzipped/folder
   ```</br>
   For example, if you unzipped to Downloads:</br>
   ```bash
   cd ~/Downloads/Limitless_Life_Logs
   ```</br></br>

4. Make the installation script executable. Copy and paste this exact command:</br>
   ```bash
   chmod +x install.sh
   ```</br></br>

5. Run the installation script. Copy and paste this exact command:</br>
   ```bash
   ./install.sh
   ```</br></br>

6. Make the launcher script executable. Copy and paste this exact command:</br>
   ```bash
   chmod +x launcher.sh
   ```</br></br>

7. Run the launcher script. Copy and paste this exact command:</br>
   ```bash
   ./launcher.sh
   ```</br></br>

## First-Time Setup

When you first run the app, you'll need to provide:</br></br>

1. The path to your Obsidian vault</br>
   - To find your vault path:</br>
     1. Open Obsidian</br>
     2. Click your vault name at the bottom of the window</br>
     3. Click "Manage Vaults"</br>
     4. Click the three dots (...) next to your vault</br>
     5. Click "Reveal in Finder"</br>
   - Example path: `/Users/username/Documents/Obsidian`</br></br>

2. Choose the AI model (select option 2 for Google Gemini Pro)</br></br>

3. Enter your Google Gemini API key</br></br>

4. Enter your Limitless API key</br></br>

## How It Works

The app will:</br>
1. Fetch your lifelogs from the Limitless API</br>
2. Process them using the Google Gemini Pro model</br>
3. Organize them in your Obsidian vault with this structure:</br>
   ```
   Transcripts/
     2024/
       03/
         15/
           9:30am.md
           2:45pm.md
   ```</br></br>

Each note will contain:</br>
- A title</br>
- A summary of the conversation</br>
- Key points and insights</br>
- The raw conversation with timestamps</br></br>

## Troubleshooting

If you encounter any issues:</br>
1. Make sure all prerequisites are installed</br>
2. Check that your API keys are correct</br>
3. Verify your Obsidian vault path is correct</br>
4. Ensure you have write permissions in your Obsidian vault directory</br></br>

## Support

For support or questions, please contact your mom lol.</br>
