# Terminal_mcp — Your AI Can Finally Do Terminal Work

**Stop typing commands. Start telling AI what you need done.**

[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](LICENSE)
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

## 🔒 TLS/SSL Encryption: Secure Communications Built-In

**Direct TLS encryption for all your secure protocols.**

### The Problem Before

Connecting to secure mail servers, encrypted services, or TLS-wrapped protocols meant:
- Finding the right tool for each protocol
- Managing certificates manually
- Hoping the encryption "just works"
- No visibility into what's actually encrypted

**After:** Terminal_mcp handles TLS 1.3 encryption natively. Just add `use_tls: true`.

### What Works Right Now

Terminal_mcp supports **direct TLS connections** for any TCP-based protocol:

| Protocol | Port | Status | Use Case |
|----------|------|--------|----------|
| **SMTPS** | 465, 587, custom | ✅ **Production Ready** | Send encrypted email |
| **IMAPS** | 993, custom | ✅ **Production Ready** | Read mail securely |
| **POP3S** | 995, custom | ✅ **Production Ready** | Download mail encrypted |
| **HTTPS** | 443, custom | ✅ **Production Ready** | Direct HTTP over TLS |
| **Secure Telnet** | Any port | ✅ **Production Ready** | Encrypted device management |
| **RFC2217 + TLS** | Any port | ✅ **Production Ready** | Secure remote serial ports |
| **Custom Protocols** | Any port | ✅ **Production Ready** | Your encrypted services |

### Real Test Results

We tested with a production mail server using secure ports:

**SMTPS (Port 465):**
- ✅ TLS 1.3 connection established
- ✅ Cipher: TLS_AES_256_GCM_SHA384 (256-bit encryption)
- ✅ **Successfully sent email**
- ✅ Message accepted: `607MPBrB173441`
- ✅ Email delivered and verified in mailbox

**IMAPS (Port 993):**
- ✅ TLS 1.3 connection established
- ✅ Authenticated successfully
- ✅ Listed mailboxes
- ✅ **Read 3 messages** including the test email we sent
- ✅ Fetched headers and content over encrypted connection

**POP3S (Port 995):**
- ✅ TLS 1.3 connection established
- ✅ Server greeting received encrypted
- ✅ All communication secured

### How To Use It

Just add `use_tls: true` when opening a connection:

```json
// Connect to secure SMTP
{
  "operation": "open_session",
  "endpoint": "tcp://mail.example.com:465",
  "use_tls": true,
  "tls_verify": false  // Optional: skip certificate verification
}

// Connect to secure IMAP
{
  "operation": "open_session",
  "endpoint": "tcp://mail.example.com:993",
  "use_tls": true
}

// Any TCP protocol with TLS
{
  "operation": "open_session",
  "endpoint": "tcp://device.local:8883",
  "use_tls": true,
  "tls_server_hostname": "device.local"  // Optional: for SNI
}
```

### Certificate Information

Get detailed TLS connection info:

```json
{
  "operation": "get_tls_info",
  "session_id": "mcu_1"
}
```

Returns:
- TLS protocol version (e.g., "TLSv1.3")
- Cipher suite details
- Certificate subject and issuer
- SHA256 fingerprint
- Validity dates
- Subject Alternative Names (SAN)

### Security Features

- ✅ **TLS 1.3 by default** - Latest, most secure protocol
- ✅ **Strong ciphers** - AES-256-GCM and similar
- ✅ **Certificate verification** - Optional but available
- ✅ **SNI support** - Server Name Indication for virtual hosts
- ✅ **Fingerprint extraction** - Verify server identity
- ✅ **No credential caching** - Your responsibility to manage trust

### Transport-Agnostic Design

TLS works with any stream-based transport:
- ✅ TCP connections
- ✅ Telnet protocol
- ✅ RFC2217 (remote serial ports)
- ✅ Unix domain sockets
- ✅ Named pipes

**The same `use_tls: true` flag works everywhere.**

### Coming Soon: STARTTLS

**STARTTLS support is in development** for protocols that upgrade from plaintext to encrypted:

- SMTP STARTTLS (port 25 → encrypted)
- IMAP STARTTLS (port 143 → encrypted)
- POP3 STARTTLS (port 110 → encrypted)
- FTP over TLS (FTPS)
- XMPP STARTTLS

