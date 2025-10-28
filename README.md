# Dog-and-Cat-Boarding-and-Grooming-App
/backend
  package.json
  .env
  src/
    app.js
    routes/
      owners.js
      dogs.js
      bookings.js
      payments.js
    controllers/
    models/
    services/
    db/
      index.js
      migrations/
      seeds/
/frontend
  package.json
  src/
    App.jsx
    pages/
      OwnerDashboard.jsx
      DogProfile.jsx
      BookingPage.jsx
      CheckInOutPage.jsx
    components/
    services/
    const express = require('express');
const router = express.Router();
// import controllers…
router.post('/', createDog);
router.get('/:dogId', getDog);
router.put('/:dogId', updateDog);
module.exports = router;

