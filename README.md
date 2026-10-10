# Resilient Teams

A single-page Women Who Code workshop site for Masha's "Building Resilient Teams" session.

Open `index.html` directly or serve the folder with a static server.

## Visit Tracking

The page has an optional GA4 hook in `index.html`.

To enable visit tracking, replace the empty `ga4MeasurementId` value near the top of `index.html` with the GA4 measurement ID for this site:

```js
window.RESILIENT_TEAMS_ANALYTICS = {
  ga4MeasurementId: "G-XXXXXXXXXX"
};
```

Tracked events:

- automatic page views
- slide dot clicks
- keyboard/clicker slide advances
- leader quiz selections
- handout downloads
- external link clicks