The `upgrade_to_tls` operation will let you:
1. Connect in plaintext
2. Negotiate STARTTLS with the server
3. Upgrade the connection to TLS
4. Continue with encrypted communication

**Status:** Core implementation complete, post-upgrade communication being refined.

### Perfect For

- **Secure email** - Send/receive mail with encryption
- **IoT devices** - Encrypted MQTT, custom protocols
- **Remote management** - Secure device configuration
- **API access** - HTTPS without a full HTTP client
- **Industrial systems** - Encrypted Modbus, proprietary protocols
- **Network equipment** - Secure Telnet, encrypted management

### Why This Matters

Before, connecting to secure services meant:
- Finding protocol-specific tools
- Managing multiple clients
- Hoping encryption works
- No visibility into security details

**Now:** Your AI can securely connect to any TLS-enabled service, send encrypted email, read secure mailboxes, and access encrypted APIs - all with the same simple interface.

**All communication is encrypted with TLS 1.3. All certificates are inspectable. All under your control.**

---

## 🌐 IPv6 Support: Future-Proof Networking

**Full IPv6 support for all network protocols.**

### The Modern Internet Needs IPv6

As IPv4 addresses run out, more services are moving to IPv6. Terminal_mcp supports both IPv4 and IPv6 seamlessly:

- ✅ **Dual-stack support** - Automatically uses IPv4 or IPv6 as needed
- ✅ **Standard bracket notation** - `tcp://[2001:db8::1]:443`
- ✅ **Works with all protocols** - TCP, Telnet, SSH, RFC2217, TLS
- ✅ **Automatic fallback** - Tries all addresses until one succeeds
- ✅ **No configuration needed** - Just use IPv6 addresses

### IPv6 Address Formats

Terminal_mcp accepts standard IPv6 notation with brackets:

```json
// IPv6 with TLS
{
  "operation": "open_session",
  "endpoint": "tcp://[2a01:4ff:f0:4ca4::1]:993",
  "use_tls": true
}

// IPv6 SSH
{
  "operation": "open_session",
  "endpoint": "ssh://user@[2001:db8::1]:22",
  "ssh_password": "password"
}

// IPv6 Telnet
{
  "operation": "open_session",
  "endpoint": "telnet://[fe80::1]:23"
}

// IPv6 localhost
{
  "operation": "open_session",
  "endpoint": "tcp://[::1]:8080"
}
```

### Real IPv6 Test Results

We tested with a production server over IPv6:

**IMAPS over IPv6 + TLS 1.3:**
- ✅ Connected to `tcp://[2a01:4ff:f0:4ca4::1]:52993`
- ✅ TLS 1.3 handshake successful
- ✅ Authenticated and read mailbox
- ✅ All IMAP commands worked perfectly
- ✅ **Full IPv6 + TLS encryption working!**

### How It Works

Terminal_mcp uses Python's `getaddrinfo()` which:
1. Resolves both IPv4 and IPv6 addresses
2. Tries each address family in order
3. Falls back automatically if one fails
4. Works transparently with all protocols

**You don't need to know if a server is IPv4 or IPv6** - just use the address and it works.

### Use Cases

- **Modern cloud providers** - Many use IPv6-only instances
- **ISP IPv6 deployments** - Residential IPv6 is increasingly common
- **IoT devices** - Many support IPv6 for direct addressing
- **Future-proofing** - Your automation works as the internet transitions
- **Dual-stack testing** - Test both IPv4 and IPv6 connectivity

### Platform Support

IPv6 works on all platforms:
- ✅ **Windows 10/11** - Full IPv6 support tested
- ✅ **Linux** - Native IPv6 support
- ✅ **macOS** - Native IPv6 support
- ✅ **WSL** - IPv6 works through Windows host

**Your AI can now connect to the modern internet, both IPv4 and IPv6!**

---

## 🎯 What Your AI Can Actually Control (Products & APIs)

**The terminal tool isn't just for hardware - it's your gateway to controlling hundreds of software products.**

When you ask your AI to "control OBS Studio" or "send data to my CNC mill," it needs to know that the **terminal tool** is the right choice. This table shows exactly which products your AI can control through network protocols, serial ports, and local sockets.

