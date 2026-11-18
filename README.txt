# Santa Gorgonzola — Main Website, Celebration Themes & Inventory Studio

This package is based on the existing Santa Gorgonzola homepage and inventory update. The original handmade-cardboard website, Gifts & Patches catalogue and browser-local Inventory Studio remain intact. The Celebration Themes gallery has 18 clickable illustrated design concepts, including nine upgraded premium-themed pictures, and an expanded custom-order form.

## Preview
Open index.html in a browser, or serve this directory with `python3 -m http.server 8000` and visit http://localhost:8000. Existing patch images are in assets/patch_crops/ and the new theme images are in assets/themes/.

## Publish the update
Extract the ZIP. Upload index.html and both assets folders to the same website directory, preserving their paths. Back up the current live index.html first. If you've already edited your inventory in the browser, export a JSON inventory backup before changing files, then import it if needed. The new page preserves the original inventory seed and local storage keys.

## Custom-order theme selector
- Choose an event and a collection filter (Kids, Treats, Flowers & lights, Seasonal, Milestones).
- Click a design example to preselect its theme and suggest a filling in the custom-order form. The customer's selected event is carried over.
- The selected picture stays visible on the form. A theme-specific personalization prompt lets the customer describe changes to the design. Customize name/number, shape, size, colors, budget, quantities, fillings, cardboard wrapper/finish, open or closed construction, optional extras and special requests.
- Submit to open an email draft addressed to santagorgonzola27@gmail.com. The customer must send that email. Reference photos can be attached in their email app. There is no automatic submission or processing of payments.
- The theme photographs are generated design inspiration, not photographs of completed customer orders. The gallery discloses this; actual designs and figurine availability must be confirmed.

## Manage products
Scroll to the footer and click `Inventory Studio (local editor)`.
- Add/edit/delete products with name, SKU, category, description, CAD price, stock quantity and photo.
- Upload multiple product photos at once (they create hidden drafts until reviewed).
- Change quantities with +/- controls, show/hide products and feature products.
- Export/import an inventory backup in JSON.
- Click `Download publishable index.html` to embed your current catalogue into a new page, then replace the published index.html on your host. Keep both assets/patch_crops and assets/themes on your host as well. Newly uploaded product photos are embedded in the exported HTML.

## Important limitations
This is a static HTML website, not a secure live inventory backend. Inventory edits are stored only in the browser that made them. Customers elsewhere will not see edits until you export and upload the new index.html. There is no secure administrative login or synchronization. Cart only prepares an email inquiry; payments, stock reservation, transactional order saving and centralized inventory management are not connected. For real production use across devices, a server-side inventory service or Shopify backend is required. Photo crop quality varies; please review each patch and correct duplicate or incomplete crops.
