<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webhook Tool</title>
    
    <style>
        :root {
            --bg-color: #36393f;
            --card-bg: #2f3136;
            --discord-blue: #5865f2;
            --text-main: #ffffff;
            --text-muted: #b9bbbe;
        }

        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            background-color: var(--card-bg);
            padding: 2rem;
            border-radius: 16px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.5);
            text-align: center;
            width: 90%;
            max-width: 400px;
        }

        h1 { font-size: 1.5rem; margin-bottom: 1.5rem; }

        .input-group { margin-bottom: 1.5rem; text-align: left; }
        
        label { display: block; margin-bottom: 0.5rem; color: var(--text-muted); font-size: 0.9rem; }

        input {
            width: 100%;
            padding: 12px;
            border-radius: 8px;
            border: none;
            background-color: #202225;
            color: white;
            box-sizing: border-box;
            font-size: 1rem;
        }

        button {
            width: 10
