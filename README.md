# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey Brooke20240901!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/Brooke20240901/skills-getting-started-with-github-copilot/issues/1)

---

# Debugging Guide

## Backend (FastAPI)

1. **Run the server with reload and debug output:**
   ```bash
   uvicorn src.app:app --reload --port 8000
   ```
   - The `--reload` flag auto-restarts the server on code changes.
   - Check the terminal for error messages and stack traces.

2. **Add print statements or use logging:**
   - Insert `print()` or `import logging` in your Python code to trace variables and flow.

3. **Test API endpoints:**
   - Use [http://localhost:8000/docs](http://localhost:8000/docs) for the interactive Swagger UI.
   - Use `curl` or Postman to send requests and inspect responses.

## Frontend (JavaScript)

1. **Open the app in your browser:**
   ```bash
   $BROWSER http://localhost:8000
   ```

2. **Use browser developer tools:**
   - Press `F12` or right-click → "Inspect" to open DevTools.
   - Use the "Console" tab to view errors and `console.log()` output.
   - Use the "Network" tab to inspect API requests and responses.

3. **Add `console.log()` statements:**
   - Insert `console.log(variable)` in `app.js` to trace values and execution.

## Common Issues

- **CORS errors:** Make sure frontend and backend are served from the same origin or configure CORS in FastAPI.
- **API not reachable:** Ensure the FastAPI server is running and accessible at the expected port.
- **Static files not loading:** Check the static files path and server logs for errors.

## Tips

- Restart the server after code changes if not using `--reload`.
- Check both backend and frontend logs for clues.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

