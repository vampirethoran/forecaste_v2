# Merit, my foot!
**Forecaste** started out as an interactive, branched storytelling project that deals with caste and class trauma in academic circles. In India, it is not just enough for one to have the privilege to get educated. Casteist/classist humiliation rituals are almost a rite of passage – almost, because the ✨passage✨ never happens.

The endgame here is to evolve into a visually driven, drag-and-drop game creation studio-suite-whatever one must call it :) 

![Last Commit](https://img.shields.io/github/last-commit/beneathatree/forecaste_v2) 
![Top Lang](https://img.shields.io/github/languages/top/beneathatree/forecaste_v2)
#### Find the app deployed at [demo.forecaste.in](demo.forecaste.in)

## Getting Started
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

Install dependencies:

```bash
pnpm install
# or
npm install
```

Run the development server:

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Dependencies

gsap, tailwind

## Current Project Structure

- `app/layout.tsx`: Global layout (title banner, 400px-wide frame, control bar with Reset and Audio).
- `app/page.tsx`: Landing scene with layered SVG (`College`, `People`, `Ground`) and a “Start!” CTA.
- `app/*/page.tsx`: Story scenes (e.g., `adjustment`, `isolate`, `small-bonds`, `organize`, etc.) that progress the narrative via choices.

## Some Noteworthy Stuff

- To add a new route and thereby extend the story, fork this repository, or open an issue.
- Add new routes by creating new folders inside `/app` directory.
- Find the current game flow [here](https://github.com/beneathatree/forecaste_v2/blob/main/public/images/forecaste_flow.jpeg)