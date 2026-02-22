# Score Cat Photo Quality

A comprehensive evaluation function that scores cat photographs for technical quality and visual clarity on a scale from 0 to 1. This function combines objective technical assessment with an appreciation for how effectively a photograph captures and communicates the essence of its feline subject.

## Overview

`score-cat-photo-quality` provides photographers, social media platforms, and cat enthusiasts with consistent, principled evaluation of photographic excellence. Rather than relying on subjective taste or arbitrary metrics, this function identifies photographs that achieve technical mastery while effectively showcasing their subject.

## Input

The function accepts a cat photograph with the following structure:

```json
{
  "url": "string (required) - The URL or file path to the cat photo image",
  "title": "string (optional) - A title or label for the photo",
  "photographer": "string (optional) - Credit to the photographer"
}
```

The photograph may be taken with any camera or device, in any setting (natural light, studio, candid, posed), and can depict one or more cats in various situations and contexts.

## Output

A numerical quality score between **0 and 1**, where:
- **0.9 - 1.0**: Exceptional - Technical excellence combined with captivating subject presentation
- **0.7 - 0.9**: Excellent - Strong technical execution with clear subject visibility
- **0.5 - 0.7**: Good - Solid technical quality with minor shortcomings
- **0.3 - 0.5**: Fair - Notable technical or clarity issues that diminish impact
- **0.0 - 0.3**: Poor - Significant technical or clarity problems

## What Gets Evaluated

The function comprehensively evaluates cat photographs across four core dimensions:

### 1. Technical Execution
Assesses the photographer's command of their craft, including:
- Proper exposure with appropriate balance between highlights and shadows
- Thoughtful composition and framing
- Effective use of focus and depth of field
- Overall image clarity and visual comfort

### 2. Lighting Quality and Effectiveness
Evaluates how well the photograph's lighting serves the subject:
- Appropriate direction and intensity of light
- Ability to reveal detail and texture in the cat's fur and features
- Creation of flattering shadows and dimension
- Avoidance of harsh overexposure or problematic underexposure

### 3. Fine Detail Clarity and Color Reproduction
Measures the sharpness and accuracy of visual information:
- Clarity of fine details (whiskers, fur texture, eye definition, nose detail, paw pads)
- Accuracy of color reproduction across the cat's coat, eyes, and environment
- Faithful capture without distracting color casts, oversaturation, or loss of accuracy
- Visual distinctness of the cat as the primary subject

### 4. Subject Sharpness and Focus Quality
Assesses focus precision and depth of field appropriateness:
- Whether the cat is sharp and in-focus with focus on the eyes
- Appropriateness of depth of field to the composition
- Preservation of fine details through sharp focus
- Effective rendering of the cat's features and form

## Use Cases

### For Photographers
- Receive objective feedback on photographic technique and areas for improvement
- Benchmark images against consistent quality standards
- Identify which of their shots best represent their feline subjects
- Develop understanding of what constitutes excellence in cat photography

### For Content Platforms
- Identify and promote high-quality cat photos to users
- Organize content libraries with consistent quality assessment
- Surface images that consistently engage and delight viewers
- Maintain curated collections that meet professional standards

### For Social Media and Online Communities
- Help users discover the best cat photography
- Encourage quality over quantity in photo sharing
- Recognize and celebrate excellent feline photography
- Build engagement around technically accomplished images

### For Enthusiasts and Curators
- Develop personal collections of exceptional cat photographs
- Understand the technical elements that make cat photography compelling
- Make informed decisions about which images deserve to be saved and shared
- Learn to appreciate photographic craft in feline portraiture

## Sub-Functions

This function is composed of specialized evaluation sub-functions that assess specific dimensions of cat photo quality:

- **Sharpness and Focus Assessment**: https://github.com/ObjectiveAI-claude-code-1/assess-cat-focus-quality
- **Lighting Quality Evaluation**: https://github.com/ObjectiveAI-claude-code-1/evaluate-cat-lighting
- **Detail Clarity and Color Reproduction**: https://github.com/ObjectiveAI-claude-code-1/assess-detail-and-color-accuracy

Each sub-function is automatically invented to provide deep, specialized evaluation of its respective quality dimension.

## Philosophy

This function embodies the belief that photographic quality is identifiable through consistent application of principles that have guided visual arts for centuries. A great cat photograph serves both **truth and beauty**—it captures what is genuinely there while presenting it in a way that moves, engages, or illuminates. In evaluating cat photographs through this lens, we celebrate not just technical perfection, but those rare moments when a photographer captures something that deserves to endure: a revelation of character, a composition that elevates the everyday into the extraordinary, a truthful moment that speaks to the unique nature of its feline subject.

Quality is not arbitrary. It is recognizable, teachable, and worthy of celebration.

---

*Built with ObjectiveAI | Evaluating Cat Photography with Precision and Heart*