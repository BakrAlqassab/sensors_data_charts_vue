# Sensors data Dashboards project


![Project daiagram](https://i.ibb.co/F6LV8yZ/Screenshot-2024-07-23-151458.png?raw=true "Project's Diagram")


## Project's Functionality

- User authentication (login and registration)
- Dynamic chart creation using sensor data
- Filtering charts by date (by default -5, +5 days selected)
- Admin page for display all user data
- Utilizing a frontend library (Vuetify) for the UI
- Managing state with Vuex ORM
- Login, Logout, addNewDashboard changes reflect on all tabs

## Idea's for new version's Functionality

- add Node.js && MongoDB database for store user's and Dashboards results.
- Auto import to the components under ``` /componetns/``` directory
- fetch real Sensor's data
- can be have the possiblity that each user have different Sensor's data permission to configure the Dashboard
- have different permissions for norma User & Admin
- optimize the UI/UX

  ## Used packages and OS
  - OS Windows 11
  - Node 18.20.2
  - Npm 10.8.1
  - vue 2.6.4
  - vuex 3.6.2
  - vuex-orm/core 0.36.5
  - vuex_persistedstate 4.1.9
  - vuetify 2.6.0
  - vue-router 3.6.5
  - highchairs-vue 1.4.3
  - uuid 10.0.0

## Project setup

```js
git clone  [Vuetify](https://github.com/BakrAlqassab/natlex-frontend-developer-task)
npm install (be sure you inside the project's directory)
npm run serve
```

## Resources 
-  [Vuetify](https://vuetifyjs.com/en/)
-  [Highchart](https://highcharts.com/docs/index)
-  [Vuex](https://vuex.vuejs.org/)

