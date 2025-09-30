# Ethery Rech

A modern web application built with **Next.js 15**, **React 19**, and **TypeScript**, designed with performance, scalability, and smooth user experience in mind.  
The project leverages popular libraries like **Tailwind CSS**, **Framer Motion**, **NextAuth**, and **Axios** for seamless UI, animations, authentication, and API communication.

---

## 🚀 Features

- ⚡ **Next.js 15** – App Router, Server Components, and optimized builds  
- 🎨 **Tailwind CSS** – utility-first responsive styling  
- 🌙 **Dark/Light Mode** with `next-themes`  
- 🔑 **Authentication** powered by `next-auth`  
- 📩 **Email Integration** via `emailjs/browser`  
- 🔄 **API Requests** with `axios`  
- 🗓 **Date Formatting** using `date-fns`  
- 🎬 **Animations** powered by `framer-motion`  
- 📰 **Markdown Rendering** with `remark` + `remark-html`  
- 📸 **Optimized Images** with `sharp`  
- 🛝 **Carousels & Sliders** with `react-slick` and `swiper`  
- 🔔 **Toast Notifications** with `react-hot-toast`  

---

## 📦 Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/)  
- **Language**: [TypeScript](https://www.typescriptlang.org/)  
- **UI**: [React 19](https://react.dev/) + [Tailwind CSS](https://tailwindcss.com/)  
- **Auth**: [NextAuth.js](https://next-auth.js.org/)  
- **Animations**: [Framer Motion](https://www.framer.com/motion/)  
- **Icons**: [Lucide](https://lucide.dev/), [Iconify](https://iconify.design/)  
- **Markdown**: [remark](https://github.com/remarkjs/remark)  
- **Other Tools**: `axios`, `sharp`, `swiper`, `date-fns`  

---

## 📂 Project Structure

```bash
ethery-rech/
├── app/                # Next.js App Router
├── components/         # Reusable UI components
├── lib/                # Helpers & utilities
├── pages/              # API routes/legacy support
├── public/             # Static assets
├── styles/             # Tailwind / global styles
├── types/              # TypeScript type definitions
└── package.json        # Project dependencies & scripts


git clone https://github.com/your-username/ethery-rech.git
cd ethery-rech


NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=secret_key
EMAILJS_SERVICE_ID=service_id
EMAILJS_TEMPLATE_ID=template_id
EMAILJS_PUBLIC_KEY=public_key



