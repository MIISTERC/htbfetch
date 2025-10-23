# htbfetch
<img width="781" height="467" alt="image" src="https://github.com/user-attachments/assets/621f49a1-a1a2-4915-8823-878cdfe222a9" />

Fetches information of Your profile On hackthebox in neofetch like output.

## ✨ Features

- Displays HTB avatar image inline in the terminal (requires `catimg`)
- Fetches profile data from the HTB API (`curl` + `jq`)
- Colorized, aligned terminal output (username, rank, owns, respects, team etc.. You can add more by your self!)
- You can add or remove fields as you want !

---

## ⚙️ Requirements

Install the following dependencies:

```bash
sudo apt install -y jq curl catimg
```

`catimg` is used for terminal image rendering. If you prefer another tool (e.g., `chafa`), modify the script accordingly.
## 🔧 Installation

1. Clone or copy the script into a file named `htbfetch.sh`.
2. Make the script executable:

```bash
chmod +x htbfetch
```

3. (Optional) Place it in your PATH:

```bash
sudo mv htbfetch /usr/local/bin/htbfetch
```
---

## Change USER_ID Variable.
1. Change `USER_ID` Variable in Script to Your Own User ID.

### How to Get Your User ID? Easy
1. Go to your hackthebox profile dashboard > click on share profile > copy the id

<img width="1208" height="192" alt="image" src="https://github.com/user-attachments/assets/22b9d0af-578e-4522-be60-e73df42b2632" />