### 🎬 Video, Streaming & Broadcasting

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **OBS Studio** | WebSocket (obs-websocket) | TCP 4455 | Start/stop recording, switch scenes, control sources, adjust audio |
| **vMix** | HTTP REST + TCP | HTTP 8088, TCP 8099 | Switch inputs, control overlays, trigger recordings, adjust audio |
| **Wirecast** | HTTP API | HTTP 8080 | Scene switching, source control, streaming control |
| **Streamlabs Desktop** | WebSocket | TCP 59650 | Scene control, source management, alerts |
| **Twitch EventSub** | WebSocket | WSS 443 | Receive live events, chat integration, channel updates |
| **YouTube Live API** | HTTP REST | HTTPS 443 | Stream control, chat moderation, analytics |
| **DaVinci Resolve** | Python/Lua API | Local script execution | Timeline editing, color grading, render control |
| **FFmpeg** | Command line + pipes | STDIN/STDOUT | Video transcoding, streaming, format conversion |
| **VLC Media Player** | HTTP/RC interface | HTTP 8080, TCP 4212 | Playback control, playlist management, streaming |
| **mpv** | JSON IPC | Unix socket/Named pipe | Playback control, property queries, event monitoring |

**Example**: "Start recording in OBS" → `terminal` opens WebSocket to `ws://localhost:4455`, sends JSON-RPC command

### 🎵 Music Production & Audio

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Ableton Live** | OSC (Open Sound Control) | UDP 11000/11001 | Control tracks, clips, effects, automation, tempo |
| **Reaper** | OSC + ReaScript | UDP 8000, Local API | Full DAW automation, plugin control, rendering |
| **Bitwig Studio** | OSC + Control Surface API | UDP custom | Track control, device automation, clip launching |
| **Pro Tools** | EUCON protocol | TCP 3293 | Transport control, mixing, plugin automation |
| **Logic Pro** | OSC via plugins | UDP custom | Limited control via third-party OSC bridges |
| **Traktor Pro** | MIDI over network | UDP/RTP-MIDI | Deck control, effects, mixing (requires MIDI setup) |
| **VCV Rack** | OSC + CV Bridge | UDP custom | Modular synthesis control, parameter automation |
| **SuperCollider** | OSC | UDP 57110/57120 | Synthesis control, live coding, sound generation |
| **Pure Data** | OSC/UDP | UDP custom | Patch control, audio processing, synthesis |
| **Max/MSP** | OSC/UDP | UDP custom | Patch automation, audio/video processing |

**Example**: "Set Ableton tempo to 128 BPM" → `terminal` sends OSC message to UDP 11000: `/song/tempo 128`

### 🏭 CNC, 3D Printing & Manufacturing

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Roland Modela (MDX series)** | RML-1 commands | Serial/USB | Milling operations, tool paths, coordinate control |
| **GRBL CNC Controllers** | G-code | Serial (115200 baud) | CNC control, jogging, homing, coordinate systems |
| **Marlin (3D Printers)** | G-code | Serial (115200/250000 baud) | Print control, temperature, movement, bed leveling |
| **Klipper** | HTTP API (Moonraker) | HTTP 7125 | Advanced 3D printer control, macros, monitoring |
| **OctoPrint** | REST API | HTTP 5000 | 3D print job control, monitoring, webcam access |
| **PrusaSlicer** | HTTP (PrusaLink) | HTTP 80 | Direct printer control, job upload, monitoring |
| **Cura** | Plugin API | Local Python | Slicing automation, settings control |
| **Mach3/Mach4** | Modbus/Plugin API | Serial/TCP | CNC machine control, toolpath execution |
| **LinuxCNC** | HAL interface | Local IPC | Real-time CNC control, custom machine configs |
| **Universal Robots** | TCP/IP Socket | TCP 30001-30003 | Robot arm control, movement, I/O, safety |
| **FANUC Robots** | KAREL/TCP | TCP custom | Industrial robot control, program execution |
| **ABB Robots** | RAPID/EGM | TCP/UDP | Robot control, real-time motion, I/O |

**Example**: "Mill a 10cm square" → `terminal` opens serial port, sends RML-1 commands to Roland mill

### 🌐 Web Browsers & Automation

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Chrome/Chromium** | Chrome DevTools Protocol | WebSocket 9222 | Full browser automation, DOM access, network monitoring |
| **Microsoft Edge** | Edge DevTools Protocol | WebSocket 9222 | Same as Chrome (Chromium-based) |
| **Firefox** | Remote Debugging Protocol | WebSocket 6000 | Browser automation, debugging, profiling |
| **Selenium Grid** | WebDriver HTTP | HTTP 4444 | Multi-browser test automation |
| **Playwright** | WebSocket | Local/Remote WS | Cross-browser automation, testing |
| **Puppeteer** | CDP over WebSocket | Local WS | Headless Chrome automation |

