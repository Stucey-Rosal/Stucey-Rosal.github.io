PROJECT COVERS
==============
These 10 covers were designed in Figma and exported at 1600x1000, then
converted to progressive JPEG (quality 86). Total weight: ~820KB for all ten.

Source file (edit here, then re-export):
  https://www.figma.com/design/6UeNUzN6lJeH73z7Ud6mWc

Each Figma frame is named "cover / <slug>" and maps to a file here:

  cover / kind-home-help  -> kind-home-help.jpg
  cover / ecommerce-ai    -> ecommerce-agents.jpg
  cover / chatbots        -> chatbots.jpg
  cover / ersy            -> ersy.jpg
  cover / umlu            -> umlu.jpg
  cover / bingo-bot       -> bingo-bot.jpg
  cover / quoz-ai         -> quoz-ai.jpg
  cover / ip-automation   -> ip-automation.jpg
  cover / compliance      -> compliance.jpg
  cover / ai-camera       -> ai-camera.jpg

TO REPLACE A COVER
  1. Edit the frame in Figma (or shoot a real screenshot).
  2. Export at 1600x1000, save over the .jpg here with the same name.
  3. Hard-refresh. No code change needed.

The filenames come from PROJECTS[].img in index.html. If you rename a file,
update that field to match.

NOTES
- 16:10 is the target ratio. Other ratios get center-cropped.
- If a file is missing, index.html falls back to its built-in SVG mockup.
  Nothing breaks - that fallback is still in the code as a safety net.
- Real client screenshots: BLUR OR CROP patient names, emails, and API keys.
- The DRAFT badge mechanism is still in the code (`draft:true` on a project
  entry renders an amber badge + warning banner). No project uses it now.
