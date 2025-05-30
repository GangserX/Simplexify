# Simplexify Learning Platform

Simplexify is a modern online learning platform designed to help users master new skills with interactive courses, personalized learning paths, and expert guidance.

## Features

- **Personalized Learning Paths**: Tailored learning experiences based on user goals and skill levels
- **Interactive Courses**: Engaging content across various disciplines
- **Expert Guidance**: Access to industry professionals and real-time feedback
- **Progress Tracking**: Comprehensive dashboard to monitor learning progress
- **Community Support**: Connect with peers and experts in a collaborative environment
- **AI-Powered Recommendations**: Smart course suggestions based on user preferences and goals

## Getting Started

1. Clone the repository: `git clone https://github.com/yourusername/simplexify.git`
2. Navigate to the project directory: `cd simplexify`
3. Open `index.html` in your browser or use a live server

## Firebase Configuration

The platform uses Firebase for authentication and database services. To set up Firebase:

1. Create a Firebase project at [firebase.google.com](https://firebase.google.com)
2. Enable Authentication (Email/Password, Google, and Facebook)
3. Create a Realtime Database
4. Copy your Firebase configuration to `auth.js`

## Deploying to Vercel

When deploying to Vercel, follow these steps to ensure Firebase authentication works correctly:

1. **Add Authorized Domains**: 
   - Go to the Firebase Console
   - Navigate to Authentication > Settings > Authorized Domains
   - Add your Vercel deployment domain (e.g., `your-app.vercel.app`)

2. **Update OAuth Consent Screen**:
   - If using Google Authentication, go to the Google Cloud Console
   - Navigate to "APIs & Services" > "OAuth consent screen"
   - Add your Vercel domain under "Authorized domains"
   - Under "APIs & Services" > "Credentials" > Your OAuth Client ID
   - Add your Vercel domain to "Authorized JavaScript origins"
   - Add `https://your-app.vercel.app/__/auth/handler` to "Authorized redirect URIs"

3. **Environment Variables**:
   - Consider moving Firebase configuration to environment variables
   - Set these in your Vercel project settings

## Technology Stack

- HTML5 & CSS3
- JavaScript (ES6+)
- Firebase (Authentication & Database)
- Chart.js (for analytics and progress tracking)

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add my new feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

# skill-x -semester 4th-

<br>
Team members: <br>
1.Ankit Halder <br>
2.Debajyoti Basu <br>
3.Biswajyoyi biswas<br>
4.Anwesha Bhatia <br>
5.Bishal pritam chowdhury<br>


changes can be done



