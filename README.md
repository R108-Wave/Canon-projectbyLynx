# Canon-projectbyLynx

## 🔗 Project Links
* **Live Deployed App:** [https://canon-flow-studio--ramcharan805077.replit.app]
* **Source Code Repository:** [https://github.com/R108-Wave/Canon-projectbyLynx]

## 🛠️ Installation & Setup Instructions
Follow these steps to clone and run the application locally:

1. **Clone the repository:**
   ```bash
   git clone <https://github.com/R108-Wave/Canon-projectbyLynx>
   cd <Canon-projectbyLynx>
   ```

2. **Install dependencies:**
   ```bash
   pnpm install
   ```
   *(Note: replace `pnpm` with `npm` or `yarn` depending on what you used)*

3. **Environment Variables:**
   Create a `.env` file in the root directory and add the following configuration keys (replace the placeholders with your own keys):
   ```text
   CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   GEMINI_API_KEY=your_gemini_api_key
   SESSION_SECRET=your_session_secret
   VITE_CLERK_PUBLISHABLE_KEY=your_vite_clerk_publishable_key
   ```

4. **Run the development server:**
   ```bash
   pnpm run dev
   ```

## 🏗️ Technical Architecture
* **Frontend UI:** React (`.tsx`) powered by Vite for fast hot-reloading.
* **Authentication:** Clerk for user authentication management.
* **Artificial Intelligence:** Gemini API for processing dynamic inputs.
* **Package Management:** Managed securely with `pnpm`.