**Example**: "Take screenshot of website" → `terminal` connects to Chrome CDP on port 9222, sends `Page.captureScreenshot`

### 🏠 Smart Home & IoT

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Home Assistant** | REST API + WebSocket | HTTP 8123 | Control all connected devices, automation, scenes |
| **MQTT Broker** (Mosquitto) | MQTT | TCP 1883/8883 | Pub/sub messaging for IoT devices |
| **Sonoff Devices** | HTTP (DIY mode) + MQTT | HTTP 8081, MQTT 1883 | Switch control, sensor reading, firmware updates |
| **Philips Hue** | HTTP REST | HTTP 80 | Light control, scenes, groups, schedules |
| **LIFX Bulbs** | HTTP + LAN protocol | HTTP 80, UDP 56700 | Light control, effects, color changes |
| **TP-Link Kasa** | TCP Protocol | TCP 9999 | Smart plug/bulb control |
| **Shelly Devices** | HTTP REST + MQTT | HTTP 80, MQTT 1883 | Relay control, sensor data, scripting |
| **Zigbee2MQTT** | MQTT | TCP 1883 | Control Zigbee devices via MQTT bridge |
| **Z-Wave JS** | WebSocket | WS 3000 | Z-Wave device control via JS server |
| **ESPHome Devices** | Native API | TCP 6053 | ESP32/ESP8266 device control, sensors, switches |
| **Tasmota Devices** | HTTP + MQTT | HTTP 80, MQTT 1883 | ESP-based device control, scripting |

**Example**: "Turn on living room lights" → `terminal` sends MQTT message to topic `home/living_room/lights` with payload `ON`

### 🤖 Robotics & Drones

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **ROS 2** | DDS (Data Distribution Service) | UDP/TCP multicast | Robot control, sensor data, navigation |
| **MAVLink** (ArduPilot, PX4) | MAVLink protocol | Serial/UDP 14550 | Drone control, telemetry, mission planning |
| **DJI SDK** | TCP/UDP | Custom ports | DJI drone control, camera, flight modes |
| **HEBI Robotics** | TCP/UDP | TCP 50000+ | Modular robot control, kinematics, feedback |
| **WPILib** (FRC Robots) | NetworkTables | TCP 1735 | Competition robot control, sensors, actuators |

**Example**: "Arm drone and takeoff" → `terminal` sends MAVLink commands over UDP to flight controller

### 🏢 Industrial Automation & PLCs

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Modbus TCP** | Modbus | TCP 502 | Read/write PLC registers, coils, industrial control |
| **Modbus RTU** | Modbus | Serial RS-485 | Serial PLC communication |
| **Siemens S7** | S7 Protocol | TCP 102 | PLC programming, monitoring, control |
| **Allen-Bradley** | EtherNet/IP | TCP 44818, UDP 2222 | PLC control, I/O, motion control |
| **Omron PLCs** | FINS protocol | TCP 9600, UDP 9600 | PLC communication, data exchange |
| **Mitsubishi PLCs** | MC Protocol | TCP 5000 | PLC control, monitoring |
| **BACnet** | BACnet/IP | UDP 47808 | Building automation, HVAC control |
| **KNX** | KNX/IP | UDP 3671 | Building automation, lighting, climate |
| **OPC UA** | OPC UA | TCP 4840 | Industrial data exchange, SCADA integration |

**Example**: "Read temperature from PLC" → `terminal` connects via Modbus TCP to port 502, reads holding register

### 💾 Databases & Data Systems

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **PostgreSQL** | PostgreSQL Wire Protocol | TCP 5432 | SQL queries, database management |
| **MySQL/MariaDB** | MySQL Protocol | TCP 3306 | SQL queries, database operations |
| **MongoDB** | MongoDB Wire Protocol | TCP 27017 | NoSQL operations, document queries |
| **Redis** | RESP Protocol | TCP 6379 | Key-value operations, pub/sub, caching |
| **Memcached** | Memcached Protocol | TCP 11211 | Caching operations, key-value storage |
| **Elasticsearch** | HTTP REST | HTTP 9200 | Search queries, indexing, analytics |
| **InfluxDB** | HTTP REST | HTTP 8086 | Time-series data, metrics, queries |
| **Apache Kafka** | Kafka Protocol | TCP 9092 | Message streaming, pub/sub |
| **RabbitMQ** | AMQP | TCP 5672 | Message queuing, routing |
| **NATS** | NATS Protocol | TCP 4222 | Lightweight messaging, pub/sub |

