Please add database and collection in that database called "advertising"

```
db.getCollection("advertising").insertMany(    
    [
        { name: "microsoft team", url: "https://www.microsoft.com/th-th/microsoft-teams/group-chat-software" },
        { name: "discord", url: "https://discord.com/" },
        { name: "google", url: "https://www.google.com/" },
        { name: "garena", url: "https://www.garena.co.th/"},
        { name: "riot", url: "https://www.riotgames.com/en"}
    ]
)
```