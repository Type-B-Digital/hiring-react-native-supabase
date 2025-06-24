# 📱 React Native Take-home Exercise: "Task Tracker Lite"

## 🧠 Objective

Build a simple task tracking mobile app using **React Native with Expo** and **Supabase** for backend services. The app allows users to manage a list of tasks.

## 📦 Repository Instructions

Welcome! This is a take-home exercise for potential React Native candidates at **Type B Digital**.

Please follow the steps below to complete the task:

1. **Fork** this repository to your personal GitHub account:  
   👉 https://github.com/Type-B-Digital/hiring-react-native-supabase

2. Create a new branch called `develop` in your fork.

3. Do all your work on the `develop` branch.

4. Once complete, create a **Pull Request** to the `main` branch of **your own fork** (not to the original Type B Digital repo).

5. Share the link to your forked repository and the pull request.

---

## 🕒 Estimated Time

2–4 hours

---

## 📝 Requirements

### Task Management

Users should be able to:

#### ✅ View Tasks

- Fetch and display all tasks from Supabase.
- Each task should have:
  - `title` (string)
  - `description` (optional)
  - `is_complete` (boolean)

#### ➕ Add Task

- A form (modal or inline) to add a new task with title and description.

#### ✏️ Update Task

- Tapping on a task should toggle its completion status (`is_complete`).

#### ❌ Delete Task

- Provide a button or swipe action to delete a task.

---

## 🖼️ UI Expectations

Keep the UI clean and minimal. Requirements:

- Use basic components (`FlatList`, `TextInput`, `Pressable`, etc.)
- Optional: Use a UI library like `react-native-paper` or `native-base` to speed up development.
- Provide basic user feedback (e.g., loading states, empty state UI, success/failure messages).

---

## 📦 Supabase Setup

You should:

- Set up your own Supabase project.
- Create a `tasks` table with the following schema:

```sql
id: uuid (Primary Key)
title: text
description: text
is_complete: boolean
created_at: timestamp
```

- No RLS rules are necessary for this exercise (you can use service role or enable public access just for testing).

---

## 💡 Bonus (Optional)

- Add a “pull to refresh” feature.
- Show task creation date in the list.
- Sort tasks (e.g., incomplete first).
- Add a basic animation on task toggle.

---

## 📤 Submission Checklist

- [ ] All features implemented (add, update, delete, list tasks)
- [ ] Code pushed to `develop` branch on your fork
- [ ] Pull request created on your **own fork**
- [ ] Link to the PR shared with us
- [ ] `README.md` includes setup instructions

---

## 🔍 Evaluation Criteria

- Functional correctness: add, update, delete, view tasks
- Code clarity and structure
- Usage of Supabase client
- UI/UX basics (usability, responsiveness)
- Thoughtfulness in edge case handling (e.g., loading, errors)

Good luck, and thank you for taking the time to complete this exercise!