**Example**: "Query database" → `terminal` connects to PostgreSQL on port 5432, sends SQL via wire protocol

### 🐳 DevOps & Infrastructure

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Docker Engine** | Docker API | Unix socket / TCP 2375 | Container management, image operations, networking |
| **Kubernetes** | REST API | HTTPS 6443 | Cluster management, pod control, deployments |
| **Nomad** | HTTP REST | HTTP 4646 | Job scheduling, task management |
| **Consul** | HTTP REST | HTTP 8500 | Service discovery, health checks, KV store |
| **etcd** | gRPC/HTTP | TCP 2379 | Distributed key-value store, configuration |
| **Prometheus** | HTTP REST | HTTP 9090 | Metrics queries, alerting |
| **Grafana** | HTTP REST | HTTP 3000 | Dashboard management, data source queries |
| **Jenkins** | REST API | HTTP 8080 | Build triggers, job management, pipeline control |
| **GitLab CI** | REST API | HTTPS 443 | Pipeline triggers, project management |
| **Terraform Cloud** | REST API | HTTPS 443 | Infrastructure automation, state management |

**Example**: "Deploy container" → `terminal` connects to Docker socket, sends API command to create/start container

### 📡 Network Devices & Monitoring

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Cisco IOS** | SSH/Telnet | TCP 22/23 | Router/switch configuration, show commands |
| **Juniper JunOS** | NETCONF over SSH | TCP 830 | Network device configuration, monitoring |
| **MikroTik RouterOS** | API | TCP 8728 | Router configuration, monitoring, scripting |
| **Ubiquiti UniFi** | HTTP REST | HTTPS 8443 | Network management, device control |
| **SNMP Devices** | SNMP | UDP 161/162 | Device monitoring, trap reception |
| **Nagios** | HTTP REST (via plugins) | HTTP custom | Monitoring, alerting, status checks |
| **Zabbix** | Zabbix Protocol | TCP 10051 | Monitoring, metrics collection |
| **Wireshark** (tshark) | Command line | STDIN/STDOUT | Packet capture, network analysis |

**Example**: "Configure router" → `terminal` opens SSH to port 22, sends configuration commands

### 🎮 Game Servers & Engines

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Minecraft (RCON)** | RCON Protocol | TCP 25575 | Server commands, player management |
| **Counter-Strike (RCON)** | Source RCON | TCP 27015 | Server control, map changes, kicks/bans |
| **TeamSpeak 3** | ServerQuery | TCP 10011 | Server management, channel control, permissions |
| **Discord Bots** | Discord Gateway | WebSocket WSS | Bot commands, message handling, voice control |
| **Mumble** | Ice Protocol | TCP 6502 | Voice server control, channel management |

**Example**: "Execute Minecraft command" → `terminal` connects via RCON to port 25575, sends `/give` command

### 🔬 Scientific Instruments

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **LabVIEW Instruments** | VI Server | TCP 3363 | Remote VI control, data acquisition |
| **SCPI Instruments** | SCPI over TCP/Serial | TCP 5025 / Serial | Oscilloscopes, multimeters, signal generators |
| **National Instruments DAQ** | NI-DAQmx | Local API | Data acquisition, signal generation |
| **Arduino** | Serial Protocol | Serial USB | Sensor reading, actuator control, custom protocols |
| **Raspberry Pi GPIO** | GPIO + Network | SSH 22 / Local | GPIO control, sensor interfacing |

**Example**: "Read oscilloscope measurement" → `terminal` sends SCPI command `MEAS:VMAX?` over TCP to instrument

### 📧 Email Servers & Mail Protocols

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Postfix** | SMTP | TCP 25/587 | Email sending, relay control |
| **Sendmail** | SMTP | TCP 25/587 | Mail delivery, queue management |
| **Exim** | SMTP | TCP 25/587 | Email routing, filtering |
| **Dovecot** | IMAP/POP3 | TCP 143/993 (IMAP), 110/995 (POP3) | Mailbox access, folder management |
| **Courier** | IMAP/POP3 | TCP 143/993, 110/995 | Mail retrieval, folder operations |
| **Microsoft Exchange** | SMTP/IMAP | TCP 25/587, 143/993 | Email operations, calendar access |
| **Gmail** | SMTP/IMAP | TCP 587 (SMTP), 993 (IMAP) | Email sending/reading via standard protocols |

