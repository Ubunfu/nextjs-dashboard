## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard
application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Learned Goodness Within

* Tailwind CSS
    * Global CSS classes make styling elements directly less painful
    * Sensible class name conventions, and good inline doc
* Image/Font Optimizing
    * Font imports and `<Image>` help optimize image renderings
* Layouts
    * Easy way to share UI structure across separate "pages"
    * Enable Partial Renderings for UI to keep things fast + efficient
* Next Project Structure
    * Nav is directory path based, relative from `/app`. Put page / layout files here.
    * Put other UI components to compose pages inside `/app/ui`
    * Put stuff like utils, defs, data fxns inside `/app/lib`
    * Static data like bundled images / icons can go in `/public`
* `<Link>`
    * Allows client-side navigation b/w pages
    * Next can pre-fetch pages sensibly based on the derived link tree
* Fetching Data
    * React Server Components allow secure data access w/o an API layer
    * Vercel SDKs allow easy data access w/in server components
    * Can use SQL directly or an ORM like Prisma
    * Parallelized data requests w/ `Promise.all()` help prevent waterfalls
* Static vs Dynamic Rendering
    * Static rendering fetches/renders data at deploy time (or configured revalidation time) and caches it.
    * Dynamic rendering does this for every request. Allows up-to-date or request-specific data to be shown.