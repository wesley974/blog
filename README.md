## Blog Project

### Stack
- Latest version of Next.js
- Vercel environment
- Postgres from Vercel
- Prisma
- Tiptap
- TypeScript

### Project Features

#### /write Route
- Admin interface for article management.
- Write articles using the Tiptap editor.
- Toggle the `/register` route to either allow new user registrations or display a 'Registration Closed' message.
- Allow clipboard, ctrl-v to paste image

#### CRUD Operations
- Create, Read, Update, and Delete articles.
- Draft/Publish options for articles.
- Efficient search feature for managing large volumes of articles.

#### /register Route
- User registration: Pseudonym, username, password (minimum 20 characters).

### Authentication
- Username/Password authentication (consider using JWT).
- Sessions expire after 2 hours.

### SEO Optimization
- SEO-friendly articles to enhance visibility.
- Automatic meta titles, descriptions for each article.
- Automatically generated slugs.

### Dark Mode
- Eye-friendly dark theme for the website.

### Article Tags
- Categorize articles with tags for easier navigation; display article count next to tags.

### Home Page Dynamics
- Load the six most recent articles with pagination support.

### View Counter
- Track and display the number of views for each article.

### Database
- Utilize Postgres from Vercel for data management.

### Search
- Search by title, content, and tags.
