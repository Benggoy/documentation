# Claude MCP Setup Instructions

## Quick Start

1. **Open Terminal** and navigate to this directory:
   ```bash
   cd "/Users/benitomartinlopez/Documents/Claude-Access"
   ```

2. **Make the script executable**:
   ```bash
   chmod +x setup-claude-mcp.sh
   ```

3. **Run the setup script**:
   ```bash
   ./setup-claude-mcp.sh
   ```

4. **Follow the prompts** to enter your GitHub Personal Access Token

5. **Restart Claude Desktop** completely (Cmd+Q then reopen)

## What the Script Does

✅ Checks for Node.js and npm installation  
✅ Installs filesystem and GitHub MCP servers globally  
✅ Prompts for your GitHub Personal Access Token  
✅ Creates the Claude Desktop configuration file  
✅ Copies configuration to the correct location  
✅ Sets proper file permissions  
✅ Tests the server installations  
✅ Provides troubleshooting information  

## Getting Your GitHub Token

1. Go to **GitHub.com** → Profile → **Settings**
2. Navigate to **Developer settings** → **Personal access tokens** → **Tokens (classic)**
3. Click **"Generate new token (classic)"**
4. Name it: `Claude MCP Access`
5. Select these scopes:
   - ✅ `repo` (Full control of private repositories)
   - ✅ `read:user` (Read user profile data)  
   - ✅ `user:email` (Access user email addresses)
6. Click **"Generate token"**
7. **Copy the token immediately** (you won't see it again!)

## Testing After Setup

Once Claude Desktop restarts, try these commands:

**Test Filesystem:**
```
List the files in my accessible directory
```

**Test GitHub:**
```
Show me my GitHub repositories
```

**Test Combined:**
```
Create a new file in my ManaeBenito Stuff folder and then show me my GitHub repos
```

## Troubleshooting

If something goes wrong:

1. **Check the logs**: Claude Desktop → Help → Developer Mode → MCP Log File
2. **Verify the config file**:
   ```bash
   cat ~/Library/Application\ Support/Claude/claude_desktop_config.json
   ```
3. **Test servers manually**:
   ```bash
   # Test filesystem server
   npx -y @modelcontextprotocol/server-filesystem "/Users/benitomartinlopez/Documents/Claude-Access"
   
   # Test GitHub server (replace YOUR_TOKEN)
   GITHUB_PERSONAL_ACCESS_TOKEN=YOUR_TOKEN npx -y @modelcontextprotocol/server-github
   ```

## Manual Configuration

If you prefer to set up manually, the configuration file should be placed at:
`~/Library/Application Support/Claude/claude_desktop_config.json`

## Need Help?

- Check the MCP documentation: https://modelcontextprotocol.io/
- Review Claude Desktop MCP guide: https://modelcontextprotocol.io/quickstart/user
- Join the community discussions on GitHub
