# - Netflix Token
- Netflix Generate Token
- Demo : https:///

## Endpoint 

- /api/generate
```json
{
  "creator": "Henkaramazov",
  "status": true,
  "data": [
    {
      "success": true,
      "token": "",
      "expiry": "",
      "type": "",
      "country": "",
      "plan": "",
      "links": {
        "pc": "",
        "android": "",
        "tv": "",
        "tv8": ""
      }
    }
  ]
}
```
## Struktur Project
```
api-netflix/
├── api/
│   └── generate.js
├── README.md
├── package.json
└── vercel.json
```
## Deploy

1. Deploy repository ke [Vercel](https://vercel.com).
2. Deploy.
