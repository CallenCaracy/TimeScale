# TimeScale

# Personal Schedule Maker

Welcome to the **TimeScale** project! This application allows users to efficiently manage their schedules, track events, and plan activities in an intuitive and user-friendly interface.

# **Tech Stack**

The project uses the following technologies:

# **Frontend**
- **Bun**: A fast JavaScript runtime for modern applications.
- **TailwindCSS**: For styling and responsive design.

# **Backend**
- **Elysia**: A lightweight web framework for Bun to handle routing and APIs.
- **Supabase**: Backend-as-a-service to handle authentication, database, and real-time updates.

# **Language**
- **TypeScript**: For building a robust and type-safe application.

# **Project Structure**

```
project/
├── public/                   # Static assets like images, fonts, etc.
│   └── index.html            # Main HTML file
├── src/                      # Source code
│   ├── routes/               # Elysia route handlers
│   ├── middlewares/          # Middleware functions
│   ├── utils/                # Helper functions and utilities
│   ├── styles/               # Tailwind CSS or other styles
│   │   └── main.css          # Main CSS file
│   ├── main.ts               # Entry point for the Elysia app
│   └── config.ts             # Configuration (e.g., Supabase keys)
├── supabase/                 # SQL scripts or Supabase setup
├── bunfig.toml               # Bun configuration file
├── tailwind.config.js        # TailwindCSS configuration
└── README.md                 # Project documentation
```

# **Features**

- **User Authentication**: Secure login/signup using Supabase.
- **Schedule Management**: Add, edit, delete, and view events.
- **Real-time Updates**: Changes are instantly reflected across devices.
- **Responsive Design**: Optimized for desktop and mobile using TailwindCSS.

# **Getting Started**

# **Prerequisites**
- Install [Bun](https://bun.sh/).
- Have a [Supabase](https://supabase.com/) account and project set up.

# **Setup Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/personal-schedule-maker.git
   cd personal-schedule-maker
   ```

2. Configure dependencies:
   - Update `supabaseUrl` and `supabaseKey` in `src/config.ts` with your Supabase project details.

3. Install dependencies:
   ```bash
   bun install
   ```

4. Run Tailwind to build styles:
   ```bash
   tailwindcss -i ./src/styles/main.css -o ./public/style.css --watch
   ```

5. Start the development server:
   ```bash
   bun run src/main.ts
   ```

6. Open the app in your browser:
   - Navigate to `http://localhost:3000`.

# **Contributing**

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

# **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


# **Contact**

For questions or feedback, please reach out:

- **Email**: your-email@example.com
- **GitHub**: [your-username](https://github.com/your-username)