**Example**: "Send email via SMTP" → `terminal` connects to port 587 with TLS, sends SMTP commands

### 🔐 Security & Authentication

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **OpenVPN** | Management Interface | TCP 7505 | VPN control, status queries, client management |
| **WireGuard** | Netlink/Config | Local interface | VPN configuration, peer management |
| **FreeRADIUS** | RADIUS | UDP 1812/1813 | Authentication, accounting |
| **OpenLDAP** | LDAP | TCP 389/636 | Directory queries, user management |
| **Active Directory** | LDAP/Kerberos | TCP 389/636, 88 | User authentication, group management |
| **HashiCorp Vault** | HTTP REST | HTTP 8200 | Secrets management, token generation |
| **Keycloak** | HTTP REST | HTTP 8080 | Identity management, SSO, authentication |

**Example**: "Query LDAP directory" → `terminal` connects to port 389, sends LDAP search queries

### 🖨️ Printers & Document Systems

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **CUPS** | IPP (Internet Printing Protocol) | HTTP 631 | Print job management, printer control |
| **HP Printers** | JetDirect | TCP 9100 | Raw printing, status queries |
| **Epson Printers** | ESC/P, Network | TCP 9100, Serial | Print control, status monitoring |
| **Zebra Label Printers** | ZPL (Zebra Programming Language) | TCP 9100, Serial | Label printing, barcode generation |
| **Brother Printers** | IPP + proprietary | TCP 631, 9100 | Print jobs, scanner control |

**Example**: "Print label" → `terminal` sends ZPL commands to Zebra printer on port 9100

### 🚗 Automotive & Vehicle Systems

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **OBD-II Scanners** | ELM327 Protocol | Serial/Bluetooth | Vehicle diagnostics, sensor reading, DTC codes |
| **CAN Bus Interfaces** | SocketCAN | Local interface | Vehicle network monitoring, message injection |
| **Tesla API** | HTTP REST | HTTPS 443 | Vehicle control, charging, climate, location |
| **Comma.ai OpenPilot** | WebSocket | WS 8082 | ADAS control, telemetry, video streaming |

**Example**: "Read engine RPM" → `terminal` sends OBD-II command `010C` over serial to ELM327 adapter

### 🏥 Medical & Healthcare Devices

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **HL7 Interfaces** | MLLP (HL7) | TCP 2575 | Medical record exchange, lab results |
| **DICOM Servers** | DICOM | TCP 104 | Medical imaging, PACS integration |
| **Philips IntelliVue** | Data Export Interface | Serial/Network | Patient monitor data, vital signs |
| **GE Healthcare Monitors** | Serial Protocol | Serial RS-232 | Vital signs monitoring, alarm data |

**Example**: "Receive HL7 messages" → `terminal` listens on TCP 2575 for MLLP-wrapped HL7 data

### 🎲 Blockchain & Crypto

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Bitcoin Core** | JSON-RPC | HTTP 8332 | Wallet operations, blockchain queries |
| **Ethereum (geth)** | JSON-RPC | HTTP 8545, WS 8546 | Smart contract interaction, transactions |
| **IPFS** | HTTP API | HTTP 5001 | File storage, content addressing |
| **Monero** | JSON-RPC | HTTP 18081 | Wallet operations, mining control |

**Example**: "Query Bitcoin balance" → `terminal` sends JSON-RPC to port 8332

### 🎯 Game Consoles & Emulators

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **RetroArch** | Network Command Interface | UDP 55355 | Emulator control, save states, cheats |
| **RPCS3** (PS3 Emulator) | Debug API | TCP custom | Game control, debugging |
| **Dolphin** (GameCube/Wii) | Pipe Interface | Named pipe | Memory reading, TAS input |
| **PCSX2** (PS2 Emulator) | Pine Interface | TCP 28011 | Memory access, cheat engine |

**Example**: "Save RetroArch state" → `terminal` sends UDP command to port 55355

