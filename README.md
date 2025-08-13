# Soulseek CSV Downloader (macOS)

A one-shot builder that creates a macOS `.app` which lets you upload a CSV, enter your Soulseek login, and start batch downloads.  
Everything runs **locally**; your password is only sent to the helper on `http://127.0.0.1`.

## Run it (one command)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/wudwerd/soulseek_csv_downloader-/main/soulseek_csv_downloader.sh)"
