# Whisper: The Complete Setup Guide

## 1. Start Web Sockets Server

Run the following commands:

```bash
git clone https://github.com/Whisper-Inc/whisper-ws.git
cd whisper-ws/
npm i
npm run dev
```

✅ Web socket server should be running

## 2. Start Next.js Frontend Server

Run the following commands:

```bash
git clone https://github.com/Whisper-Inc/whisper-client.git
cd whisper-client/
npm i
npm run dev
```

✅ Client server should be running

## 3. Start FastAPI Backend Server

Run the following commands:

```bash
git clone https://github.com/Whisper-Inc/whisper-core.git
cd whisper-core/
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 main.py
```

✅ FastAPI server should be running

## 4. View in Browser

Now, copy the localhost:3000 URL provided by Whisper Client, and paste it into the browser. There are a few test users available for you to start chats with—start typing in 'test' and a few users should come up.

## Run tests

If you'd like to run the `whisper-core` tests, run `coverage run pytest`

If you'd like to run the `whisper-client` tests, run `npm run test`
