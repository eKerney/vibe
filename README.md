# vibe
### Resources
[https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/](https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/)

### Plan 
- Eric to checkout vibe coding 101 course 
- Eric is creating a catch all repo for vibe resources and projects 
- Eric is also doing some market research into Geospatial - UAS - Remote Sensing Domains.

### Vibe CLI Resources
- [Crush CLI: FASTEST AI Coder + Opensource! BYE Gemini CLI & ClaudeCode! (FREE QWEN 3 CODER)](https://youtu.be/kH8NFQ7TkiU?si=Az9Om19lkgbaRY0E)
- [neovmim + OpenCode](https://youtu.be/3szpSiGjBkQ?si=0Jy28ZXPlLt1KgqT)
- [Gemini CLI unstoppable coding beast](https://youtu.be/YAy7kd5Nqm0?si=gUduwvRdTa13SOoI)


#### Gemini CLI Features
With Gemini CLI you can:

Code Understanding & Generation
- Query and edit large codebases
- Generate new apps from PDFs, images, or sketches using multimodal capabilities
- Debug issues and troubleshoot with natural language

Automation & Integration
- Automate operational tasks like querying pull requests or handling complex rebases
- Use MCP servers to connect new capabilities, including media generation with Imagen, Veo or Lyria
- Run non-interactively in scripts for workflow automation

Advanced Capabilities
- Ground your queries with built-in Google Search for real-time information
- Conversation checkpointing to save and resume complex sessions
- Custom context files (GEMINI.md) to tailor behavior for your projects

🔗  GitHub Integration
- Use the Gemini CLI GitHub Action for automated PR reviews
- Automated issue triage and on-demand AI assistance directly in your repositories
- Seamless integration with your GitHub workflows

#### Workflow
Initiated using npx command and looks great, was able to authenticate using a gmail account.  
First asked Gemini to fix the pesky github PAT issue I've had on this machine using ubuntu 22.04 on WSL2.
Trying again after if set the incorrect path for the credential manager.
Seems that the problem is the lack of a graphical interface which is correct on WSL.
Finally the browser auth dialog popped up.

#### 8-14-2025
Installing Gemini via npm vs using the npx command to run without installing
```bash
npm install -g @google/gemini-cli
```
Planning to test using gemini to automate Market Research in the Geospatial Domain.   
OK so far this looks great! 
I asked gemini to create a jupyter notebook I could use to 'query' my linkedin feed for any post and information related to the Geospatial market.
It was able to generate a requirements.txt and notebook with what I had asked for, now on to testing!

#### 8-15-2025
The notebook didn't work at first, and had some characters that VSCode could not parse properly from the JSON.
This took a couple of tries, and Gem was able to eventually fix the issue when told what the errors were.
Instructions to follow for using cookie to query
1. Log in to LinkedIn in your regular browser (like Chrome or Firefox).                                                                                
2. Open the developer tools in your browser. You can usually do this by pressing F12 or right-clicking on the page and selecting "Inspect".                                                                                                                                          
3. Go to the "Application" or "Storage" tab and find the cookies for linkedin.com.                                                                     
4. Find the cookie named `li_at` and copy its value.

