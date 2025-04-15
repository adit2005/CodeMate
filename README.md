# CodeMate

A real-time collaborative code editor that allows multiple users to code together simultaneously. Features include real-time editing, chat functionality, and support for multiple programming languages.

## Manual Installation

1. Clone the repository
2. Create `.env` files in both client and server directories:

   Client `.env`:
   ```
   VITE_BACKEND_URL=http://localhost:3000
   ```

   Server `.env`:
   ```
   PORT=3000
   ```

3. Install dependencies:
   ```bash
   # Install client dependencies
   cd client
   npm install

   # Install server dependencies
   cd ../server
   npm install
   ```

4. Start the servers:
   ```bash
   # Start the server (in server directory)
   npm run dev

   # Start the client (in client directory)
   npm run dev
   ```

5. Open `http://localhost:5173` in your browser to use the application. 