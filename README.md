# Portfolio

A personal portfolio website for Sudul Fernando, featuring an auto-emailing contact form.

## Features

- Responsive design
- Contact form with email integration via Web3Forms
- Smooth scroll animations
- Service showcase
- Work experience timeline
- Project gallery

## Setup

### Contact Form Configuration

The contact form uses [Web3Forms](https://web3forms.com/) for email functionality. To enable the contact form:

1. Visit [Web3Forms](https://web3forms.com/) and create a free account
2. Get your access key from the dashboard
3. Replace `YOUR_ACCESS_KEY_HERE` in `index.html` (line 240) with your actual access key:
   ```html
   <input type="hidden" name="access_key" value="your_actual_access_key">
   ```

## Local Development

Simply open `index.html` in a web browser, or use a local server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080` in your browser.