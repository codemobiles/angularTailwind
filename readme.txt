# follow the instruction in this page
https://tailwindcss.com/docs/guides/angular


# fix style conflict between material and tailwind
# https://tailwindcss.com/docs/preflight
add this in tailwind.config.js
---------------------------------------------------
corePlugins: {
    preflight: false,
},
