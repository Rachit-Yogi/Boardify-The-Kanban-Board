# Boardify - Kanban Board

Boardify is a simple, efficient, and visually appealing **Kanban board** designed to streamline task management. It allows users to create boards, add tasks, move them between columns, and track their progress in an intuitive way.

## Features 🚀

- **Create & Manage Boards** → Users can create multiple boards for different projects.
- **Drag & Drop Tasks** → Move tasks easily between columns.
- **Real-time Firestore Integration** → All updates are instantly synced.
- **Task CRUD Operations** → Create, update, and delete tasks seamlessly.
- **Customizable UI** → Modify board colors and background for a personalized experience.
- **Persistent Data** → All tasks and boards are stored in Firestore.
- **Error-Free Experience** → Fixed all major issues like task overwrites, unexpected deletions, and drag-and-drop errors.

## Tech Stack 🛠️

- **Frontend:** Next.js 14, TypeScript, Tailwind CSS, React DnD
- **Backend:** Firebase Firestore (for real-time data syncing)
- **Authentication:** Firebase Auth (if implemented)

## Installation & Setup ⚙️

Follow these steps to set up and run Boardify locally:

### **Prerequisites**
- Node.js (>=16.0.0)
- npm or yarn
- Firebase account

### **1. Clone the Repository**
```sh
git clone https://github.com/yourusername/boardify.git
cd boardify
```

### **2. Install Dependencies**
```sh
npm install
```

### **3. Set Up Firebase**
- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
- Enable **Firestore** and **Authentication** (if needed).
- Get your Firebase config and create a `.env.local` file:
```sh
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

### **4. Start the Development Server**
```sh
npm run dev
```

The app should now be running at `http://localhost:3000` 🚀

## Deployment 🚀

You can deploy Boardify on **Vercel** easily:
```sh
vercel
```
Or connect your GitHub repository directly to Vercel for automatic deployments.

## Usage 🏗️

1. Create a new board and name it.
2. Add columns such as "To Do," "In Progress," and "Done."
3. Drag and drop tasks between columns.
4. Customize board colors and backgrounds.
5. All changes are saved in real-time with Firestore.

## Contributing 🤝

We welcome contributions! Follow these steps:

1. Fork the repository 🍴
2. Create a new branch `git checkout -b feature-name`
3. Make changes and commit `git commit -m "Added new feature"`
4. Push to your fork `git push origin feature-name`
5. Open a Pull Request ✅

## License 📜

Boardify is open-source and available under the **MIT License**.

---

Made with ❤️ by the Boardify Team!

