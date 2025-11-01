🤖 ExpoAI: Discover Your Next AI Tool & Comprehensive Guide

Project Overview

ExpoAI is designed to be the definitive mobile platform for discovering, researching, and rating the latest Artificial Intelligence (AI) tools across various categories (e.g., Image Generation, Code Assistants, Productivity, Data Analysis, and more).
In the rapidly evolving AI landscape, users often struggle to find reliable information and user-driven feedback on new tools. ExpoAI solves this by providing a curated, intelligently categorized, and community-rated collection, ensuring users can make informed decisions about the AI solutions that best fit their needs.
This application is developed natively for Android using the Kotlin language, ensuring a fast, performant, and modern user experience.


✨ Key Features
ExpoAI will offer the following core functionalities:

1.	Intelligent Discovery & Filtering:
   
○	Category-Based Browsing: Quickly navigate tools by functional categories (e.g., Text-to-Image, Healthcare AI, Financial Analysis).
○	Advanced Filtering: Filter tools based on pricing model (Free, premium, Paid), integration capabilities (API, Web-Only), and use case (Personal, Business, Developer).

2.	Comprehensive Tool Profiles:

○	Detailed Guides: Each tool features a dedicated page with an in-depth, summarized guide on how to use it, best practices, and limitations.
○	Direct Access: One-tap access to the tool's official website or source.
○	Technology Breakdown: Listing of the underlying AI model (if public, e.g., GPT-4, Stable Diffusion, Llama) used by the tool.

3. Learning & Skill Development:

○	Step-by-Step Tutorials: Carefully crafted guides showing how to use each AI tool effectively
○	AI Tool Quizzes: Test your knowledge with interactive quizzes for each AI tool category.
○	Tool Limitations & Considerations: Understand the boundaries and ethical aspects of each AI tool

4.	Modern Mobile Experience:

○	Seamless navigation and a dark/light mode option.
○	Optimized search functionality for instant results.




🛠️ Technology Stack

This project is built using modern, stable, and scalable technologies best suited for native Android development.

      Component	                  Technology	                                          Role

      Mobile Language            	Kotlin            	                         Primary language for native Android development. Ensures type safety and conciseness.
      Framework                  	Android SDK	                                  Core components and tools for building the application.
      UI/UX	                      Jetpack Compose    	                            Declarative and modern UI framework for building responsive interfaces.
      State Management          	Kotlin Flow        	                            Handling data streams and state across the application.
      Backend & Database        	Firebase (Firestore, Authentication)	          Scalable, real-time NoSQL database for tool data, user profiles, and ratings.
      image Loading               Coil/Glide	                                  Efficient and lightweight image loading for tool icons and screenshots.





📁 Project Structure
The project follows a modular, clean architecture pattern (e.g., MVVM) to ensure maintainability and testability.


      ExpoAI/
   
         app/
            src/main/kotlin/com/expoai/app/
               data/       # Repositories, Database Models (Firestore/Local)
               di/        # Dependency Injection modules (Hilt)
               domain/    # Use Cases, Business Logic
               presentation/ # UI Screens, ViewModels, Composables
               util/      # Constants, Extensions, Helper classes
         
            google-services.json # Firebase configuration
         build.gradle.kts   # Project level configuration




📝 Future Enhancements (Scope)

The following features are planned for future iterations to expand the platform's capabilities:

●	Offline Mode: Allowing users to view saved tool profiles and guides without an internet connection.
●	User Contribution: Implementing a system for vetted users to submit new AI tools for review.
●	AI Trend Analysis: A dashboard showing the fastest-growing tool categories or popular models based on user engagement.
●	Deep Linking: Enhancing navigation by supporting direct links to specific tool pages from external sources.




👥 Group Members & Index Numbers

This project was developed by the following team members:

               Name                                  Index Number
      K.M Dulash Priyashan	                      GWU-HICT-2021-09
      R.A.R Viduranga	                         GWU-HICT-2021-18
      S.T Dharmasena	                            GWU-HICT-2021-51
      S.S.D Karunarathna	                      GWU-HICT-2020-31
      M.K.D.G Thathsarani	                      GWU-HICT-2021-11

