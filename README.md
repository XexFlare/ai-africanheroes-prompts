# African Character Prompting

## What this repository is

This repository is a **practical prompt library** for improving how AI models generate African and African-descended characters.

It focuses on **realism**, **modern context**, and **accurate physical representation**, particularly in image generation tools such as:

- ChatGPT image generation  
- Leonardo AI  
- Z-Image  
- Stable Diffusion based systems  

Throughout this repository, you will be introduced to **Adewale** and **Thandiwe**.

They are used as recurring examples to demonstrate how well-constructed prompts can produce more believable, modern African characters. You will see how they are generated, what prompt structures are used, and how small changes in wording affect the final result.

### Adewale

Adewale is a Nigerian-born Yoruba man represented in a contemporary, urban setting. He is used as an example for generating modern African male characters with realistic structure, presence, and proportion.

### Thandiwe

Thandiwe is a Malawian-born Chewa woman represented in a modern African town setting. She is used as an example for generating contemporary African female characters with realistic anatomy, balance, and individuality, without defaulting to rural village imagery or large metropolitan city aesthetics.

These examples are not archetypes.  
They are **practical test cases** for evaluating prompt quality.
<br>
<br>
## The problem this repository addresses

Many current AI models consistently misrepresent African characters in a small number of repeatable ways:

- Over-defaulting to rural, tribal, or impoverished imagery
- Distorting body proportions and physical structure
- Collapsing diverse African populations into a single generic appearance
- Applying European fashion-model anatomy as a default
- Swinging between underrepresentation and caricature

These issues are not usually intentional.  
They are the result of uneven training data and weak default assumptions.
<br>
<br>

## What this repository is not

To avoid confusion, this project is **not**:

- A denial of physical or structural differences between populations
- A moral or ideological critique of AI companies

This repository is about **correcting technical failure modes** using better prompts.
<br>
<br>

## Core approach

This library works by:

1. Over-specifying context  
   (urban vs rural, modern vs historical, lifestyle and environment)

2. Encoding physical realism explicitly  
   (structure, proportion, posture, and presence)

3. Describing visual constraints through physical objects  
   (for example: footwear instead of saying “full body visible”)

The goal is **believable, contemporary representation**.
<br>
<br>

## Example characters (reference mascots)

The following two characters are used as **grounded reference examples** of modern African representation.

They are included to show how prompt structure affects realism in practice.
<br>
<br>

## Example 1: Adewale (Yoruba male)

Adewale represents a modern West African man in a contemporary, urban setting.

### Adewale – copy-paste this prompt into an Ai image generator to meet Adwale

Create a photorealistic full-body image of a modern African man named Adewale.

Context:
- Contemporary urban African city
- Middle-class professional lifestyle

Physical appearance:
- Yoruba facial features with natural individual variation
- Structurally solid male frame
- Broad shoulders and chest relative to waist
- Dense skeletal build with visible physical presence
- Natural muscle mass at rest, not lean or fashion-thin
- Balanced limb-to-torso proportions
- Upright, relaxed posture conveying confidence

Clothing:
- Modern, well-fitted casual-professional outfit
- Long-sleeve shirt or light jacket
- Tailored trousers
- Clean leather shoes worn on the feet, standing naturally on pavement

Style:
- Photorealistic
- Neutral, natural lighting
- High-resolution skin texture
- Clean, modern urban aesthetic

## Example 2: Thandiwe (Chewa female)

Thandiwe represents a modern Southern African woman in a contemporary, professional context.

### Thandiwe – copy-paste this prompt into an Ai image generator to meet Adwale

Create a photorealistic full-body image of a modern African woman named Thandiwe.

Context:
- Modern African town setting in southern Africa
- Clean streets and everyday town commerce
- Contemporary, non-metropolitan environment

Physical appearance:
- Chewa facial features with natural individual variation
- Woman in her mid-20s.
- light brown skin tone, closer to light skinned black women
- Even skin tone with minimal shadowing
- Full, well-proportioned female body typical of Southern African women
- Pronounced hip width with strong lower-body presence
- Fuller hips and thighs relative to waist and shoulders
- Solid skeletal frame with visible physical presence
- Natural body mass, weighing approximately 80kgs, bigger boned body
- Slightly lighter brown skin tone with natural variation
- Upright, relaxed posture

Facial expression:
- Warm, approachable expression
- Subtle, natural smile

Clothing:
- Modern, well-fitted everyday outfit, including skin tight leggings suitable for running a clothing store
- Practical town fashion, neat and contemporary
- Comfortable heels worn on the feet, standing naturally on clean pavement

Style:
- Photorealistic
- Bright, even daylight
- Soft lighting with low contrast
- Clean, realistic color tones

<br>
<br>


## How to use this repository

- Start with principles.md to understand why models fail
- Use base-prompts.md for general-purpose prompting
- Use full-body-prompts.md when proportions matter
- Use urban-context-prompts.md to avoid rural defaults
- Refer to common-failures.md when results drift
- Check tool-notes for platform-specific behavior

All prompts are designed to be **copied, adapted, and reused**.

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.