### 📻 Ham Radio & SDR

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **rigctld** (Hamlib) | Hamlib Protocol | TCP 4532 | Radio control, frequency, mode, PTT |
| **WSJT-X** | UDP Protocol | UDP 2237 | FT8/FT4 automation, logging, QSO management |
| **SDR++** | HTTP API | HTTP 8080 | SDR control, frequency tuning, recording |
| **GNU Radio** | ZMQ/TCP | TCP custom | SDR signal processing, flowgraph control |

**Example**: "Tune radio to 14.074 MHz" → `terminal` sends Hamlib command to rigctld on port 4532

### 🎛️ Audio/Video Switchers & Control

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Blackmagic ATEM** | TCP Protocol | TCP 9910 | Video switching, transitions, upstream keys |
| **Roland V-60HD** | TCP/RS-232 | TCP 8023, Serial | Video switching, effects, audio mixing |
| **Extron Switchers** | SIS (Simple Instruction Set) | TCP 23, Serial | AV switching, routing, volume control |
| **Crestron** | CIP Protocol | TCP 41794 | Control system programming, device control |
| **AMX** | NetLinx | TCP custom | Control system automation |
| **Dante Audio** | Dante Controller API | TCP custom | Audio routing, device discovery |
| **AES67/Ravenna** | RTSP/SDP | TCP/UDP | Professional audio streaming, routing |

**Example**: "Switch ATEM to camera 2" → `terminal` sends binary command to port 9910

### 🌡️ Environmental & Sensor Systems

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **1-Wire Sensors** | 1-Wire Protocol | Serial/USB | Temperature, humidity, pressure reading |
| **I2C Devices** | I2C over USB | Serial/USB adapter | Sensor reading, device control |
| **SPI Devices** | SPI over USB | Serial/USB adapter | High-speed sensor/device communication |
| **Modbus Sensors** | Modbus RTU/TCP | Serial/TCP 502 | Industrial sensor reading |
| **SNMP Sensors** | SNMP | UDP 161 | Network-enabled sensor monitoring |
| **BLE Sensors** | Bluetooth LE | Bluetooth | Wireless sensor data collection |

**Example**: "Read temperature sensor" → `terminal` reads from I2C device via USB adapter

### 🎮 Streaming & Content Creation

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Twitch API** | HTTP REST | HTTPS 443 | Stream info, chat, channel management |
| **YouTube Data API** | HTTP REST | HTTPS 443 | Video management, analytics, live streaming |
| **Streamlabs** | WebSocket | WS custom | Alert control, donation tracking |
| **StreamElements** | WebSocket | WS custom | Overlay control, chat commands |
| **Elgato Stream Deck** | WebSocket | WS 28492 | Button control, page switching, actions |
| **Philips Hue Sync** | HTTP REST | HTTP 80 | Entertainment area control, light sync |

**Example**: "Get Twitch viewer count" → `terminal` sends HTTP REST request to Twitch API

### 🔊 Pro Audio Hardware

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Behringer X32** | OSC | UDP 10023 | Mixer control, channel routing, effects |
| **Midas M32** | OSC | UDP 10023 | Digital mixer automation |
| **Allen & Heath dLive** | TCP Protocol | TCP 51325 | Mixer control, scene recall |
| **Yamaha CL/QL Series** | OSC | UDP custom | Digital console control |
| **DiGiCo Consoles** | OSC | UDP custom | Mixing console automation |
| **Focusrite Control** | HTTP REST | HTTP custom | Audio interface control |

**Example**: "Mute channel 5" → `terminal` sends OSC message `/ch/05/mix/on 0` to X32 mixer

### 🖥️ Remote Desktop & VNC

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **VNC Servers** | RFB Protocol | TCP 5900+ | Remote desktop control, screen viewing |
| **RDP** | Remote Desktop Protocol | TCP 3389 | Windows remote desktop (via xfreerdp, etc.) |
| **TeamViewer** | Proprietary | TCP 5938 | Remote control (limited API) |
| **AnyDesk** | Proprietary | TCP 7070 | Remote desktop access |
| **NoMachine** | NX Protocol | TCP 4000 | Remote desktop, file transfer |

**Example**: "Connect to VNC server" → `terminal` opens TCP connection to port 5900, implements RFB protocol

