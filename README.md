# GIGWORK-SITE

A Next.js application with Vercel Speed Insights integration for real-time performance monitoring.

## Features

- **Next.js 16.4.6** - Latest stable version with App Router
- **Vercel Speed Insights** - Real-time performance monitoring and Core Web Vitals tracking
- **TypeScript** - Full type safety
- **React 19** - Latest React features

## Getting Started

### Development

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build

Build the production application:

```bash
npm run build
```

### Production

Start the production server:

```bash
npm run start
```

## Vercel Speed Insights

This project includes Vercel Speed Insights for tracking Core Web Vitals and performance metrics. The `SpeedInsights` component is integrated in the root layout (`app/layout.tsx`).

### What it tracks:

- First Contentful Paint (FCP)
- Largest Contentful Paint (LCP)
- First Input Delay (FID)
- Cumulative Layout Shift (CLS)
- Time to First Byte (TTFB)
- Interaction to Next Paint (INP)

### Viewing Metrics

After deploying to Vercel:
1. Go to your Vercel dashboard
2. Select your project
3. Click "Speed Insights" in the sidebar
4. View real-time performance data

## Deployment

The easiest way to deploy this application is to use the [Vercel Platform](https://vercel.com):

```bash
vercel deploy
```

Or connect your Git repository for automatic deployments on every push.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Speed Insights Documentation](https://vercel.com/docs/speed-insights)
- [React Documentation](https://react.dev)