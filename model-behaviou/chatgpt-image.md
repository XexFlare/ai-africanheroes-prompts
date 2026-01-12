# ChatGPT Image – Observed Model Behaviour

This document describes observed behavior when generating images using ChatGPT Image generation.

The notes below are based on repeatable testing and are intended to help users understand how to prompt the model effectively.

## General characteristics

ChatGPT Image generation is highly responsive to detailed prompts and follows instructions closely. It excels at producing a strong, coherent reference image when given clear constraints.

It tends to converge on a single, well-formed composition rather than generating wide variation across multiple attempts.

## Strengths

ChatGPT Image performs particularly well at:

- Following detailed anatomical instructions
- Respecting body mass, proportions, and skeletal structure
- Responding to explicit skin tone descriptions when the model supports it
- Rendering facial expressions such as smiles or direct eye contact
- Maintaining photorealistic lighting and texture when prompts are clear
- Producing a strong “canonical” version of a character

It is especially useful for validating whether a prompt is logically sound and capable of producing a realistic result.

## Canonical composition behavior

A consistent behavior observed is **composition convergence**.

When given a detailed prompt and asked to generate multiple images:
- The model tends to reuse the same pose
- Leg positioning, hip angle, stance, and camera distance remain similar
- Footwear interpretation often remains identical
- Variation is mostly limited to:
  - Facial micro-features
  - Shirt or clothing color
  - Minor hairstyle changes

Requests such as “create another image” or “generate a variation” do not reliably produce structural changes.

## Clothing and pose coupling

Certain clothing items implicitly lock pose and framing.

For example:
- “Skin-tight leggings” frequently results in a standardized fashion-style stance
- Weight distribution and leg spacing often remain fixed across generations

In these cases, clothing description acts as a proxy for pose.

## Forcing variation

ChatGPT Image requires **structural changes** to produce meaningful variation.

Effective levers include:
- Changing the action (walking, waving, stepping, turning)
- Changing camera angle (side view, three-quarter view, lower angle)
- Changing ground interaction (one foot on a curb, mid-step)
- Changing clothing category (leggings to skirt or trousers)

Soft requests such as “variation” or “different outfit” are usually insufficient.

## Emotional and interaction prompts

ChatGPT Image handles emotional and relational cues well.

Instructions involving:
- Smiling
- Looking at the viewer
- Friendly gestures
- Emotional warmth

are generally respected and rendered accurately.

This makes ChatGPT Image suitable for scenes involving human interaction or expressive intent.

## Recommended use

Use ChatGPT Image to:
- Design and validate prompts
- Produce a high-quality reference image
- Test realism, anatomy, and tone
- Explore emotional expression and interaction

For batch variation or randomized outputs, pair it with other image generation tools.
