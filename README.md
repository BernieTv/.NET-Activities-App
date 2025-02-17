# 🚀 Full-Stack Awesomeness: ASP.NET Core WebAPI & React 🎯

Hey there! 👋 Welcome to this full-stack web app that’s built using **ASP.NET Core WebAPI** on the backend and **React** on the frontend. We’ve followed **Clean Architecture** and implemented **CQRS + Mediator pattern** to keep things scalable, maintainable, and just straight-up cool. Plus, we threw in **real-time chat** and **modern front-end magic** to make it a seamless experience. 🪄✨

---

## 🏠 Tech Stack - What’s Under the Hood?

### Backend 🖥️

- **ASP.NET Core WebAPI** ⚙️ (Super-fast and cross-platform API framework)
- **CQRS + Mediator Pattern** 🛠️ (Keeping commands and queries separate for a clean codebase)
- **Entity Framework Core** 🛂 (ORM that makes database stuff a breeze)
- **ASP.NET Core Identity** 🔒 (Handles authentication like a pro)
- **AutoMapper** 🔄 (Transforms objects like a wizard)
- **SignalR** 📡 (Real-time web communication for instant updates)
- **Azure Deployment** ☁️ (Because cloud is the future)

### Frontend 🌐

- **React** ⚛️ (Because why not? It’s awesome!)
- **TypeScript** 📝 (Say goodbye to annoying JS bugs)
- **React Router** 🛠️ (For that smooth single-page app experience)
- **React Hook Form & Zod** 🗋l️✅ (Handling forms like a boss)
- **Material UI** 🎨 (Gives your UI a sleek and stylish look)
- **React Query** 🔍⚡ (Fetch, cache, and sync data like a pro)
- **MobX** 💡 (Simple and scalable state management)

---

## 🌟 Why This Project is 🔥

- 🚀 **Full-Stack Vibes**: ASP.NET + React combo for max efficiency
- 🔑 **Secure Login System**: Users can sign up, log in, and stay protected
- 💬 **Real-Time Chat**: SignalR-powered chat that works instantly
- 🎨 **Sleek UI**: Built with **Material UI**, so it looks modern and fresh
- 🗋l️ **Smart Forms**: React Hook Form + Zod makes input handling a breeze
- 🔍 **Supercharged API Calls**: React Query makes data fetching smooth
- 📸 **Photo Uploads & Profiles**: Users can upload and manage profile pics
- 📊 **Data Optimization**: Paging, sorting, and filtering to keep things snappy
- ☁️ **Azure Hosting**: Deploy once, scale forever
- 🏠 **Future-Proof Codebase**: Clean Architecture means easy maintenance

---

## ⚡ Get Started - Set It Up Like a Pro 🛠️

You can check out the **live demo** of this project [here](https://reactivities-course.azurewebsites.net/). 🎉

### 🔑 Accessing the App

To log in, either **sign up with a valid email** or use **GitHub login** (email verification is required in the published version).

#### 📌 Prerequisites

Make sure you have the following installed:

1. **.NET SDK v9** 💻
2. **Node.js (18+ or 20+)** 🚀
3. **Git** 🛠️ (to clone the repo)

### 1️⃣ Clone the Repo 🗂️

```sh
 git clone https://github.com/BernieTv/.NET-Activities-App
 cd .NET-Activities-App
```

### 2️⃣ Restore dependencies 🖥️

```bash
# From the root folder
 dotnet restore

# Move to client folder and install dependencies
 cd client
 npm install
```

### 3️⃣ Set Up Photo Uploads (Optional) 🌐

- Create a file `appsettings.json` inside `Reactivities/API`
- Copy-paste this config:
  ```json
  {
    "Logging": {
      "LogLevel": {
        "Default": "Information",
        "Microsoft.AspNetCore": "Warning"
      }
    },
    "CloudinarySettings": {
      "CloudName": "REPLACEME",
      "ApiKey": "REPLACEME",
      "ApiSecret": "REPLACEME"
    },
    "AllowedHosts": "*"
  }
  ```
- Sign up for a free **Cloudinary** account at [cloudinary.com](https://cloudinary.com) 🌥️
- Replace **REPLACEME** with your actual Cloudinary API keys 🔑

### 4️⃣ Run the App Locally 🎠

```bash
# Start the API
cd API
dotnet run

# Open another terminal and start the React frontend
cd client
npm run dev
```

### 5️⃣ Access the App Locally ✨

- Open **https://localhost:3000** in your browser 🌍
- Log in using these test credentials:
  ```plaintext
  Email: bob@test.com, tom@test.com, or jane@test.com
  Password: Pa$$w0rd
  ```

---

## 🤝 Wanna Contribute? Let’s Collab! 🚀

Got ideas? Found a bug? Want to add a feature? PRs are always welcome! 🎉 Open an issue, start a discussion, or just dive in and make things better.

---

## 📝 License - No Strings Attached!

This project is licensed under the **MIT License** 📞. Go ahead, use it, modify it, make it yours.

---

🚀 Happy coding, rockstar! 🖥️🔥
