# Contact Form Setup Instructions

To enable the contact form to send emails to stallvikensislandshastar@gmail.com, follow these steps:

## Option 1: Web3Forms (Recommended - Free)

1. Visit https://web3forms.com
2. Enter your email: stallvikensislandshastar@gmail.com
3. Click "Create Access Key"
4. Copy the access key you receive
5. In `/src/pages/kontakt.astro`, replace `YOUR_ACCESS_KEY_HERE` with your actual access key (line 293)

## Option 2: Netlify Forms (If hosting on Netlify)

If you're hosting on Netlify, you can use their built-in form handling:

1. Add `netlify` attribute to the form tag
2. Remove the custom JavaScript handler
3. Forms will automatically be sent to your Netlify dashboard

## Option 3: EmailJS (Alternative)

1. Sign up at https://www.emailjs.com
2. Create a service and template
3. Replace the form handler with EmailJS code

## Testing

After setting up, test the form by:
1. Filling out all fields
2. Clicking "Skicka meddelande"
3. Checking that you receive the email at stallvikensislandshastar@gmail.com

## Security Note

Never commit your access keys to the repository. Consider using environment variables for production.