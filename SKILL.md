---
name: create-travel-doodle-photo
description: Generate new images or edit uploaded photos in a realistic-photography plus youthful travel-magazine hand-drawn doodle collage style. Use for 文生图, 图生图, travel doodle, scrapbook photo collage, marker-outline, street-zine, or requests to apply this established style to people, vehicles, animals, architecture, food, music, travel, or everyday documentary scenes. For edits, preserve the original identity, anatomy, objects, text, composition, crop, aspect ratio, and dimensions unless the user explicitly requests a change. Do not use for pure illustration, vector graphics, simple color filters, or typography-led poster design.
---

# Create Travel Doodle Photo

Create a realistic photographic scene with a carefully art-directed handmade doodle layer. Keep the photograph dominant; treat the graphics as physical marker, ink, brush, tape, sticker, and paper interventions rather than a flat digital filter.

## Read the style rules

Read these references before prompting the image tool:

- Read [references/style-spec.md](references/style-spec.md) for the fixed visual grammar, intensity, paper limits, hierarchy, and failure conditions.
- Read [references/prompt-patterns.md](references/prompt-patterns.md) for the text-to-image and image-to-image prompt structures and scene-adaptation patterns.

## Choose the workflow

### Generate from text

1. Extract the subject, action, environment, camera position, time, mood, and requested aspect ratio.
2. Add only scene details that materially support the request. Do not invent brands, slogans, extra characters, or unrelated props.
3. Identify one physical or compositional motion path, such as walking direction, road curve, wheel rotation, sound vibration, cooking arc, gaze, wind, steam, water current, or architectural perspective.
4. Build all doodle elements around that path so the result feels designed for the scene rather than templated.
5. Use the built-in image generation tool and produce one image unless the user asks for variants.

### Edit an uploaded photo

1. Treat the uploaded photo as the edit target, not a loose reference.
2. Lock all photographic invariants before describing the new graphic layer:
   - identity, facial features, expression, skin tone, hair, body proportions, hands, fingers, limbs, and pose;
   - animal anatomy, fur pattern, eyes, paws, tail, and posture;
   - vehicle geometry, wheels, panels, lights, mechanical parts, and road contact;
   - architecture, objects, product structure, existing text, signage, numbers, logos, reflections, perspective, lighting, crop, and camera angle.
3. Change only the graphic treatment unless the user explicitly requests another edit.
4. Place most graphics in negative space, behind the focal subject, or immediately around its contour. Never cover faces, eyes, hands, text, important products, or key mechanical details.
5. Preserve the source aspect ratio and pixel dimensions when requested. Prompt for the original ratio first. If the generated ratio differs materially, regenerate. If it is within 2%, resize once with high-quality Lanczos filtering to the exact source dimensions; do not add borders or crop important content.
6. Use the built-in image generation tool and save non-destructively.

## Construct the composition

1. Establish one unmistakable focal subject.
2. Build three graphic depth planes:
   - broad cobalt-blue or teal brush energy behind the subject;
   - imperfect yellow contours and orange action marks around the subject;
   - sparse thin black arrows, dots, stars, notes, quotation marks, clouds, or abstract marks in the foreground.
3. Keep graphic presence at the approved medium level. Never let paper, brush strokes, or symbols become the subject.
4. Use no more than two tiny torn-paper accents and keep them at safe outer edges.
5. Extend the photograph and graphics to every edge. Add no frame, white margin, or poster panel.

## Generate and inspect

After generation, inspect the output against these checks:

- The base still reads as a real photograph.
- The focal subject remains clear and unobstructed.
- The doodles follow the scene's actual action or geometry.
- Yellow, blue/teal, orange, black, and sparse magenta are balanced.
- Torn paper obeys the size and count limits.
- Faces, hands, anatomy, vehicles, products, buildings, and existing text remain coherent.
- No giant letters, numerals, headlines, watermarks, duplicated subjects, extra limbs, fake borders, or pure-illustration drift appear.

If one check fails, revise only the failed dimension and regenerate. Do not globally increase or decrease every graphic element unless the user asks for a new intensity level.

## Deliver

Render the image inline. For project-bound or batch work, keep every final deliverable in the workspace with clear numbered filenames. Report the final paths and the user-facing content prompt; do not overwhelm the user with the entire internal style block unless requested.
