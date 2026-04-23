# 🚀 Angular Learning Guide (For React + TypeScript Developers)

This guide is designed for developers who already know **TypeScript, React, and CSS frameworks (Bootstrap, SCSS, Tailwind)** and want to quickly learn Angular in a practical way.

---

# 📌 Why Angular?

Angular is a **full-fledged framework** that provides:
- Built-in routing
- Dependency Injection (DI)
- State handling (via RxJS/Signals)
- Strong structure for large applications

👉 Think of Angular as:
> React + Router + State + Architecture (all included)

---

# 🆚 React vs Angular

| React | Angular |
|------|--------|
| Library | Full framework |
| JSX | HTML Templates |
| Hooks | Services + RxJS |
| Props | @Input() |
| State | Component variables / Signals |

---

# 🏗️ Project Setup

```bash
npm install -g @angular/cli
ng new angular-learning
cd angular-learning
ng serve

---

# 📂 Angular Project Structure
src/
 ├── app/
 │   ├── app.component.ts
 │   ├── app.component.html
 │   ├── app.component.css
 │   └── app.routes.ts
 ├── main.ts

---

# 📅 Day-wise Learning Plan

    🟢 Day 1 – Setup & Basics
    Learn:
    - Angular CLI
    - Project structure
    - What is a component?
    
    🟢 Day 2 – Data Binding
    Types:
    - Interpolation → {{ value }}
    - Event binding → (click)="fn()"
    - Property binding → [value]="data"
    -Two-way binding → [(ngModel)]
    - Practice:
        - Counter app

    🟢 Day 3 – Directives
    Learn:
    - *ngIf
    - *ngFor
    - ngClass
    - Practice:
    - List rendering
    - Conditional UI
    
    🟡 Day 4 – Component Communication
    Learn:
    - @Input() (Parent → Child)
    - @Output() (Child → Parent)
    - EventEmitter
    
    🟡 Day 5 – Routing
    Learn:
    - Route configuration
    - routerLink
    - router-outlet
    - Practice:
        - Multi-page app
    
    🟡 Day 6 – Services & Dependency Injection
    Learn:
    - Services
    - @Injectable()
    - Dependency Injection
    - Practice:
    - Move logic from component → service
    
    🟠 Day 7 – API Calls
    Learn:
    - HttpClient
    - GET requests
    - Practice:
        - Fetch data from API
    
    🟠 Day 8 – RxJS (Important)
    Learn:
    - Observable
    - subscribe()
    - pipe()
    - operators: map, switchMap
    - Concept:
    - Promise = single value
    - Observable = stream of values
    
    🟠 Day 9 – Forms
    Types:
    - Template-driven forms
    - Reactive forms (recommended)
    - Practice:
    - Login form with validation
    
    🔴 Day 10 – Advanced Topics
    Learn:
    - Standalone components
    - Signals (modern state)
    - Interceptors
    - Route Guards

---

# 💻 Project-Based Learning
    
    🟢 Project 1: Todo App
    - Add / delete tasks
    - Use basic components
    - Use directives
    
    🟡 Project 2: Dashboard
    - API integration
    - Table display
    - Filtering
    
    🔴 Project 3: Advanced App
    - Convert an existing React project to Angular
    - Example: Graph Crafter
    ⚡ Best Practices
    - Use Standalone Components
    - Keep logic in Services
    - Avoid heavy logic in components
    - Use RxJS properly
    - Follow folder structure
    
    🧠 Common Challenges
    - Topic	Difficulty
    - RxJS	Hard
    - Dependency Injection	Medium
    - Templates	Easy
    
    📚 Recommended Learning Strategy
    - 30% theory
    - 70% hands-on coding
---