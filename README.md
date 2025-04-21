<h1 align="center">💪  fit-fex-ai Fitness chatbot  🤖</h1>

## Highlights:

- 🚀 Tech stack: Next.js, React, Tailwind & Shadcn UI
- 🎙️ Voice AI Assistant (Vapi)
- 🧠 LLM Integration (Gemini AI)
- 🏋️ Personalized Workout Plans
- 🥗 Custom Diet Programs
- 🔒 Authentication & Authorization (Clerk)
- 💾 Database (Convex)
- 🎬 Real-time Program Generation
- 💻 Layouts
- 🎭 Client & Server Components

## Features
### **Your Smart Fitness Companion**  
Stay motivated with an AI assistant that gets to know you—your fitness goals, current fitness level, and even your preferences—so it can guide you every step of the way.  

### **Workouts Made Just for You**  
No more guessing! Get custom workout plans tailored to your strength, any injuries, and what you want to achieve—whether it’s building muscle, losing weight, or just staying active.  

### **Eating Right, Your Way**  
Personalized meal plans that fit your diet—vegan, keto, gluten-free, or anything else. Plus, we’ll keep your allergies and food dislikes in mind so you enjoy every bite.  

### **Easy Sign-In, No Hassle**  
Jump in quickly with your GitHub or Google account, or use a simple email and password—whatever works for you.  

### **Flexible Fitness Programs**  
Create, save, and switch between different workout plans, with only your latest one active. Perfect for when your goals change!  

### **Looks Great on Any Device**  
Whether you’re on a phone, tablet, or computer, the app adapts smoothly so your fitness journey stays seamless.  

## Setup .env file

```js
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

## Getting Started

1. Clone the repository
2. Install dependencies:

```shell
npm install
```

3. Set up your environment variables as shown above
4. Run the development server:

```shell
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This application can be easily deployed to Vercel:

```shell
npm run build
npm run start
```

Or connect your GitHub repository to Vercel for automatic deployments.

## Technologies Used

- **Next.js**: React framework for building the frontend and API routes
- **Tailwind CSS & Shadcn UI**: For styling and UI components
- **Clerk**: Authentication and user management
- **Vapi**: Voice agent platform for conversational AI
- **Convex**: Real-time database
- **Gemini AI**: Large Language Model for generating personalized fitness programs

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://clerk.com/docs)
- [Vapi Documentation](https://docs.vapi.ai)
- [Convex Documentation](https://docs.convex.dev)
- [Gemini AI Documentation](https://ai.google.dev/gemini-api)
