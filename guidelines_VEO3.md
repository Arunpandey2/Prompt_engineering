Here's a detailed guideline for Google Vertex AI's **VEO3 video generation** based on the official documentation, structured for optimal results:

---

### **1. Core Prompt Structure**
Use this template for effective prompts:  
`[Subject] + [Action/Verb] + [Context/Setting] + [Style/Artistic Details] + [Camera/Technical Specs]`

**Example**:  
> "A golden retriever puppy running through a sunlit meadow, cartoon style, cinematic wide-angle shot with shallow depth of field."

---

### **2. Key Prompt Elements**
| **Element**       | **Details**                                                                 | **Examples**                                  |
|-------------------|-----------------------------------------------------------------------------|----------------------------------------------|
| **Subject**       | Primary focus (person/animal/object)                                        | "Astronaut," "Cyberpunk cat," "Vintage car"  |
| **Action**        | Dynamic verbs describing movement                                           | "dancing," "melting," "flying through clouds"|
| **Setting**       | Environment/background context                                              | "underwater coral reef," "neon-lit cityscape"|
| **Style**         | Artistic/aesthetic direction                                                | "Studio Ghibli anime," "1960s poster art," "photorealistic 4K" |
| **Camera Specs**  | Shot composition & movement                                                | "slow-motion," "drone overhead shot," "Dutch angle" |
| **Lighting**      | Lighting conditions                                                         | "volumetric god rays," "bokeh sunset lighting" |

---

### **3. Pro Tips for High-Quality Output**
- **Specificity Wins**:  
  ❌ *"A bird flying"*  
  ✅ *"Majestic bald eagle soaring over snowy mountains at dawn, 8K wildlife documentary style"*
  
- **Negative Prompts**: Exclude unwanted elements  
  `"without text, watermarks, or humans"`

- **Motion Intensity**:  
  Use adverbs: *"gently flowing"* vs. *"violently splashing"*

- **Temporal Cues**:  
  Specify time progression: *"time-lapse of flowers blooming"*, *"slow-motion splash"*

---

### **4. Advanced Techniques**
- **Sequential Actions**:  
  `"A seed sprouting → growing into a sunflower → blooming in timelapse"`

- **Mood & Atmosphere**:  
  Add descriptors: *"dreamy atmosphere," "chaotic cyberpunk energy," "serene minimalist"*

- **Physics/Effects**:  
  Specify: *"fluid dynamics," "smoke simulation," "celestial particles"*

---

### **5. Limitations to Avoid**
- **❌ Overly complex scenes**: (e.g., "20 characters interacting in a battle")
- **❌ Text rendering**: VEO3 doesn't generate legible text
- **❌ Precise continuity**: Not ideal for multi-shot narratives
- **❌ Real trademarks**: Avoid branded content requests

---

### **6. Sample Prompts**
1. *"Oil painting of stars swirling into a galaxy, Van Gogh style, with dynamic brushstroke animation"*  
2. *"Robotic arm 3D-printing a crystal on Mars, photorealistic NASA footage, red dust storm background"*  
3. *"Steampunk dragon flying over Victorian London at night, cinematic trailer lighting, rain effects"*

---

### **7. Optimization Workflow**
1. **Iterate**: Start simple → add details in subsequent runs
2. **Test Variations**: Change 1-2 elements per generation (e.g., swap "sunset" → "foggy morning")
3. **Combine**: Use `Video Editor` to stitch multiple outputs
4. **Refine**: Add post-production effects (upscaling, color grading)

---

### **8. Ethical Guidelines**
- Avoid generating:  
  ✗ Real people's likenesses  
  ✗ Violence/hate content  
  ✗ Misinformation scenarios  
  *(Adheres to Google's [Responsible AI](https://ai.google/responsibility/) policies)*

---