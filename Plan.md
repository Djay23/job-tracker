### Big Picture
- Web app with:
    - backend API
    - database
    - frontend UI
    - AI layer (future)

### Stage 1
## Job Tracker + Notifications
- The goal is to build an app where users can define a search criteria: keywords, location or job type and the scraper runs on a schedule to notify the user when new matches appear
# Goals: 
- REST API Design
- DB modeling: users, preferences (location, job specifications, distance, remote/hybrid), job records, notifcation history, best matches and weak matches
- Background task scheduling (APScheduler or Celery)
- Email sending (SMPTP/SendGrid)
- .env and secrets management

# POI currently:
- What is REST API 
- Difference between SQL & NoSQL; DB schemas?
- Should scraper run on a fixed schedule or be triggered by user actions? Bottlenecks?