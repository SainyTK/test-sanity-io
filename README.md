# Sanity.io Headless CMS Review
This repository is my playground to test Sanity.io's functionality. I'm searching for a modern CMS tool (I don't like Wordpress and PHP) to work with content-based website. The tool I'm finding should be compatible with my tech stack (TypeScript and JS Ecosystem).

After completing the get started section of Sanity.io, here're my notes:

1. `Schemas are defined using TypeScript`: This is a bit more complicated compared to some tools that offer no code schema defining.
2. `The UI is pretty`: I like the UI styling of Sanity dashboard.
3. `Comprehensive customizable`: While using code to control UI is complex, it offers a wide range of possible customization. 
4. `Rich text editor support`: Sanity supports rich text editor. This makes blog post generation much simpler for marketing team.
5. `Grapg Relational Object Quries (GROQ) based data retrival`: It uses another query language to retrive data. GROQ uses to query JSON data. I think the learning curve is now high for this one.

## How to fix VS code type warning
- Add `"moduleResolution": "NodeNext"` in `tsconfig.json` 