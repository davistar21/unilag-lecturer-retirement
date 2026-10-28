# UNILAG Retirement Tribute Website
## Professor A. I. Mowete & Professor T. O. Akinbulire
**Department of Electrical & Electronics Engineering, Faculty of Engineering, University of Lagos**

An editorial-grade, single-page retirement celebration and tribute website built with vanilla HTML5, CSS3, and modern JavaScript. Designed strictly following authentic UNILAG colours (maroon, warm ivory, and gold) and high-end typography modeled after [`prof-ogunwolu.vercel.app`](https://prof-ogunwolu.vercel.app/).

---

## Event Details

- **Event**: Joint Send-off & Retirement Ceremony
- **Honourees**: Professor A. I. Mowete & Professor T. O. Akinbulire
- **Date**: Friday, 30 October 2026
- **Time**: 10:00 AM – 12:00 Noon (Arrival from 9:45 AM)
- **Venue**: Frederick Ige Lab. Complex, Faculty of Engineering, University of Lagos
- **Registration**: [Google Form Registration Link](https://forms.gle/xHoydT1CKy7JDxao9)

---

## Features

1. **Duo-Honouree Hero Showcase**:
   - Prominently features both Professor A. I. Mowete and Professor T. O. Akinbulire with gold-accented portrait frames.
   - Interactive modal preview when clicking on either celebrant or the official invitation flyer.
2. **Key Event Information Bar**:
   - At-a-glance strip summarizing date, time, venue, and registration link.
3. **Editorial Tribute Section**:
   - Deeply respectful biographical and scholarly tributes to both professors, highlighting their decades of teaching, research, and mentorship.
4. **"Journey in Pictures" (Chapters)**:
   - 4 curated milestone chapters covering NYSC youth service, doctoral attainment, university leadership, and cherished family moments.
5. **Interactive Photo Archive & Lightbox**:
   - Filterable gallery by category:
     - `All Photographs`
     - `Prof. A. I. Mowete`
     - `Prof. T. O. Akinbulire`
     - `Event & Invitation`
   - Fullscreen Lightbox viewer with Next / Previous navigation and keyboard shortcuts (`Esc`, `ArrowLeft`, `ArrowRight`).
6. **Program of Events Schedule**:
   - Complete 17-item timeline from the official Order of Programme, detailing timings from 9:45 AM arrival to closing remarks, responsibility leads, and dignitaries.
7. **Fully Responsive**:
   - Tailored layouts for widescreen desktops, laptops, tablets, and mobile smartphones with a smooth animated navigation drawer and animated hamburger toggle.

---

## Image Asset Directory (`images/`)

| File Name | Description |
|-----------|-------------|
| `images/event-flyer.jpg` | Official joint retirement celebration invitation poster |
| `images/mowete-portrait-smile.jpg` | Prof. A. I. Mowete — studio portrait (smiling frontal) |
| `images/mowete-portrait-standing.jpg` | Prof. A. I. Mowete — studio portrait (standing profile) |
| `images/mowete-portrait-seated.jpg` | Prof. A. I. Mowete — studio portrait (seated) |
| `images/akinbulire-doctoral-framed.jpg` | Prof. T. O. Akinbulire — formal doctoral portrait in academic regalia |
| `images/akinbulire-doctoral-cap.jpg` | Prof. T. O. Akinbulire — academic convocation regalia & cap |
| `images/akinbulire-wedding-celebration.jpg` | Prof. T. O. Akinbulire — family milestone & wedding celebration |
| `images/akinbulire-nysc.jpg` | Prof. T. O. Akinbulire — vintage National Youth Service Corps (NYSC) |
| `images/akinbulire-student-days.jpg` | Prof. T. O. Akinbulire — vintage student days |
| `images/akinbulire-youth-wildlife.jpg` | Prof. T. O. Akinbulire — vintage field excursion |

---

## Quick Start

Open `index.html` in any modern web browser:
- Double click `index.html` on your desktop/folder, or
- Serve locally using:
  ```bash
  python -m http.server 8000
  # or
  npx serve .
  ```

---

## Deployment

Zero build dependencies. Upload directly to any static host:
- **Vercel**: Run `npx vercel --prod`
- **Netlify**: Drag and drop the folder into the Netlify dashboard
- **GitHub Pages**: Push repository and enable GitHub Pages on `main` branch
