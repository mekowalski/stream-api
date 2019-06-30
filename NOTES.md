# JSON Server Docs
- `npmjs.com/package/json-server`
- Can create a `db.json` file
- Any records that are trying to be saved to API Server will automatically be stored in `db.json`

1. [x] Create `db.json` with resource type: streams
    - As streams are created, they will be stored into the array of streams (within `db.json`)
    - along the way, the file will store more and more streams records
2. [x] Edit `tests` to `start`
    - remove tests and start the json-server on port 3001 and watch db.json file for changes

- This is all the could that is necessary to get API Server up and running
- Now have a listed Resource of: `http://localhost:3001/streams`
- This will be used to manipulate list of streams stored in API Server by following RESTful conventions