### 🎪 Lighting & Stage Control

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **DMX512 Controllers** | DMX512 | Serial/USB | Stage lighting control, effects |
| **Art-Net** | Art-Net (UDP) | UDP 6454 | Network DMX distribution, lighting control |
| **sACN (E1.31)** | sACN | UDP 5568 | Streaming ACN, lighting control |
| **MA Lighting** | MA-Net | TCP/UDP custom | GrandMA console control |
| **ETC Consoles** | OSC | UDP custom | Lighting console automation |
| **Philips Dynalite** | DyNet | Serial/TCP | Architectural lighting control |
| **Lutron** | Integration Protocol | Serial/TCP 23 | Lighting and shade control |

**Example**: "Set stage lights to red" → `terminal` sends Art-Net packet to UDP 6454

### 🏭 SCADA & Industrial HMI

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Wonderware** | OPC UA | TCP 4840 | SCADA data access, HMI control |
| **Ignition** | OPC UA + HTTP | TCP 4840, HTTP 8088 | Industrial automation, data logging |
| **FactoryTalk** | EtherNet/IP | TCP 44818 | Rockwell automation, PLC integration |
| **WinCC** | S7 Protocol | TCP 102 | Siemens HMI, process visualization |
| **Citect** | TCP Protocol | TCP custom | SCADA operations, alarm management |

**Example**: "Read SCADA tag" → `terminal` connects via OPC UA to port 4840, reads tag value

### 📞 VoIP & Telephony

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Asterisk PBX** | AMI (Manager Interface) | TCP 5038 | Call control, extension management, IVR |
| **FreeSWITCH** | ESL (Event Socket) | TCP 8021 | Call routing, conference control, voicemail |
| **3CX** | HTTP REST | HTTP 5000 | PBX management, call control |
| **SIP Servers** | SIP Protocol | UDP/TCP 5060 | VoIP call control, registration |
| **RTP Streams** | RTP | UDP 10000-20000 | Audio/video streaming for calls |

**Example**: "Make phone call" → `terminal` sends SIP INVITE to port 5060

### 🎰 Point of Sale & Retail

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Square API** | HTTP REST | HTTPS 443 | Payment processing, inventory, orders |
| **Stripe Terminal** | HTTP REST | HTTPS 443 | Card reader control, payment processing |
| **Clover POS** | REST API | HTTPS 443 | POS operations, inventory, reporting |
| **Receipt Printers** (ESC/POS) | ESC/POS | Serial/USB/Network | Receipt printing, cash drawer control |
| **Barcode Scanners** | Keyboard wedge/Serial | Serial/USB | Barcode reading, inventory scanning |

**Example**: "Print receipt" → `terminal` sends ESC/POS commands to receipt printer

### 🔬 Laboratory Equipment

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Agilent/Keysight** | SCPI over LAN | TCP 5025 | Instrument control, measurement |
| **Tektronix Scopes** | SCPI over LAN | TCP 4000 | Waveform capture, measurement |
| **Fluke Calibrators** | SCPI | Serial/TCP | Calibration control, measurement |
| **Thermo Fisher** | Serial Protocol | Serial | Lab equipment control, data collection |
| **Waters HPLC** | Empower API | TCP custom | Chromatography control, data analysis |
| **Agilent ChemStation** | TCP Protocol | TCP custom | GC/MS control, method execution |

**Example**: "Capture waveform" → `terminal` sends SCPI commands to oscilloscope

### 🎪 Event & Conference Systems

| Product | Protocol | Port/Interface | What You Can Do |
|---------|----------|----------------|-----------------|
| **Zoom** | WebSocket API | WSS 443 | Meeting control, participant management |
| **Microsoft Teams** | Graph API | HTTPS 443 | Meeting scheduling, chat, calls |
| **Webex** | REST API | HTTPS 443 | Meeting control, recording, participants |
| **Jitsi** | XMPP/REST | TCP 5222, HTTP 8888 | Video conferencing control |
| **BigBlueButton** | REST API | HTTPS 443 | Online classroom control, recording |

**Example**: "Start Zoom recording" → `terminal` sends WebSocket command to Zoom client

---

## 🐍 For Python-Controlled Products

Many products are better controlled through **Python code** rather than raw protocols. See the `python` tool documentation for products like:
- **AutoCAD, Inventor, SolidWorks** (COM/ActiveX via `win32com`)
- **Blender, Maya, 3ds Max** (Python scripting APIs)
- **Microsoft Office** (Excel, Word, Outlook via `win32com`)
- **Adobe Products** (Photoshop, After Effects via scripting)
- **And hundreds more...**

The `python` tool lets your AI execute Python code that uses these APIs directly!

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

