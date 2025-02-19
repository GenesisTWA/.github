# GENESIS

Genesis est un projet de boilerplate, il a pour but de mettre en place des bases pour une stack de dev prédéfini . Cette stack est composé de Symfony (PHP) pour le Backend/API, Next.js(React) pour le Frontend et Shadcn (Tailwindcss) pour l'UI/Components library . Cette boilerplate devra mettre en place des feature simple et basique dans les projet de dev : File manager (upload systeme), user profile , login, register, logout, CRUD , une entité témoin "Article" avec des entité connexe comme des Category, Tag, Image (voir liste des feature completes). La boilerplate doit fournir une documentation .

## Domain archi

Une app est constitué de :
- domain.com (domain principale, vitrine, site principale)
- cdn.domain.com (pour délivrer les assets rapidement sur le site principale)
- api.domain.com (le backend, permet d'ajouter des assets sur cdn, et gérer les requete du site principal, gere les données etc)
- brand.domain.com (regroupe les assets concernant l'image de marque du projet)

cdn et api partage le meme code source et dossier symfony . il pointe au meme endroit , symfony gere le routing.

## MVP

- 

## Feature checklist

Liste des fonctionnalités toute tech confondu (backend, frontend, ui).

- Authentification
    - Login
    - Register
    - Logout
    - Provider login*
        - Facebook*
        - Github*
        - Google*
    - Email verification
    - Forgot Password

- User
    - profile
    - Image picture
    - Change password
    - Modify info 

- Security
    - Path gate
    - CORS
    - CSRF
    - HoneyPot
    - Nelmio other check

- Entity
    - Validation
    - CRUD
    - API
    - Form

- SEO
    - PWA
    - Favicons
    - Manifest
    - Screenshots
    - Twitter card

- UI
    - Responsive
    - Flash/alert
    - Navbar
    - Dark/light mode
    - Locale switch i18n (FR/EN)*
    - Animation/transition section

- Footer
    - Socials
    - Legals
    - Partners
    - Sitemap
    - About

- Utils
    - create admin command

- CDN
    - image
    - fonts

- CI/CD
