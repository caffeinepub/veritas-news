# VERITAS NEWS - The Untold Indian

## Current State
New project. Backend has empty Motoko actor. Frontend is scaffolded.

## Requested Changes (Diff)

### Add
- News/Blog article management: create, read, update, delete with title, body, category, language, image, author, timestamp
- Photo gallery management: upload and display images
- YouTube video embed management: add/remove YouTube video links with title
- Live TV embed: store and display a YouTube Live link
- Social media links management: Facebook Page, Facebook Profile, YouTube, Twitter/X, Instagram
- Role-based access: Admin (full control) + Team (can create/edit content)
- Language switcher: Gujarati / English / Hindi
- About page content (static)
- Contact page with form fields
- Breaking news ticker at top
- News categories: India, World, Politics, Sports, Business, Entertainment, Gujarat
- Share buttons on articles (Facebook, WhatsApp, Twitter)

### Modify
- Nothing (new project)

### Remove
- Nothing

## Implementation Plan
1. Backend: news CRUD, gallery, videos, social links, live TV link, settings storage
2. Authorization component for Admin + Team roles
3. Blob-storage for photo/image uploads
4. Frontend: Home page (breaking ticker, featured news, category sections), News detail page, Gallery page, Videos page, Live TV page, About page, Contact page, Admin dashboard (manage all content), language switcher
5. Social share buttons on articles
6. Social media icons in header/footer
