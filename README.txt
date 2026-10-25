Medora — Anatomy Topic Pages Prototype (v2)

UPLOAD ALL FILES IN THIS FOLDER TO THE ROOT OF YOUR GITHUB PAGES REPOSITORY. Do not upload only one HTML file.

FILES:
- index.html: Medora homepage and main search.
- topic.html: standalone topic page, opened by search as topic.html?q=...
- supabase-config.js: authentication configuration template. Email sign-in stays inactive until a real Supabase project is configured.
- ATTRIBUTION.txt: anatomical model sources, credits, and licensing notes.

WHAT THIS BUILD DOES:
1. Searching for القلب or الرئة opens a dedicated organ page rather than leaving the answer as inline search cards. The page contains an in-site summary, key facts, a rotatable 3D organ model, a list of anatomical parts, and references.
2. Clicking a part in the part list opens its own topic.html?q=... page with more detailed information, a part-focused schematic, adjacent part links, a source section, and a 3D part viewer when the source model contains a separable, named structure.
3. Brain-region search opens a dedicated page with the 3D brain explorer and part links. The in-model region selector provides a link to the detailed region page.
4. For heart and lung components, the 3D substructure viewer is loaded only when the user presses its button, to reduce unnecessary data use on mobile. It attempts to isolate a named component from the referenced GLB file. If the file does not expose a matching anatomical node name, the viewer says so and the part-specific schematic remains available; it does not claim a false isolation.
5. The page «مبادئ المواد الفعّالة» gives a general educational explanation of active ingredients, inactive ingredients/excipients, and source verification. It does not provide a product/brand matching list or medication-use recommendations.
6. The existing 8 main fields and 88 sub-specialty entries are retained.

KNOWN LIMITATIONS:
- This is still a prototype, not a complete medical search engine or a clinical tool.
- The external 3D models require internet access. Some assets, especially lung models, can be large. Load the isolated component model only when needed.
- Exact hit testing depends on the names and structure stored in the source GLB; not every component can be guaranteed to be isolatable. Use the named part list when direct click recognition does not work.
- Saved items and recent searches are local to the browser. Cross-device account syncing needs a configured backend.
- Real email registration is not enabled until Supabase credentials and redirect settings are configured.

PUBLISHING:
Upload these files (not the ZIP itself) directly into the repository root so index.html, topic.html, supabase-config.js and ATTRIBUTION.txt are side by side. Then enable GitHub Pages from branch main / root.

QUICK TESTS AFTER PUBLISHING:
Search for: القلب, الرئة, المخ, المخيخ, البطين الأيسر, الصمام التاجي, الحويصلات الهوائية, الفص الجبهي, طب القلب, المواد الفعالة.

Educational use only; not for diagnosis or treatment.
