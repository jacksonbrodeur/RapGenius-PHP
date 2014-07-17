RapGenius-PHP
=============

Simple API for Genius.com (old RapGenius.com) written in PHP.

## Rationale

  This project was created because RapGenius does currently not support a Node.js API.
  
## Usage

  The API is very simple to use and currently enables you to perform the following:
  
### Models
#### Artist's page
    Artist:
      - album list: array:
             - name: string
             - link: string
    
#### Album page
    Tracklist (array for each song):
      - id: int
      - link: string
      - title: string
      - artist: string
    
#### Song page
    Song:
      - artist: string
      - title: string
      - genre: string
      - tags: array:
             - tag: string
             - link: string
      - featurings: array:
             - name: string
             - link: string
      - roducers: array:
             - name: string
             - link: string
      - lyrics: string
    
## Licence

MIT (Make It Tremendous)
