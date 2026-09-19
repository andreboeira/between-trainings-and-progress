# Between Trainings and Progress

> **We have data and process.**

Between Trainings and Progress (BTP) is a sports analytics project focused on transforming training data into meaningful performance insights.

The goal is simple: go beyond showing what happened in a training session and understand **why it happened, how it connects to the training process, and whether it is contributing to long-term progress.**

## Vision

Athletes generate enormous amounts of data through their training.

Heart rate, power, pace, cadence, elevation, distance, training load and countless other metrics can describe what happened — but data alone does not explain the process behind performance.

BTP aims to connect these pieces.

> **Data tells you what happened.
> Process tells you why.
> Progress tells you whether it mattered.**

## Current Status

🚧 **Early development**

The project is currently being developed as an MVP, starting with Strava activity data and gradually evolving into a broader sports analytics platform.

## Planned Features

* [ ] Strava OAuth
* [ ] Activity import
* [ ] Training data storage
* [ ] Training dashboard
* [ ] Running analytics
* [ ] Cycling analytics
* [ ] Triathlon & brick analysis
* [ ] Training load
* [ ] Performance trends
* [ ] Long-term progress
* [ ] Athlete insights
* [ ] AI-assisted training insights

## Tech Stack

* **Next.js**
* **TypeScript**
* **React**
* **Tailwind CSS**
* **PostgreSQL**
* **Prisma**
* **Strava API**
* **Python**
* **Google Colab**

## Project Architecture

The initial architecture is designed to separate the application, data storage and analytical experimentation:

```text
Strava
  ↓
PostgreSQL
  ↓
Data Pipeline
  ↓
Analytics
  ↓
BTP Web Application
  ↓
Performance Insights
```

Python and Google Colab will be used primarily as the analytical and experimentation environment, while the Next.js application will serve as the product layer.

## Roadmap

### Phase 1 — Foundation

* [x] Create GitHub repository
* [x] Initialize Next.js
* [x] Configure TypeScript
* [x] Configure Tailwind CSS
* [ ] Configure PostgreSQL
* [ ] Configure Prisma

### Phase 2 — Strava Integration

* [ ] Strava OAuth
* [ ] Access token management
* [ ] Activity import
* [ ] Activity synchronization

### Phase 3 — Analytics

* [ ] Feature engineering
* [ ] Running metrics
* [ ] Cycling metrics
* [ ] Triathlon metrics
* [ ] Training load
* [ ] Performance trends

### Phase 4 — Product

* [ ] Athlete dashboard
* [ ] Training calendar
* [ ] Performance visualization
* [ ] Progress tracking
* [ ] Athlete insights

### Phase 5 — Intelligence

* [ ] Automated training analysis
* [ ] Contextual insights
* [ ] AI-assisted interpretation

## Philosophy

BTP is built around a simple idea:

**More data does not automatically create more understanding.**

The value comes from connecting data with context, consistency and the training process.

---

**Between Trainings and Progress**
*We have data and process.*
