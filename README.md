# Blog Application

## Installation

### Prerequisites
- Node.js (v18 or higher)
- Git
- React.js knowledge
- Familiarity with TanStack Query, Tailwind CSS, and shadcn/ui.

### Setup Instructions

1. **Fork the repository**
   - Click **Fork** on GitHub to create a copy in your account.
   - Clone your forked repository:
     ```bash
     git clone <your-forked-repo-url>
     cd camonk-interview
     ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install required libraries** , ie, TanStack Query, Tailwind CSS, and  shadcn/ui
4. **Start the JSON Server (Backend API)**
   ```bash
   npm run server
   ```
   The API will run on `http://localhost:3001`

5. **Start the Development Server (in a new terminal)**
   ```bash
   npm run dev
   ```
   The app will run on `http://localhost:5173`


### API Endpoints

The JSON Server provides the following endpoints:

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/blogs` | Get all blogs |
| GET | `/blogs/:id` | Get a specific blog by ID |
| POST | `/blogs` | Create a new blog |




## Sample Blog Object

```json
{
  "id": 1,
  "title": "Future of Fintech",
  "category": ["FINANCE", "TECH"],
  "description": "Exploring how AI and blockchain are reshaping financial services",
  "date": "2026-01-11T09:12:45.120Z",
  "coverImage": "https://images.pexels.com/photos/6801648/pexels-photo-6801648.jpeg",
  "content": "Full blog content..."
}
```

description: A short summary of the blog  
content: The full content of the blog
