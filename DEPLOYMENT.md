# Deployment Guide

## Vercel Deployment

### Environment Variables (Optional)
If you want to use Supabase features, add these to your Vercel project:
- `VITE_SUPABASE_URL` - Your Supabase project URL
- `VITE_SUPABASE_ANON_KEY` - Your Supabase anonymous key

The app will work without these variables in offline mode.

### Build Settings
- Framework Preset: Vite
- Build Command: `npm run build`
- Output Directory: `dist`
- Install Command: `npm install`

### Troubleshooting Blank Page
1. Check browser console for errors (F12)
2. Verify environment variables are set in Vercel dashboard
3. Check build logs for any errors
4. Ensure `dist` folder is being generated correctly
