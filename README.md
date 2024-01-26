# NestDoorbell

A doorbell for visitors of nestspace to alert us they are outside innowing

## functional requirements
- visitor can input their name into the website
- RESTful api for the website client to post a HTTP request to the server
- python server will send visitor name to ESP32 pixel LED display doorbell through another RESTful request
- get visitor IP address, datetime of the visit, and their name and store them in Postgres database

## non-functional requirements
- pretty

## file structure
```
nestdoorbell
├── frontend
│   ├── index.html
│   ├── style.css
│   └── static
│       ├── favicon
│       └── nestspacelogo
├── backend
│   └── flask
└── api
    └── schemas
```
(https://www.text-tree-generator.com/)
