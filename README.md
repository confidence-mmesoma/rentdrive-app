# RentDrive — Car Rental Website

A responsive React + Tailwind CSS car rental landing page based on the supplied RentDrive reference.

## Run locally

1. Install Node.js (18+ recommended).
2. Extract the ZIP and open this folder in your terminal.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed by Vite (usually http://localhost:5173).

To create a production build, run `npm run build`.

## Included interactions

- Responsive mobile navigation.
- Fleet category filters and carousel-style next/previous controls.
- Booking request modal with required fields and date validation.
- Confirmation state after submitting a booking request.
- Video/brand-story modal.
- Newsletter form with a local success state.

## Notes

- This is a front-end demo. Booking requests and newsletter subscriptions are not sent to a server, and no payment is processed. Connect an API/backend to make those workflows live.
- Vehicle and travel photography is loaded from Unsplash image CDN URLs. The images are remote, so an internet connection is required for them to display. Pinterest image URLs are not embedded because Pinterest hotlinks are unstable and may be restricted; use properly licensed image files if you want to replace these assets.
- Prices, testimonials, and company details are sample demo content and should be replaced with verified business information before launch.
