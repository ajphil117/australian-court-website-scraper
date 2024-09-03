# Australian Court Website Scraper
This project was completed over the course of a year and was created for the Queensland Government Department of Environment and Science. The team, consisting of 4 people, was tasked to create a web application that could automatically scrape publicly accessible court databases for each Australian state to notify when any open cases were returned on selected people, saved in a database within the application. A user was able to enter the details of a person they wished to search for into either a database (for automatic searches) or a search bar (for manual searches) to scrape through all databases for a record of them. This project was completed using React.js and Node.js, and implemented MongoDB for the database schema.

## Demo Videos
Demo videos for each page of the web server and the program features can be found on YouTube.

[Login and New User Demo](https://www.youtube.com/watch?v=Gfi032dtuT4)

[Dashboard Demo](https://www.youtube.com/watch?v=MBIav68K-qo)

[Auditor Page Demo](https://www.youtube.com/watch?v=CZLwPhf9190)

[Manual Search Demo](https://www.youtube.com/watch?v=hJBGiEOUMzg)

[Settings Page](https://www.youtube.com/watch?v=ljZKwnVIfWU)


## Program Features
### MVP
- Scrape data, based on a list of auditors, from the available Queensland court website
- Enable these scrapes to be made automatically
- Add auditors to the list of personnel
- Remove auditors from the list of personnel
- Manually scrape data using a manual search

### Enhanced System
- Add scrapers from other state's available court websites
- Update the details of an auditor
- Disable scrapes being made automatically
- Review individual cases found in scrapes
- Login with department details

### Stretch System
- View the list of auditors currently being searched
- View an auditor's case history
- Provide the name of the user who reviewed a case
- Change the state search when manually searching
