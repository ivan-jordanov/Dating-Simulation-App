# DevMatch – A Full-Stack Dating App Clone (Angular + .NET 8)

Welcome to DevMatch, this is a modern dating web app clone built from scratch as part of a hands-on Udemy course. This project is a full-stack application developed using the latest versions of **Angular (17)** and **.NET 8**, aiming to simulate a real-world dating app environment and teach full-stack development through practical experience.

> **Project type:** Educational  
> **Tech Stack:** Angular • ASP.NET Core Web API • SignalR • Bootstrap • Automapper  
> **Course-based build:** Developed alongside the instructor with personal codebase maintained for tracking progress  

---

## What This App Can Do

### Authentication & Authorization
Login and register using token-based authentication. Client-side route protection ensures a secure and intuitive user experience.

### User Profiles
Browse through user profiles with support for photo uploads, image gallery display, and more.

### Filtering, Sorting, Paging
Dynamic user list filtering, pagination, and sorting help mimic real-world user discovery features.

### Private Messaging
Real-time chat powered by **SignalR**, including presence indicators and live messaging.

### Photo Gallery Integration
Upload and manage profile photos with a slick UI using third-party gallery components.

### Admin Controls & Roles (optional in course)
While not implemented, the groundwork allows for future role-based access controls.

### Live Deployment Ready
The app was configured for deployment to both IIS and a Linux server via Heroku (as taught in the course).

---

## What I Learned

This wasn’t just about following along—it was about **leveling up** as a developer:

- **End-to-end full-stack workflow**: From backend API creation with .NET to building dynamic front ends with Angular.
- **Client-side routing and guards**: Protecting routes and managing client state effectively.
- **Forms in Angular**: Deep dive into Template-driven & Reactive forms, with validation techniques.
- **WebSocket basics with SignalR**: Real-time communication made simple.
- **Using Automapper**: Streamlining object-to-object mapping on the backend.
- **UI design with Bootstrap**: Fast and clean component styling.
- **Version control discipline**: Managed my own GitHub repo throughout the course, tracking changes and progress independently.

---

## Tech Stack

| Frontend      | Backend        | Utilities / Libraries     | Deployment    |
|---------------|----------------|----------------------------|----------------|
| Angular 17    | .NET 8 Web API | SignalR, Bootstrap, RxJS   | IIS, Heroku    |
| HTML & SCSS   | Entity Framework Core | Automapper, JWT Auth   |                |

---

## How to Run It

1. Clone the repo:
```
git clone https://github.com/your-username/devmatch.git
```

2. Install and run the Angular client:
```
cd client
npm install
ng serve
```

3. Run the .NET API:
```
cd ../API
dotnet run
```

> **Note:** Make sure you have the required environment set up (.NET 8 SDK, Node.js, Angular CLI).

---

## Final Thoughts

This app isn’t about reinventing Tinder—it's about sharpening real-world development skills by implementing a feature-packed full-stack app line by line. From the first terminal command to deploying live, this course taught me how to approach full-stack projects confidently.

---

## Credits

Built by me during the Udemy course:  
**“Build an app with ASPNET Core and Angular from scratch”**  
Instructor: *Neil Cummings*
