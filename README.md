# Sawarigo Static Website

This is a static website for Sawarigo.

## Deployment with Vercel

To deploy this website directly to production using Vercel, follow these steps:

1. Make sure you have the [Vercel CLI](https://vercel.com/docs/cli) installed globally on your machine:
   ```bash
   npm i -g vercel
   ```

2. Open a terminal in this project folder (`Sawarigo_Static_Website_Spaced`).

3. Run the following command to deploy it to production:
   ```bash
   vercel --prod
   ```

4. Follow the prompts in the terminal to configure the project. Vercel will automatically detect that it is a static website and deploy it.

## Local Development

You can simply open `index.html` in your browser to view the website locally, or use a tool like Live Server.

## Downloading Code from Vercel

If you ever need to download your project code back from Vercel (for example, if you misplaced your local files), you can do so from the Vercel Dashboard:

1. Log in to your [Vercel Dashboard](https://vercel.com/dashboard).
2. Select your project (e.g., `Sawarigo_Static_Website_Spaced`).
3. Go to the **Deployments** tab.
4. Click on the latest deployment from the list.
5. In the top right corner or under the deployment options (the three dots `...`), look for the **Download** option to download the source code as a `.zip` file. 

*(Note: This option is available if you uploaded the files via the Vercel CLI directly. If your project is connected to GitHub/GitLab, you should download the code directly from your Git repository.)*
