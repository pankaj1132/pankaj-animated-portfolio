# Pankaj Saini — animated Next.js portfolio

## Start locally

Use Node.js 20.9 or newer. Open this folder in your terminal and run:

```sh
npm ci
npm run dev
```

Visit http://localhost:3000.

## Build and deploy yourself

```sh
npm run build
npm run check
```

The `out/` folder is the complete static website. Upload its contents to your static hosting provider. Deploy at the domain root; the current resume and asset URLs assume `/`.

For a Git-based deployment, use this folder as the project root, `npm run build` as the build command, and `out` as the publish directory. No API keys or environment variables are needed.

## What is included

- Black and lime responsive design, animated metallic Three.js sculpture, particles and wireframe orbit.
- GSAP entrance sequences, scroll reveals, parallax, progress bar, magnetic buttons and 3D project hover tilt.
- Motion hover interactions, animated Chart.js radar, continuously moving technology strip.
- Experience, education, skills, two featured projects and both downloadable resumes.
- Real email, phone, WhatsApp, LinkedIn, GitHub and LeetCode links from the resumes.
- Twitter/X and Instagram placeholders, as requested. Replace them with your real profile URLs before using them.
- Reduced-motion support, keyboard focus styles, mobile navigation and a 3D pause control.

## Edit your content

- `app/page.tsx`: biography, experience, project links, social links and chart data.
- `app/globals.css`: colors, typography, layouts and CSS animations.
- `app/MotionEffects.tsx`: scroll and pointer animation behavior.
- `public/resumes/`: the two original PDF resumes.

The project panels are illustrative interface previews, not screenshots of the live products. Email opens a mail client and WhatsApp opens a chat; the site does not send messages automatically. Google Fonts requires internet access; system fonts are used as fallback.

The full-stack resume supplies the primary current job title, with Salesforce responsibilities included from the Salesforce resume.

## Portrait and certifications

The hero displays the supplied photograph in `public/portrait.png`, with an animated frame and responsive crop. The portrait component is `app/PortraitCard.tsx`.

`app/Certifications.tsx` contains the dedicated certification and training section. The Salesforce certificate button uses the Google Drive URL embedded in the supplied resume. The remaining entries are labeled as training or participation because no individual certificate URLs were supplied.

