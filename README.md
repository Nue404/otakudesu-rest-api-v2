# OtakuDesu API V2 (Recode By Nue404)

**Unofficial API of** : https://otakudesu.cloud/

## TODO
- [x] Home
  - [x] Ongoing
  - [x] complete
- [x] Ongoing Pagination
- [x] Complete Pagination
- [x] Schedule
- [x] Genre List
  - [x] Anime By Genre
- [x] Detail Anime
  - [x] Detail
  - [x] Batch
  - [x] Episode List
- [x] Detail Batch
  - [x] Download Link
- [x] Detail Episode
  - [x] Download Link
  - [x] Streaming Link
- [x] Search

## Usage
1. Clone this repository
```bash
git clone https://github.com/Nue404/otakudesu-rest-api-v2.git
```
2. Install packages (use `yarn` or `npm`)
```bash
npm install
```
3. Start server
```bash
npm run start
```
or
```bash
npm run dev (install nodemon on your computer)
```

## API Documentation
__Api Path__ : https://wonderful-mollee-nxploit.koyeb.app/api/</br>
__API Version__ : v2

| Endpoint | Params | Description |
| -------- | ------ | -----------|
| /home | - | Homepage |
| /complete | - | Complete/Finished Anime |
| /complete/page/${page} | pageNumber | Complete Pagination |
| /ongoing | - | Ongoing Anime |
| /schedule | - | Schedule Anime |
| /genres | - | Genre List |
| /genres/${id}/page/${page} | id,pageNumber | Show Anime by Genre |
| /search/${query} | query | Search Anime |
| /anime/${id} | id | Detail Anime |
| /batch/${id} | id | Detail Anime's Batch |
| /eps/${id} | id | Detail Anime's Episode |
