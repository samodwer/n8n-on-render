# n8n on Render

This project allows you to deploy [n8n](https://n8n.io) on [Render.com](https://render.com) with minimal setup.

## Steps

1. Upload this project to your own GitHub repository.
2. Go to [https://dashboard.render.com](https://dashboard.render.com).
3. Click "New Web Service" and connect it to your GitHub repo.
4. Use the following settings:
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Instance Type**: Free

n8n will run on the default port (3000) unless changed.