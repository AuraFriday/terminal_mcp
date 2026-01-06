# Terminal_mcp — Your AI Can Finally Do Terminal Work

**Stop typing commands. Start telling AI what you need done.**

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)](https://github.com/AuraFriday/mcp-link-server)

---

## 🎯 What This Means For You

### **AI That Actually Does Your Terminal Work**
No more copy-pasting commands. No more SSH sessions you forgot to close. No more "wait, which server was that on?" Just tell your AI what needs doing.

### **Every Connection Type, Zero Hassle**
Your AI can connect to anything: servers, microcontrollers, network equipment, IoT devices, industrial systems. Serial ports, SSH, Telnet, Bluetooth, WebSockets - all of it. You don't configure anything. It just works.

### **Rock-Solid Reliability**
9,000 lines of battle-tested code. Works on Windows, Linux, macOS. Cross-platform tested. Thread-safe. The kind of stability you need when AI is running your production deployments.

---

## ⚡ What Your AI Can Do For You

Imagine telling your AI:

- **"Flash firmware to all 50 ESP32 devices"** — It does them in parallel. Overnight. While you sleep.
- **"Configure these 100 Cisco switches"** — SSH to each one. Apply configs. Save. Done.
- **"Monitor the PLC and alert me if temperature exceeds 80°C"** — Continuous monitoring. You get notified when it matters.
- **"Figure out what protocol this unknown device speaks"** — AI explores, analyzes logs, documents the protocol.
- **"Build Go binaries on RHEL7 for universal deployment"** — SSH, rebuild dependencies, compile, ship.
- **"Collect data from all BLE temperature sensors in the building"** — Discover, connect, read, aggregate.

**Terminal_mcp makes it possible.** Your AI gets full terminal access - serial ports, network devices, remote servers, IoT gadgets - everything. You get results without touching a keyboard.

---

## 🚀 How It Feels To Use

**You:** "Connect to the ESP32 and update its firmware."

**Your AI:** 
- Finds the serial port
- Opens connection
- Enters bootloader mode
- Flashes firmware
- Verifies upload
- Reports success

**You see:** A single message - "Firmware updated successfully. Device rebooted and ready."

**No commands. No syntax. No manual work.** Just results.

---

## 🌟 What Makes This Different

### **AI Can Actually Finish Jobs**

Most tools let AI *suggest* commands. Terminal_mcp lets AI *execute* them. Big difference:

- **Before:** "Here's the SSH command you need to run..."
- **After:** "I've configured all 100 switches. Here's the summary..."

### **Works With Everything You Have**

Your AI can control:
- **Servers** via SSH (with 2FA/OTP support!)
- **Microcontrollers** via serial ports (Arduino, ESP32, STM32)
- **Network equipment** via Telnet/SSH (Cisco, Juniper, Mikrotik)
- **IoT devices** via Bluetooth LE (sensors, beacons, wearables)
- **Industrial systems** via Modbus, RFC2217, custom protocols
- **Local programs** via terminal emulation (build scripts, test suites)

### **Intelligent Automation**

Terminal_mcp isn't just "run this command." It's:
- **Pattern matching** - AI waits for specific responses before proceeding
- **Smart sequencing** - Multi-step operations execute atomically
- **Persistent auto-reconnect** - Sessions survive device resets, unplugs, reboots - never miss a boot log
- **SFTP file transfer** - Upload/download files over SSH without interrupting your shell
- **Error recovery** - Connection drops don't lose data
- **Automatic logging** - Everything captured for debugging and audit
- **Progress tracking** - Long operations report status

### **Safe & Secure**

- **Passwords never logged** to disk
- **Audit trails** for every session
- **Host key verification** for SSH
- **Session isolation** - multiple operations never interfere
- **Privilege elevation** only with your explicit approval

---

## 🎭 Real-World Stories

### **DevOps Engineer: "I Don't Touch Production Anymore"**

*"I tell Claude 'deploy v2.3 to production' and it:*
- *SSH to each server*
- *Stops services gracefully*
- *Updates code*
- *Runs migrations*
- *Starts services*
- *Verifies health checks*
- *Rolls back if anything fails*

*All I do is approve the plan. No typing. No mistakes. No 3am incidents from typos."*

### **Hardware Hacker: "Firmware Updates Used To Take Days"**

*"I have 200 ESP32 devices in the field. Before Terminal_mcp, I'd spend a week driving to each location with a laptop.*

*Now I tell my AI 'update firmware on all remote devices' and it:*
- *Connects via SSH to local gateways*
- *Flashes each ESP32 via serial*
- *Verifies bootup*
- *Tests connectivity*

*It runs overnight. In the morning, I have a report. Days of work → one sentence."*

### **Embedded Developer: "I Finally Stopped Missing Boot Logs"**

*"My ESP32-C6 uses USB Serial JTAG - every reset makes Windows re-enumerate the port. I'd frantically try to reconnect after each flash, missing crucial boot messages every time.*

*With Terminal_mcp's auto-reconnect, I open ONE session and it survives everything:*
- *Device not plugged in? It waits.*
- *Device resets? It reconnects instantly.*
- *DFU mode? It stays connected.*
- *Crash loop? It captures every single boot.*

*I tested it - 5 reconnects through unplugs, resets, and DFU transitions. Captured 31KB of boot logs. Zero manual intervention. My AI can finally debug crashes that happen when I'm not watching."*

### **DevOps Engineer: "Deployments Are Actually One Command Now"**

*"I used to juggle three tools: SSH for commands, SCP for file transfers, and a browser for monitoring. Every deployment was a context-switching nightmare.*

*Now I tell my AI 'deploy v2.4 to production' and it:*
- *SSH into each server*
- *Uploads the new binary via SFTP (same session!)*
- *Runs the deployment script*
- *Downloads the logs to verify*
- *All without me opening a single terminal*

*The SFTP just works - it uses the existing SSH connection, so no extra authentication. Worked perfectly the first time I tried it."*

### **Security Researcher: "Reverse Engineering Is Actually Fun Now"**

*"Found a weird IoT device. Unknown protocol. Before, I'd spend days in Wireshark making sense of hex dumps.*

*I told my AI 'figure out what this device speaks.' It:*
- *Connected via Bluetooth LE*
- *Enumerated all GATT services*
- *Tried different commands*
- *Analyzed responses*
- *Generated protocol documentation*

*What used to take me a week took Claude 20 minutes. And it was thorough."*

### **Factory Manager: "We Actually Monitor Everything Now"**

*"We have PLCs, sensors, and industrial controllers everywhere. Modbus, proprietary serial protocols, you name it.*

*Setting up monitoring used to mean hiring consultants. Now I tell my AI 'monitor PLC temperatures every 10 seconds and alert if any exceed 80°C.'*

*It just works. Continuous monitoring. Real alerts. No consultants. No custom programming."*

---

## 🌐 The Real Power: Everything Works Together

**Here's what makes Terminal_mcp different from every other automation tool:**

### **It's Not Alone**

Terminal_mcp is part of the MCP-Link ecosystem. Your AI has access to:

- **Terminal_mcp** - Connect to any device, any protocol
- **Python execution** - Run code with full tool access
- **Chrome browser** - Your actual browser, logged in, with all your sessions
- **SQLite + Embeddings** - Semantic memory and search
- **Desktop control** - Windows automation, any app
- **WhatsApp** - Send messages, read conversations
- **OpenRouter** - 500+ AI models on demand
- **Local LLMs** - Private, offline intelligence
- **Context7** - Live documentation for any library
- **User GUI** - HTML popups for forms and confirmations
- **And 20+ more tools...**

### **They All Talk To Each Other**

This is where it gets wild:

**Any tool can call any other tool.**

Your AI orchestrating a terminal session can:
- Query SQLite to find which servers need updates
- Use Chrome to download the latest firmware
- Show you a GUI popup to confirm the operation
- Execute the updates via Terminal_mcp
- Store results back in SQLite with semantic embeddings
- Send you a WhatsApp when it's done

**And anything running INSIDE the terminal can do the same.**

A Python script you run via SSH can:
- Call back to Terminal_mcp to open new connections
- Use the browser to authenticate with web services
- Query semantic search to find relevant configurations
- Show GUI popups on your local machine
- Call other AI models for decision-making

### **It Runs Forever, Everywhere**

- **24/7/365 Orchestration** - Python scripts coordinate everything
- **Localhost, LAN, WAN** - Works across your entire network
- **Always TLS-secured** - End-to-end encryption everywhere
- **Zero configuration** - Tools auto-discover each other

### **This Is What Sci-Fi Promised**

Remember those movies where you tell a computer "handle it" and it just... does?

That's this.

Not someday. Not with a $50,000 enterprise license. Not after six months of configuration.

**Now. Free. Local. Secure.**

Your AI has:
- **Terminal access** to any device
- **Browser control** with your actual sessions
- **Semantic memory** of everything you've done
- **Desktop automation** for any application
- **Communication tools** to notify you
- **Intelligence** from local or cloud models
- **Persistence** to run workflows 24/7

**And every tool works with every other tool, in combinations the AI invents on the fly.**

### **Example: The Impossible Becomes Trivial**

**You:** "Monitor PLC temperatures, and if any exceed 80°C, check the maintenance database for that unit, open a support ticket in our web portal, and notify the on-call engineer via WhatsApp."

**Your AI:**
1. Terminal_mcp connects to PLC via Modbus
2. Python orchestration loop monitors readings
3. SQLite semantic search finds maintenance records
4. Chrome automation opens support portal (using your logged-in session)
5. GUI popup asks you to confirm ticket details
6. Browser submits the ticket
7. WhatsApp sends notification to on-call
8. SQLite stores incident with embeddings for future reference

**All automatic. All working together. All secure.**

**You never wrote a single line of integration code.**

This isn't like n8n where you drag boxes and pray the connectors work.

This isn't like LangChain where you fight with chains and agents.

This isn't like IFTTT where you're limited to pre-built triggers.

**This is AI with actual intelligence, actual tools, and actual results.**

The science fiction future isn't coming.

**It's here. It's free. It's yours.**

---

## 🔧 What Your AI Can Actually Control

### **Network Infrastructure**
- Configure routers and switches
- Deploy firewall rules
- Update device firmware
- Monitor network health
- Automate backups

### **IoT & Embedded Systems**
- Flash microcontroller firmware
- Read sensor data
- Control actuators
- Monitor device health (through resets - auto-reconnect captures every boot!)
- Debug communication protocols
- Capture crash logs (session survives device resets)

### **Industrial Equipment**
- Program PLCs
- Monitor sensors
- Control motors and relays
- Read Modbus registers
- Automate quality control

### **Remote Servers**
- Deploy applications
- Run build processes
- Execute maintenance scripts
- Monitor logs
- Manage services
- **Transfer files via SFTP** (upload firmware, download logs - without interrupting your shell session!)

### **Bluetooth Devices**
- Read fitness tracker data
- Control smart home devices
- Collect sensor readings
- Reverse-engineer protocols
- Monitor beacons

### **Development Workflows**
- Build cross-platform binaries
- Run test suites
- Deploy to staging
- Monitor compilation logs
- Automate DevOps pipelines

---

## 🧵 The Technical Magic (That You Don't Think About)

Terminal_mcp handles all the hard stuff so your AI can focus on your problem:

- **Thread-safe architecture** - Multiple operations never interfere
- **Persistent auto-reconnect** - Devices can reset, unplug, reboot - session survives it all
- **Smart buffering** - No data loss, even at high speeds
- **Protocol translation** - AI speaks commands, Terminal_mcp speaks protocols
- **Platform abstraction** - Same AI commands work on Windows, Linux, macOS
- **Dependency management** - Missing libraries? Auto-installed.
- **Error recovery** - Failures are detected and handled gracefully

**You never see this complexity.** Your AI just gets reliable results.

---

## 🔌 Auto-Reconnect: Never Miss Another Boot Log

**This changes everything for embedded development.**

### The Problem Before

Working with microcontrollers means constantly losing your serial connection:

- ESP32 resets? **Port vanishes.** Connection lost. Boot logs gone.
- Device crashes? **You missed what happened.**
- Flashing firmware? **Unplug, replug, frantically try to reconnect** before boot finishes.
- USB Serial JTAG devices? **Windows re-enumerates the port on every reset.**

You'd tell your AI "watch the serial output" and two minutes later it's staring at a dead connection while your device rebooted three times.

### The Solution: Persistent Sessions

Terminal_mcp's auto-reconnect feature creates **sessions that survive anything:**

```
AI opens session on COM22 with auto_reconnect=true
↓
Device not plugged in yet? Session waits, polling every 250ms.
↓
You plug in the device → Instant connection, boot logs captured from first byte
↓
Device resets mid-operation? Session detects disconnect, enters reconnect mode
↓
Port re-appears → Automatic reconnection, captures next boot sequence
↓
Repeat forever. One session. Every boot log. Zero manual intervention.
```

### Real Test Results

We tested this with an ESP32-C6 Super Mini (which manages its own USB serial - no dedicated FTDI chip):

| Action | Result |
|--------|--------|
| Open session before device plugged in | ✅ Session waits for port |
| Plug in device | ✅ Instant connection, full boot log captured |
| Unplug device | ✅ Session detects disconnect, enters reconnect mode |
| Plug back in | ✅ Reconnects, captures boot from first byte |
| Press RESET button | ✅ Survives port re-enumeration, captures reboot |
| Enter DFU mode (BOOT+RESET) | ✅ Stays connected (silent - DFU doesn't output) |
| Exit DFU (RESET) | ✅ Captures boot sequence immediately |
| Multiple rapid resets | ✅ Catches every single boot |

**5 successful reconnects through various resets. 31KB of boot logs captured. Zero manual intervention.**

### Why This Matters

**Before auto-reconnect:**
- "Quick, the device is booting! Open PuTTY! Which COM port? Too late, missed it."
- "It crashed but I don't know why - I wasn't connected when it happened."
- "I need to capture boot logs but the device resets itself every 30 seconds."

**With auto-reconnect:**
- AI opens session once. Captures every boot. Forever.
- Device crashes at 3am? Boot log is in the session file.
- Firmware flashing requires reset? AI sees the entire reboot sequence.
- Walk away, come back, everything's logged.

### How To Use It

Just add `auto_reconnect: true` when opening a session:

```json
{
  "operation": "open_session",
  "endpoint": "COM22",
  "baud_rate": 115200,
  "auto_reconnect": true,
  "auto_reconnect_interval_ms": 250
}
```

That's it. The session now survives:
- Device not yet plugged in (waits for it)
- Device unplugged/replugged
- Device resets (button, crash, watchdog, OTA update)
- USB re-enumeration (common with USB Serial JTAG chips)
- Network hiccups (for TCP/Telnet/WebSocket connections)

### Session Status Reporting

Your AI always knows the connection state:

```json
{
  "auto_reconnect": {
    "enabled": true,
    "interval_ms": 250,
    "connection_state": "port_missing",
    "reconnect_attempts": 47,
    "successful_reconnects": 5,
    "total_disconnected_seconds": 218.0
  }
}
```

States include:
- `connected` - Active and reading data
- `port_missing` - Device unplugged, waiting for it
- `reconnecting` - Port exists but connection failed, retrying

### Perfect For

- **ESP32/ESP8266** - USB Serial JTAG that re-enumerates on reset
- **Arduino** - Bootloader that grabs the port during upload
- **STM32** - DFU mode transitions
- **Any USB device** - That Windows loves to re-enumerate
- **Network devices** - That drop connections during config changes
- **Flaky USB cables** - We've all got that one cable...
- **Remote devices** - Where you can't physically reconnect

### The Bigger Picture

This isn't just convenience. **This is the difference between "AI-assisted" and "AI-automated."**

Without auto-reconnect, your AI can only help while connected. One reset and it's blind.

With auto-reconnect, your AI can:
- Monitor a device 24/7 through any number of resets
- Flash firmware and watch the reboot
- Debug crash loops by capturing every boot
- Coordinate multi-device operations where devices reset each other
- Run unattended overnight and have complete logs in the morning

**Your AI finally has the same persistence you do.** It doesn't give up when the device hiccups. It waits, reconnects, and continues the job.

---

## 📁 SFTP File Transfer: Move Files Without Leaving Your Session

**SSH sessions now include full SFTP support.**

### The Problem Before

You're debugging a remote server via SSH. You need to:
- Upload a new binary
- Download some logs
- Check what files are in a directory

**Before:** Open a separate SFTP client, enter credentials again, navigate to the right folder, transfer, switch back to your terminal...

**After:** Just ask your AI. It uses the same SSH session.

### How It Works

Terminal_mcp opens a **separate SFTP channel** over your existing SSH connection. This means:

- ✅ **No new authentication** - uses your existing session
- ✅ **Shell stays active** - file transfers don't interrupt your terminal
- ✅ **Progress tracking** - see bytes transferred, speed, elapsed time
- ✅ **Bidirectional** - upload AND download

### Available Operations

```json
// Upload firmware to remote server
{
  "operation": "sftp_put",
  "session_id": "ssh_1",
  "local_path": "C:/builds/firmware-v2.3.bin",
  "remote_path": "/home/deploy/firmware/app.bin"
}

// Download logs for analysis
{
  "operation": "sftp_get",
  "session_id": "ssh_1",
  "remote_path": "/var/log/app.log",
  "local_path": "C:/logs/remote-app.log"
}

// List remote directory
{
  "operation": "sftp_list",
  "session_id": "ssh_1",
  "remote_path": "/home/deploy/"
}
```

### Real-World Use Cases

- **Deploy binaries** to remote build servers
- **Download crash dumps** for local analysis
- **Upload config files** during remote setup
- **Backup remote data** before making changes
- **Transfer firmware** to embedded Linux devices
- **Collect logs** from multiple servers automatically

### Works Perfectly With Your Workflow

Your AI can now:
1. SSH into a server
2. Run commands to prepare a deployment
3. **Upload the new binary via SFTP**
4. Run commands to restart services
5. **Download logs via SFTP** to verify
6. All in one session. All automated.

**No context switching. No separate tools. No re-authentication.**

---

## 🌍 Works Everywhere You Do

| What You Have | Your AI Can Control It |
|---------------|----------------------|
| Windows PC | ✅ Serial, SSH, Bluetooth, everything |
| Linux Server | ✅ Full terminal access, all protocols |
| macOS Laptop | ✅ Complete hardware support |
| Raspberry Pi | ✅ GPIO, serial, network - all accessible |
| WSL | ✅ Windows + Linux hybrid setups |
| Remote Servers | ✅ SSH with 2FA/OTP support |
| Embedded Linux | ✅ Serial console, Telnet, SSH |
| Microcontrollers | ✅ Serial bootloaders, JTAG |
| Network Equipment | ✅ Cisco, Juniper, Mikrotik, etc. |
| IoT Devices | ✅ MQTT, Modbus, custom protocols |

---

## 🚀 Get Started In Seconds

**1. Install MCP-Link** (includes Terminal_mcp)

[Download for your platform →](https://aurafriday.com/downloads/)

**2. Tell your AI what to do**

That's it. Seriously.

Your AI (Claude, ChatGPT, local models) can now:
- Connect to any device
- Execute commands
- Monitor output
- React to events
- Complete complex workflows

**No configuration. No API keys. No setup.** It just works.

---

## 🔐 Security You Can Trust

### **Your Data Stays Yours**
- All operations run locally on your machine
- No cloud uploads unless you choose cloud AI
- Credentials never cached or persisted
- Session logs under your control

### **Built By Security Experts**
- Created by Christopher Nathan Drake (inventor of the #1 most-cited cybersecurity patent)
- 43+ years of professional software development
- Proven track record with 15,000+ users on previous projects

### **Enterprise-Grade Safety**
- Audit trails for compliance
- Privilege elevation requires approval
- Host key verification for SSH
- Encrypted connections for all network protocols

---

## 💡 Why This Matters

**Before Terminal_mcp:**

You: "Can you help me update firmware on my ESP32?"  
AI: "Sure! Here's the command: `esptool.py --port /dev/ttyUSB0 write_flash...`"  
You: *Opens terminal, copies command, fixes typo, runs it, monitors output, reports back to AI*

**With Terminal_mcp:**

You: "Update the ESP32 firmware."  
AI: "Done. Firmware v2.3 flashed successfully. Device rebooted and online."  
You: *Continues working on actual problems*

**That's the difference.** AI that works *for* you, not *with* you.

---

## 🎓 What You Can Stop Doing

### ❌ Things You Don't Need To Do Anymore

- **Copy-pasting commands** from AI into terminals
- **Checking if commands worked** and reporting back
- **Opening 17 SSH sessions** to 17 different servers
- **Remembering device serial port names** (was it COM3 or COM5?)
- **Manually monitoring long-running operations**
- **Writing shell scripts** to automate repetitive tasks
- **Googling "how to flash ESP32 bootloader"** for the 50th time
- **Spending weekends deploying updates**

### ✅ Things You Can Start Doing Instead

- **Telling AI what result you want** and getting it
- **Scaling operations** to hundreds of devices effortlessly
- **Automating complex workflows** with natural language
- **Sleeping through deployments** while AI handles them
- **Focusing on architecture** instead of terminal commands
- **Trusting systems to just work** because they're monitored
- **Having weekends** back

---

## 🏆 From The Creator

**Christopher Nathan Drake**  
*Founder, Aura Friday*

*"I've spent 43 years building systems that need to be absolutely reliable. Terminal_mcp is the result of that experience - battle-hardened architecture that lets AI agents safely control real hardware and infrastructure.*

*This isn't a proof of concept. It's production-grade code trusted by developers worldwide. When your AI needs to flash 1000 devices or deploy to 100 servers, this is what makes it possible."*

**Credentials:**
- Creator of [CryptoPhoto.com](https://www.cryptophoto.com)
- Inventor of the [#1 most-cited cybersecurity patent](https://patents.google.com/patent/US6328A/en#citedBy) globally
- 43+ years professional software development
- Dozens of international security awards
- TEDx speaker on cybersecurity

---

## 🤝 Join The Community

### **Who Uses Terminal_mcp?**

- **DevOps Engineers** automating infrastructure deployments
- **Hardware Hackers** flashing IoT firmware at scale
- **Security Researchers** reverse-engineering protocols
- **Factory Managers** monitoring industrial equipment
- **Embedded Developers** debugging microcontrollers
- **Network Admins** configuring enterprise equipment
- **Makers** building smart home automation
- **Researchers** collecting sensor data

### **What They're Building**

- Fully automated CI/CD pipelines
- IoT sensor networks with 1000+ devices
- Industrial monitoring and control systems
- Smart home automation that actually works
- Firmware update systems for remote devices
- Network infrastructure management tools
- Protocol analysis and documentation systems
- Custom hardware testing frameworks

---

## 📦 What's Included

Terminal_mcp is part of **MCP-Link** - the complete AI toolbox.

**When you install MCP-Link, you get:**
- ✅ Terminal_mcp (this tool)
- ✅ Browser automation
- ✅ Desktop control
- ✅ Semantic memory
- ✅ Python execution
- ✅ SQLite with embeddings
- ✅ Remote AI models
- ✅ Local AI models
- ✅ Live documentation
- ✅ And more...

**All integrated. All "just works."**

[See the full MCP-Link ecosystem →](https://aurafriday.com)

---

## 🔗 Learn More

- **Homepage:** [https://aurafriday.com](https://aurafriday.com)
- **Download:** [https://aurafriday.com/downloads/](https://aurafriday.com/downloads/)
- **Documentation:** [https://github.com/AuraFriday/mcp-link-server](https://github.com/AuraFriday/mcp-link-server)
- **Report Issues:** [https://github.com/AuraFriday/mcp-link/issues](https://github.com/AuraFriday/mcp-link/issues)

---

## 💬 Get Support

- **Email:** [email protected]
- **Phone:** +61 414 505 452  
- **Address:** PO Box 988, Noosa Heads, QLD 4567, Australia

---

## ✨ The Bottom Line

**Most tools let AI suggest commands.**

**Terminal_mcp lets AI execute them.**

That's not a small difference. That's the difference between an assistant that talks and a co-worker that ships.

- ✅ **No more copy-pasting** between AI and terminal
- ✅ **No more context switching** between conversations and commands
- ✅ **No more manual monitoring** of long operations
- ✅ **No more "I'll do that later"** forgotten tasks
- ✅ **No more weekend deployments** because automation is hard

**Just tell your AI what needs doing. Watch it happen.**

---

**Stop typing. Start delegating.**

[Download MCP-Link →](https://aurafriday.com/downloads/)

---

## License & Copyright

Copyright © 2025 Christopher Nathan Drake

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

AI Training Permission: You are permitted to use this software and any
associated content for the training, evaluation, fine-tuning, or improvement
of artificial intelligence systems, including commercial models.

SPDX-License-Identifier: Apache-2.0

---

*Free forever. Works with ChatGPT, Claude, local models, and any AI that speaks MCP.*

*Part of the MCP-Link project — Turn any AI into an active co-worker*

