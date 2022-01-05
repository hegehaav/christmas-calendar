# Christmas Calendar
An example of how to use Webpack's Module Federation to render a project inside another. 
 
A simple christmas calendar consisting of two seperate applications. `calendar-card` reders the contant of one calendar window, and `calendar-container` reders the entire calender and imports the CalendarCard from `calendar-card`.

## Run project locally

For each app, open a terminal window and run the following commands:

```
npm i
npm start
```

You can find the content of a single calendar card at localhost:3002, and the christmas calendar at localhost:3001
