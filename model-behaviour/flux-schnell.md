# FLUX Models – Observed Behaviour (Including FLUX Schnell)

This document describes observed behavior when generating images using FLUX-based models, including fast variants such as FLUX Schnell.

The notes below reflect consistent, repeatable behavior observed during testing.

## General characteristics

FLUX models prioritize speed, composition, and general scene layout. They tend to generate more variation between outputs compared to ChatGPT Image, but at the cost of fine-grained control.

Lower-capacity variants impose stronger internal priors.

## Strengths

FLUX models perform well at:

- Generating varied poses and compositions across runs
- Re-sampling stance, camera framing, and body orientation
- Handling environmental context (streets, towns, outdoor scenes)
- Responding to physical actions (standing, walking, waving)
- Rapid iteration during early prompt testing

FLUX is effective for exploring visual diversity once a prompt is broadly correct.

## Skin tone limitations

A consistent limitation observed in FLUX Schnell:

- Skin tone for African characters is clamped into a narrow, darker range
- Requests for lighter brown or medium-light skin tones are often ignored
- Lighting-based tone correction has little effect
- Comparative tone descriptions do not reliably change output

This behavior persists even when tone instructions are explicit.

Higher-capacity FLUX variants may reduce but do not fully eliminate this issue.

## Emotional and relational instruction limits

FLUX models struggle with high-level emotional or relational instructions.

Prompts that include:
- Internal emotional states
- Relational intent (e.g., affection, love, emotional motivation)
- Narrative explanations of behavior

often cause:
- Loss of photorealism
- Collapse of full-body framing
- Degradation in image quality
- Shift toward illustrative or low-detail rendering

FLUX responds best to **physical actions**, not emotional reasoning.

## Prompt overload behavior

When prompts become long or semantically dense, FLUX models tend to drop constraints in the following order:

1. Camera framing (full body)
2. Footwear and legs
3. Lighting realism
4. Texture detail

This is most noticeable when combining:
- Detailed anatomy
- Emotional intent
- Lighting control
- Interaction with the viewer

## FLUX-safe prompting pattern

FLUX performs best with prompts that emphasize:

- Physical posture and movement
- Simple facial expressions (e.g., “natural smile”)
- Clear but minimal anatomical guidance
- Concrete actions instead of emotional explanation

Example:
- “One arm raised in a casual wave” works
- “Waving happily at someone she loves” often breaks realism

## Recommended use

Use FLUX models to:
- Generate pose and composition variety
- Explore different stances, angles, and layouts
- Rapidly iterate on scene structure

Avoid relying on FLUX for:
- Fine skin tone control
- Subtle emotional expression
- Highly constrained, long prompts

For best results, design the prompt elsewhere, then use FLUX for variation.
