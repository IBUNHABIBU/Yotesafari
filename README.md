| Role                                   | Tailwind Color | Example Class                       | Mood                           |
| -------------------------------------- | -------------- | ----------------------------------- | ------------------------------ |
| **Primary (Earth Brown)**              | `stone-700`    | `bg-stone-700 text-white`           | Natural, grounded, safari feel |
| **Accent / Highlight (Sunset Orange)** | `orange-600`   | `bg-orange-600 hover:bg-orange-700` | Warm, energetic, sunset tone   |
| **Action / CTA (Savannah Green)**      | `green-600`    | `bg-green-600 hover:bg-green-700`   | Adventure, eco-friendly vibe   |

| Role                         | Tailwind Color | Example Class      | Description                      |
| ---------------------------- | -------------- | ------------------ | -------------------------------- |
| **Background Light**         | `stone-100`    | `bg-stone-100`     | Soft sand-like background        |
| **Text / Headings**          | `stone-900`    | `text-stone-900`   | Clean, strong, readable text     |
| **Subtext / Paragraphs**     | `stone-700`    | `text-stone-700`   | Balanced contrast for long reads |
| **Section Divider / Border** | `stone-300`    | `border-stone-300` | Subtle dividers between sections |


| Usage                       | Tailwind Color | Example          | Meaning                         |
| --------------------------- | -------------- | ---------------- | ------------------------------- |
| **Ocean / Coastal Tours**   | `sky-500`      | `bg-sky-500`     | Zanzibar, marine feel           |
| **Wildlife / Forest Tours** | `emerald-500`  | `bg-emerald-500` | Lively and fresh                |
| **Luxury / Premium Feel**   | `amber-500`    | `text-amber-500` | Gold touch for premium sections |

| Section                  | Suggested Classes                                                      |
| ------------------------ | ---------------------------------------------------------------------- |
| **Header**               | `bg-stone-800 text-white`                                              |
| **Hero Section**         | Background image overlayed with `bg-black/40` and text `text-stone-50` |
| **Destinations Section** | `bg-stone-100 text-stone-800`                                          |
| **Tour Packages**        | Cards with `bg-white shadow-md hover:shadow-lg`                        |
| **About / Why Us**       | `bg-orange-50`                                                         |
| **Testimonials**         | `bg-stone-50`                                                          |
| **Contact / Footer**     | `bg-stone-900 text-stone-100`                                          |




Header (bg-stone-800)
↓
Hero (bg-black/40 over image, CTA: bg-orange-600)
↓
Destinations (bg-stone-100)
↓
Tours (bg-white)
↓
About (bg-orange-50)
↓
Testimonials (bg-stone-50)
↓
Contact & Footer (bg-stone-900)


<!-- Main Homepage Container -->
<main class="homepage bg-stone-100">

  <!-- 1. Header - Dark earthy navigation -->
  <%= render 'partials/header' %>

  <!-- 2. Hero Section - Dark overlay with sunset CTA -->
  <%= render 'partials/hero' %>

  <!-- 3. Quick Stats - Natural stone background -->
  <%= render 'partials/stats_bar' %>

  <!-- 4. Why Visit - Warm orange background -->
  <%= render 'partials/why_visit' %>

  <!-- 5. Featured Destinations - Light sand background -->
  <%= render 'partials/featured_destinations' %>

  <!-- 6. Tour Packages - Clean white cards -->
  <%= render 'partials/tour_packages' %>

  <!-- 7. Experiences by Category - Stone background -->
  <%= render 'partials/experiences' %>

  <!-- 8. Special Offers - Green adventure CTAs -->
  <%= render 'partials/special_offers' %>

  <!-- 9. Travel Guides - Warm orange background -->
  <%= render 'partials/travel_guides' %>

  <!-- 10. Testimonials - Soft stone background -->
  <%= render 'partials/testimonials' %>

  <!-- 11. Newsletter - Stone background -->
  <%= render 'partials/newsletter' %>

  <!-- 12. Footer - Dark stone background -->
  <%= render 'partials/footer' %>

</main>