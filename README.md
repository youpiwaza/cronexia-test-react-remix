# cronexia-test-react-remix

[doc](https://remix.run/docs/en/main/start/quickstart)

```bash
npx create-remix@latest

# Need to install the following packages:
# create-remix@2.15.2
# Ok to proceed? (y) y

# npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
# npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported

#  remix   v2.15.2 💿 Let's build a better website...

#    dir   Where should we create your new project?
#          ./project

#       ◼  Using basic template See https://remix.run/guides/templates for more
#       ✔  Template copied

#    git   Initialize a new git repository?
#          No

#   deps   Install dependencies with npm?
#          No
#       ◼  Skipping install step. Remember to install dependencies after setup with npm install.

#   done   That's it!

#          Enter your project directory using cd ./project
#          Check out README.md for development and deploy instructions.

#          Join the community at https://rmx.as/discord

cd project
bun i
```

[build run](https://remix.run/docs/en/main/start/quickstart#build-and-run)

```bash
# build
npx remix vite:build

# serve
npx remix-serve build/server/index.js
```

Tuto intégré

```bash
# Cela crée un nouveau projet donc retour a juste avant
cd ..
npx create-remix@latest --template remix-run/remix/templates/remix-tutorial
# tout par défaut

cd my-remix-app
bun i
bun run dev
```

Pas le temps, fait jusqu'à Creating contacts, non inclus
