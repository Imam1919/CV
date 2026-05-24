# Imam Mohammed Portfolio

This repository contains my personal portfolio and CV website. It presents my experience, skills, awards, certificates, resume, and selected software, AI, automation, and robotics projects.

## Live Website

The site is deployed on Vercel:

```text
https://imams-seven.vercel.app
```

The root URL is configured through `vercel.json` to open `main.html`.

## Main Sections

- Home: Short professional introduction and social links.
- About: Overview of my education, experience, technical background, and project focus.
- Experience: Freelance, internship, part-time, and QA/software testing experience.
- Skills: Full-stack development, databases, programming languages, DevOps, cybersecurity, and AI.
- Awards: Dean's List, Golden Award, and Python coding competition achievement.
- Certificates: Ethical hacking and AI workshop certificates.
- Projects: Detailed portfolio projects with separate project pages.

## Project Pages

Project pages are stored inside:

```text
Projects/
```

Current project pages include:

- `Car-Search-project.html`
- `AI_Powered-Camera-Security-system.html`
- `Automatic-Liquid-Mixer.html`
- `AI_Power-Face-recognization.html`
- `Restourant-Managenment-system.html`
- `Automatic-Car-Driver.html`
- `AI-Driven-Autonomous-Robot.html`

Project images are stored inside:

```text
Projects/Img/
```

## How To Open Locally

Open this file in your browser:

```text
main.html
```

Or, if using VS Code, install the Live Server extension and run the site from the project folder.

## How To Edit

Most website content is inside:

```text
main.html
```

To update an individual project, edit the matching HTML file inside `Projects/`.

To update images, place them in the correct folder inside `img/` or `Projects/Img/`, then update the image path in the HTML.

## Resume

The downloadable resume used by the website is:

```text
Resume_Imam_Mohammed.pdf
```

The download button in the Home section links to this file.

## Deployment

This project is configured for Vercel. After editing, commit and push the changes:

```bash
git add .
git commit -m "Update portfolio"
git push
```

Vercel will redeploy the website automatically after the push.
