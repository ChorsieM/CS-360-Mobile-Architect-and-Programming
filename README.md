# CS-360-Mobile-Architect-and-Programming

Development Summary & Reflection
App Goals & User Needs
The WeightTrackingApp was developed to help users track their weight over time with a clean, simple interface and secure data handling. The main goal was to meet user needs for easy daily logging, historical data access, and optional goal tracking notifications. This app addresses the common need for personal health tracking without requiring cloud sync or complex setup.

Screens & User-Centered Features
To support a user-centered design, the app includes:

A Login Screen for basic authentication

A Data Grid Screen that displays daily weight entries using a RecyclerView

A Permissions Screen to handle optional SMS notifications when a goal is met

The UI was built with accessibility and simplicity in mind—clear text, minimal steps, large touch targets, and logical navigation flow. These choices made the app intuitive for new users and ensured a clean experience on mobile screens, contributing to its success.

Development Approach & Techniques
I approached coding by separating logic into distinct modules (database, UI, login, notification). I used Kotlin and Android SDK components like SQLiteOpenHelper, RecyclerView, and Intent. My strategies included:

Building and testing each feature in isolation

Using dummy/test users during early development

Keeping code modular for future scalability

These techniques help reduce bugs, improve readability, and make updates easier—beneficial habits for future Android projects.

Testing Strategy
I tested the app using both Android Emulators and a physical device. This included:

Checking database reads/writes

Verifying input validation (e.g., weight formats)

Confirming layout responsiveness across screen sizes

Testing ensured each component worked correctly and exposed bugs in permission handling and layout edge cases. This process was essential for catching problems early and building a stable app.

Innovation & Challenges
One of the biggest challenges was implementing optional SMS functionality without interrupting user flow or requiring unnecessary permissions. To solve this, I added permission prompts only when needed and made SMS alerts an opt-in feature. This maintained user trust and streamlined the experience.

Standout Component
The area where I demonstrated the most skill was in building the SQLite database integration. I used clean SQL queries, secure data handling, and connected the local database to dynamic UI components effectively. This showed my understanding of persistent data and how to build an app that works offline—valuable skills for any Android developer.
