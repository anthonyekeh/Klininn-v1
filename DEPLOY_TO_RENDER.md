# Deploy KlinInn to Render - Simple Guide

## Step 1: Get the Code
Download this entire project folder and upload it to GitHub as a new repository.

## Step 2: Deploy on Render
1. Go to [render.com](https://render.com) and sign up
2. Click "New" → "Web Service"
3. Connect your GitHub repository
4. Render will automatically detect the `render.yaml` file
5. Click "Create Web Service"

That's it! Render will automatically:
- Create a PostgreSQL database
- Install all dependencies
- Build and deploy your app
- Set up SSL certificate

## Step 3: Configure Domain (After Deploy)
1. Once deployed, Render gives you a URL like `yourapp.onrender.com`
2. Go to your app's Environment tab on Render
3. Update the `REPLIT_DOMAINS` variable to your new domain

## What Gets Deployed
- Complete KlinInn cleaning marketplace
- Customer booking system with image uploads
- Cleaner dashboard and job matching
- Escrow payment simulation
- Authentication system
- All UI components and styling

## Need Help?
- Check Render's logs if deployment fails
- Ensure all environment variables are set
- Database should auto-configure via `render.yaml`

Your app will be live at `yourapp.onrender.com` in about 5-10 minutes!