# Pod Web App (MVP)

This is a local-first web interface for Data Pods.

## Run

```bash
cd /home/claudio/.openclaw/workspace/pod-webapp
python3 -m http.server 8088
```

Open: http://localhost:8088

> Backend expected at: http://localhost:7868 (pod_qa.py --server)

## Features
- Import files / pods
- Browse sources
- Q&A chat
- Unlock / encrypt placeholders (next)

## Next Steps
- Wire .dpod import + decrypt
- Wire biometric unlock
- Streamed uploads
- PDF extraction
