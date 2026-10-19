# The Modern Mirror

A single-page website for The Modern Mirror, a luxury salon in Gomti Nagar, Lucknow. It presents hair, makeup, skincare, and nail services, with pricing, a photo gallery, client reviews, and a contact form.

## Project structure

```
The-Modern-Mirror/
├── index.html              # All page sections
├── style.css               # Layout, theme, and responsive styles
├── script.js               # Navigation, gallery, reviews, and form behavior
├── README.md
└── assets/
    └── images/
        └── logo.svg        # Wordmark used in the header and footer
```

Service, gallery, and hero photos are loaded from Unsplash. The only local image is the logo.

## Page sections

- **Header** — Sticky navigation, mobile menu, and a Book Now link to the contact section.
- **Hero** — Full-width introduction with links to services and booking.
- **Trusted by customers** — Animated counters for clients, years, services, and staff.
- **Services** — Twelve service cards covering hair, makeup, skincare, and nails.
- **Why choose us** — Short reasons to visit, beside a studio photo.
- **Gallery** — Eight photos that open in a lightbox.
- **Reviews** — Three testimonials in a Swiper carousel.
- **Pricing** — A table with Basic, Standard, and Premium prices.
- **Contact** — Studio address, phone, email, hours, a message form, and a map.
- **Footer** — Brand summary, quick links, services, and the same contact details.

## Tech stack

- HTML5
- CSS3 (custom properties, flexbox, and grid)
- Vanilla JavaScript
- [Swiper](https://swiperjs.com/) for the review carousel
- [Remix Icon](https://remixicon.com/)
- [Google Fonts](https://fonts.google.com/): Lora and Open Sans

## Design

| Role | Value |
| --- | --- |
| Rose | `#C96B8A` |
| Deep rose | `#8B1A4A` |
| Soft rose | `#F5D5DF` |
| Gold | `#C4924E` |
| Text | `#57534E` |
| Background | `#FEFCFB` |
| Headings | Lora |
| Body | Open Sans |
| Max width | 1200px |

Layout breakpoints in `style.css` adapt the grids, hero, and navigation for tablet and phone widths. The mobile menu slides in from the side and closes on a link, the overlay, or Escape.

## Run locally

No build step or package install is required.

1. Open `index.html` in a browser, or
2. From this folder, start a static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

The contact form checks that name, email, topic, and message are filled in, and that the email looks valid. On submit it shows a success state in the page. It does not send the message to a server.

## Contact

**The Modern Mirror**

- Address: 27, Vibhuti Khand, Gomti Nagar, Lucknow, Uttar Pradesh 226010
- Phone: +91 522 406 8814
- Email: studio@themodernmirror.com
- Hours: Tuesday – Sunday, 11:00 AM – 8:00 PM (closed Monday)
- Website: https://themodernmirror.com
