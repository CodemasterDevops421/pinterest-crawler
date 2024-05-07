
```markdown
# Pinterest Scraper

Unlock the full potential of Pinterest data with our free Pinterest Scraper. This tool allows you to extract detailed information from "pins" and user profiles, offering more depth than the standard web interface.

## Features

- **Profile Scraping**: Retrieve metadata directly from user profiles.
- **Pin Scraping**: Obtain comprehensive details about various types of pins.

## How to Use

For detailed instructions on utilizing the Pinterest Scraper, consult our step-by-step guide on [how to scrape Pinterest](https://blog.apify.com/how-to-scrape-data-on-pinterest-in-5-easy-steps/) or watch the [tutorial video](https://www.youtube.com/watch?v=v8WDCpA3iR0) on our YouTube channel.

## Cost

Scraping 1,000 pins costs approximately $0.25. With the Apify Free plan, which provides $5 in monthly credits, you can scrape up to 20,000 pins for free each month. For larger data needs, consider our Personal plan at $49/month, allowing for up to 200,000 pins monthly.

## Why Scrape Pinterest?

Extracting data from Pinterest can help you:

- Analyze audience characteristics and engagement.
- Identify and engage with top subscribers through targeted outreach.
- Gain insights into competitor audiences and strategies.

Explore further applications on our [industries pages](https://apify.com/industries).

## Configuration

### Input Settings

Provide a list of Pinterest profile names or URLs. These can be mixed in any order.

### Proxies

- **Standard Proxies**: Supported by Pinterest.
- **Custom Proxies**: Use your own proxy settings by specifying `proxyURLs` in the JSON configuration.

## Legal Considerations

While web scraping is legal, ensure compliance with GDPR and other privacy laws when handling personal data. For legality concerns, refer to our [web scraping legality post](https://blog.apify.com/is-web-scraping-legal/).

## Sample Input

```json
{
    "profiles": [
        "https://www.pinterest.com/exampleprofile/",
        "userProfile2"
    ],
    "proxyURLs": [
        "http://yourproxy.com"
    ]
}
```

## Sample Output

```json
{
    "profileName": "exampleprofile",
    "pins": [
        {
            "id": "123456",
            "title": "Summer Fashion",
            "description": "Latest summer fashion trends",
            "image": "https://example.com/image.jpg"
        }
    ]
}
```

## Connect With Us

- **YouTube**: [Visit our channel](https://www.youtube.com/@CodeMaster-421)
- **Instagram**: [Follow us on Instagram](https://www.instagram.com/quicklifesolutionsofficial/)
- **AI Newsletter**: [Subscribe to our newsletter](https://sendfox.com/quicklifesolutions)
- **Free Consultation**: [Book a free consultation call](https://tidycal.com/quicklifesolutions/free-consultation)
- **More Tools**: [Explore our Apify actors](https://apify.com/dainty_screw)

### Support

- **Discord**: [Raise a Support ticket here](https://discord.gg/2WGj2PDmHb)
- **Email**: [Contact us](mailto:codemasterdevops@gmail.com)

Start leveraging the power of Pinterest today with our Pinterest Scraper!
```
