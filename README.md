# PSPDFKit Server Example Deployment with Metrics

This repository contains an example PSPDFKit Server deployment exporting metrics via Telegraf, InfluxDB, and Grafana.

## Getting Started

You need to have Docker with docker-compose installed.
Clone the repository and replace `<YOUR_ACTIVATION_KEY>` placeholder with your actual PSPDFKit Server activation key.
(Check out our [product activation guide](https://pspdfkit.com/guides/server/current/deployment/product-activation/) to learn more).

Now run `docker-compose up` in the console.
You can now access Server dashboard at `http://localhost:5000/dashboard`, and Grafana at `http://localhost:3000`.
When you open Grafana in the browser, sign in using the admin/secret credentials and open the "PSPDFKit Server" dashboard.

![Grafana dashboard](/images/grafana-dashboard.png).

## Support, Issues and License Questions

PSPDFKit offers support for customers with an active SDK license via https://pspdfkit.com/support/request/

Are you [evaluating our SDK](https://pspdfkit.com/try/)? That's great, we're happy to help out! To make sure this is fast, please use a work email and have someone from your company fill out our sales form: https://pspdfkit.com/sales/.
