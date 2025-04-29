# Quickchat made with Astro Starter Kit + PocketBase + Claude AI 3.7 Sonnet 

## WARNING ⚠️
Using this chat with messages open policies will allow access to anyone both to your pocketbase URL and messages CRUD action if you don't provide additional securiy


## How does it work ?

### Backend
Install pocketbase in any server you want
Use the schema pb_schema.json provided in this repo to import a simple messages schema
**_Merge with existing collection to keep your other tables_**

### Frontend
Just use this repo to have a working frontend 
1. Download or clone repo

2. Install dependencies
3. Add ENV VARIABLE of your pocketbase backend domain (see .env.example)

## UI
Just enter a nickname and chat !
<img width="1385" alt="quickchat" src="https://github.com/user-attachments/assets/5117b82f-2a80-40d9-bf36-e129ab059158" />

You can just test it with dev command or build and deploy


