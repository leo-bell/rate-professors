## Demo

https://www.youtube.com/watch?v=SoGa16pKeF4

## Info

This app's main goal is to give users the chance of rating university professors. 

Users can search an specific professor. If he/she is not created yet, users can create him/her.

Professors are qualified by difficulty and score.

There are there different "top 3" in which professors are ranked by less or more difficulty or score.

## Backend Structure

This project used Python Flask and SqlAlquemy


```
tedijimos/
│
├── routes/	all the endpoints
├── service/	service files. Where logic is. 
├── dao/	dao files. Where the BE connects to DB
├── extra/	extra but necessary files. i.e. to_dict.py

```

## Database

### Professor

```

  ID    firstname    lastname    score    difficulty
 (pk)
```

### Review 
```

  ID    title    description    professor_id    course    score    difficulty
 (pk)	
```		

